# ZCatalyst Design System — Design Rules

> **Read this file before creating any Figma page using the MCP workflow.**
> These rules prevent known errors and ensure consistent, high-quality output.

---

## Mandatory Rules

0. **ALL frames = auto layout** — NEVER group elements. Every container must use `layoutMode='VERTICAL'|'HORIZONTAL'` with proper auto layout. Keep layer names clean and descriptive. No manual positioning.

1. **ALL colors = variables** — Never use raw hex values. Always bind colors via `setFill(node, V.variable)` using imported design variables.

2. **ALL UI elements = components** — Every button, input, badge, toggle, etc. MUST be an imported component instance. Never recreate UI elements from scratch.

3. **ALL text = text styles** — Use `await t.setTextStyleIdAsync(s.id)` to apply text styles. Do NOT use the sync setter `t.textStyleId = s.id` — it throws an error with `documentAccess: dynamic-page`.

4. **Styles reference** — Look up text style keys and color variable keys from `docs/zcatalyst-styles.md` before building.

5. **FILL after appendChild** — `layoutSizingHorizontal='FILL'` MUST be set AFTER `parent.appendChild(node)`. Setting it before throws an error.

6. **Cannot appendChild to INSTANCE** — You must call `detachInstance()` first or use plain frames. Direct append to component instances is not allowed.

7. **Async APIs only** — Use `getVariableByIdAsync`, `getMainComponentAsync`, `importComponentByKeyAsync`, etc. Sync versions do not exist in the Plugin API.

8. **Variable paint binding** — Use `setBoundVariableForPaint()` to bind color variables. Do NOT use `setBoundVariable('fills', ...)`.

9. **No opacity in fills** — Fill paint objects ignore opacity. Use `node.opacity` separately.

10. **Never set FILL on component internals** — Only set `layoutSizingHorizontal='FILL'` on direct children you create. Touching internal nodes of component instances breaks icons and layout.

11. **No spacer frames in title rows** — Instead of adding an empty frame as a spacer, set the heading text to `layoutSizingHorizontal='FILL'` so it naturally pushes buttons to the right.

12. **BADGE/TIMELINE variables don't import** — Use OTHER SHADES collection keys (Green 1–4, Red 1–4, Orange 1–4) for semantic colors. BADGE and TIMELINE keys throw "could not find variable" errors.

13. **`layoutGrow` only accepts 0 or 1** — For progress bars, use fixed-width rectangles inside a clipped auto-layout track. Do NOT use fractional values.

14. **`primaryAxisSizingMode` only accepts `'FIXED'` or `'AUTO'`** — No other values are valid.

15. **Timeout recovery** — If `figma_execute` times out (30s), content is partially built. Query what exists, then continue from there — never rebuild from scratch.

16. **Page deletion** — Cannot remove the current page. Switch to another page first, then delete.

17. **DS file is READ-ONLY** — Never add, build, modify, or change anything in the Design System file. It is a published library — only import components and variables from it.

18. **Always use DS components over hand-built elements** — If a component exists in the DS (Badges, Table, Tabs, etc.), import it. Never recreate UI elements with raw frames, ellipses, or text — even to save execution time during timeouts. Split work across multiple calls instead.

19. **Always configure Sub Header** — The Sub Header inside the Layout component must NOT be hidden. Set the title via `setText(subH, 'Feature Names', 'Page Title')` and toggle boolean properties (Back Navigation, Primary Tab, Button 1, etc.) as needed for each page. Key: `ef423f31a7636493f6d094a031c0a493a94c5667`.

20. **ALWAYS use the Table DS component — NEVER hand-build tables** — Import the ZCatalyst Table component (`f5c2c94ee6b8bddb779ff1d82125cc73b044fdfd` for Boxy, `ccaff166b021b69c24a3e554ea7e10e06c7609b9` for Stretch). Do NOT create tables from raw frames, text nodes, or dividers. The Table component is a pre-built DS component where each cell variant corresponds to its column header type (e.g. a "Status" column uses the Status cell variant, a "Name" column uses the Name cell variant, etc.). Respect this cell-variant-to-header-type relationship when customizing columns. **When using the Boxy variant, always wrap the Table instance in a card frame** (`bg: V.cardsBgPrimary, border: V.cardsBorderDefault, radius: 8`) — never place the table directly on the bare body background.

21. **ALWAYS use the Pagination DS component — NEVER hand-build pagination** — Import the ZCatalyst Pagination component (`826469f58d1a4e68df306ac04da418b009ab9380`). Do NOT build custom pagination with raw frames, buttons, or text nodes. Place the Pagination instance directly below the Table component. **ONE pagination per table — never two.** The DS Table already has a built-in pagination row; do NOT add a second standalone Pagination instance on top of it.

22. **ALWAYS use the DS Stepper component — NEVER hand-build steppers** — Use the Stepper component from the "2.0 Components" library (key: `2f4c11929da9e40ed54bb4a872209bc5ee81af29`). Never build a stepper from raw ellipses, lines, or text nodes. It is a 3-step component (success / active / disabled); step labels are TEXT nodes named `"Step 1"`. `_Stepper_Source` (ef09b7...) is an internal helper and is NOT importable.

23. **ALL input forms go inside a DS Popup component — always** — ANY user input form (create, edit, configure, upload settings, wizard, etc.) MUST be placed inside a DS Popup/Modal component. Never place a form directly on the page body as a plain card. When a stepper flow is inside a popup, the popup width must be wide enough (800–900px) for the entire stepper to render in a single horizontal row — steppers must never truncate or wrap. Search the DS for the Popup component before building; do NOT hand-build modal overlays.

24. **Section header layout pattern** — Every section card header row must follow this structure:
    - **LEFT**: A VERTICAL frame (`gap: 4`) containing the title (H5) and a subtitle/description (Body 3) directly below it.
    - **RIGHT**: Any buttons or search fields placed adjacent in the same HORIZONTAL row, each with `layoutSizingHorizontal = 'HUG'` (auto width — never fixed width on buttons here).
    - The HORIZONTAL outer row uses `counterAxisAlignItems = 'CENTER'`; the title group uses `layoutSizingHorizontal = 'FILL'` to push actions to the right.
    - Never place a section title without a subtitle. Never give buttons a fixed width in this context.

25. **Table columns — always match cell variant to column type** — The DS Table component has 10 column types and 14 cell variants. Every column header MUST use the matching type and cell variant. Never leave all columns as generic "Avatar & Name" / "Description" / "Id" when the actual data differs.

    | Column header | _Table_Col Type | _Table_Cells_Main Variant |
    |---|---|---|
    | Name / Bucket / User / File | `Avatar & Name` | `Name` |
    | Email | `Avatar & Email` | `Email` |
    | Date / Time / Created / Modified / Updated | `Date & Time` | `Date`, `Time`, or `Date and Time` |
    | Description / Notes / Details | `Description` | `Description` |
    | ID / Ref / Key | `Id` | `Id` |
    | Status / Active / Health | `Name` or `Avatar & Name` | `Status` |
    | Job / Execution / Run state | `Name` | `Execution Status` |
    | Type / Icon indicator | `Icon Only` | `Icon with Text` |
    | Inline action button | `Name` | `Button` |
    | Actions (three-dot menu) | `Threedot` | `Threedot` |
    | Select row | `Checkbox` | `Check Box` |
    | Enable / Disable toggle | `Toggle Switch` | — |

---

## Importable Semantic Color Variables

> Only keys from the **OTHER SHADES** collection are importable. BADGE and TIMELINE collection keys will fail.

| Variable | Key | Hex (Light) | Use For |
|---|---|---|---|
| Green 1 | `c5b468027686a2c9dc6e05aeac52f132148b8770` | #29B260 | Green dots, text |
| Green 4 | `f83e5196695146c60ada6141fc9037940c520346` | #EAF7EF | Green light bg |
| Red 1 | `7da69489ce9f98f8ddfb85a66724a1d6d74fb409` | #E22020 | Red dots, text |
| Red 4 | `5dc42d49093cedf272fbcf74f6da1009406fd2b8` | #FFEFEF | Red light bg |
| Orange 1 | `d1a680043888628f6988e070a825a235984cc094` | #C98E06 | Orange dots, text |
| Orange 4 | `196dd6808474b55bb51f7959f6884c003909651c` | #FFF3D7 | Orange light bg |

---

## Badge Variant Keys
| Color | Default | Small | Dot |
|---|---|---|---|
| Primary | `5d541380661e1a2de2cfb5557b50b58d8ff53425` | `7e9959c67a04d3bc86d044d6c7ff0ec5c0c40e46` | `32eb7f5e36be45eafc9b50ca25c371bbf1c4b17e` |
| Green | `8ca7161ecb86188fe2ab3881babe81a04c22c56c` | `b6387e358b9fa3b26b1253ca8d19050c6d6582a4` | `e3ed01f887449258bc7b4307cf0160472fe8b6c3` |
| Red | `e25c954ef6fdb7830d089cb529d3122e554fbd7b` | `901b403c42eed59e985407a60d0fc88254940dbb` | `e3a7f9b82d19a1166afbe3bd75678330fab9408b` |
| Orange | `67c996cc2e2e5af5cd59e9a4ea521693096370bc` | `541fcffc7b2c3a17a386e4787733dc5b17b32378` | `a9a7d7ab5bec13e8d0580c9f2029cf6b65f1ca13` |
| Grey | `97e1c6fb2b071a83dbaf197ba25a214cf0ef0a55` | `1c983b8dbd7dc166da1bc020e40456f5c1d49c93` | `dca49157612adcb7cb4138c9edc4389b869d202f` |
| Purple | `c09fe6f42b2ee25ce781bc0cf29eaf4469a335cc` | `1ea3aff575f3fa55c63b6b27952f104fdcc46873` | `bac9e7bb8bcb17fb6c52437a70449bece0a66166` |

---

## Reference Files

| File | Contains |
|---|---|
| `docs/zcatalyst-design-system.md` | 59 component sets + Layout component with keys, variants, props, text node names |
| `docs/zcatalyst-styles.md` | 26 text styles + 500+ color variables with keys |
| `.github/copilot-instructions.md` | Full workflow auto-loaded by Copilot (clone, vars, helpers, patterns) |
