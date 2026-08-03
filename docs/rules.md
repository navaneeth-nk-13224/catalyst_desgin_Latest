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

20. **ALWAYS use the Table DS component — NEVER hand-build tables** — Import the ZCatalyst Table component (`f5c2c94ee6b8bddb779ff1d82125cc73b044fdfd` for Boxy, `ccaff166b021b69c24a3e554ea7e10e06c7609b9` for Stretch). Do NOT create tables from raw frames, text nodes, or dividers. The Table component is a pre-built DS component where each cell variant corresponds to its column header type (e.g. a "Status" column uses the Status cell variant, a "Name" column uses the Name cell variant). Respect this cell-variant-to-header-type relationship when customizing columns.

21. **ALWAYS use the Pagination DS component — NEVER hand-build pagination** — Import the ZCatalyst Pagination component (`826469f58d1a4e68df306ac04da418b009ab9380`). Do NOT build custom pagination with raw frames, buttons, or text nodes. Place the Pagination instance directly below the Table component.

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
