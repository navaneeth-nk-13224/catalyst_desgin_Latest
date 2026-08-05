# Clean Layout Rules

## Purpose

These rules define only layout structure.

They do **not** modify:
- Colors
- Typography
- Component styling
- Border radius
- Shadows
- Existing design system tokens
- Existing component spacing inside components

These rules only control how components are positioned relative to each other.

---

# 1. Respect Component Boundaries

Treat every existing component as a single layout object.

Never:
- Change internal padding
- Change internal spacing
- Resize internal elements
- Override component styles

Only position the component itself.

---

# 2. Use One Parent Alignment

Every screen should have one primary alignment axis.

Examples:
- Left aligned
- Center aligned
- Two-column grid

Avoid mixing multiple unrelated alignment systems.

---

# 3. Align to Common Edges

Neighboring components should share common edges whenever possible.

Examples:
- Left edges line up
- Right edges line up
- Centers line up (when intentionally centered)

Avoid random offsets.

---

# 4. Maintain Consistent Gaps

Use one spacing value for similar relationships.

Examples:
- Card → Card
- Input → Input
- Section → Section

Avoid manually adjusting spacing for individual elements.

Spacing should communicate hierarchy rather than decoration.

---

# 5. Group Related Components

Components that belong together should appear visually close.

Increase spacing only when separating different groups.

Spacing should communicate relationships.

---

# 6. Separate Sections Clearly

Each major section should have noticeably larger spacing than items within that section.

Example hierarchy:

Section
    Item
    Item
    Item

Large gap

Section
    Item
    Item

---

# 7. Keep Reading Direction Clear

Arrange content in a predictable reading flow.

Usually:

Top → Bottom

or

Left → Right

Avoid layouts that force unnecessary eye movement.

---

# 8. Use Predictable Container Widths

Components belonging to the same content group should generally share the same container width.

Avoid arbitrary width changes unless content requires them.

---

# 9. Respect Container Boundaries

Components should remain visually inside their parent container.

Avoid:
- Floating outside containers
- Touching container edges
- Overflow without purpose

---

# 10. Avoid Edge Crowding

Maintain breathing room between the layout and screen edges.

Outer spacing should remain consistent throughout the page.

---

# 11. Preserve Visual Rhythm

Components should appear placed on an invisible rhythm.

Avoid uneven vertical jumps caused by inconsistent spacing.

---

# 12. Keep Layout Density Consistent

Within a section, maintain similar spacing density.

Do not alternate between crowded and sparse layouts without structural reasons.

---

# 13. Minimize Alignment Variations

Within the same content group, avoid switching between:
- Left alignment
- Center alignment
- Right alignment

Choose one.

---

# 14. Stack Before Nesting

Prefer vertical stacking over unnecessary nested containers.

Reduce layout complexity whenever possible.

---

# 15. Avoid Isolated Elements

Single components should not appear disconnected.

Every component should belong to:
- a group
- a section
- or the overall layout

---

# 16. Preserve Existing Component Sizes

Do not resize components unless required by layout constraints.

Allow components to use their intended dimensions whenever possible.

---

# 17. Keep Section Widths Predictable

Major sections should generally share consistent widths.

Avoid layouts where every section uses a different width.

---

# 18. Minimize Visual Noise Through Structure

Do not solve layout problems by adding more containers.

Only introduce wrappers when they create meaningful structure.

---

# 19. Avoid Uneven Margins

Outer margins around related components should remain visually balanced.

Large differences should have structural reasons.

---

# 20. Maintain Clear Hierarchical Levels

Every element should belong to one of these structural levels:

Screen

→ Section

→ Group

→ Component

Avoid unnecessary intermediate layers.

---

# 21. Prefer Consistent Placement

Repeated interface patterns should appear in the same position throughout the experience.

Examples:
- Primary actions
- Filters
- Headers
- Navigation
- Search

Consistency improves scanability.

---

# 22. Limit Competing Focal Areas

A single viewport should present one dominant content region.

Avoid layouts where multiple unrelated groups compete equally for attention.

---

# 23. Use Whitespace as Structure

Whitespace should define:
- groups
- sections
- hierarchy

Never rely on empty space as decoration alone.

---

# 24. Maintain Grid Discipline

When using a grid:

- Align components to grid lines.
- Avoid partial alignment.
- Avoid arbitrary offsets.

Breaking the grid should be intentional and rare.

---

# 25. Balance Layout Weight

Distribute components so that one side of the layout does not feel unintentionally heavier than another.

Consider:
- component size
- spacing
- grouping

rather than visual styling.

---

# 26. Avoid Layout Exceptions

If two components share the same role, they should follow the same layout rules.

Avoid creating one-off spacing or alignment exceptions.

---

# 27. Prioritize Structural Simplicity

If two layouts communicate the same information equally well, prefer the one with:

- fewer containers
- fewer alignment systems
- fewer spacing variations
- fewer nesting levels

Simpler structure generally results in cleaner layouts.

---

# Scope

These rules intentionally do **not** define:

- Typography
- Font sizes
- Colors
- Shadows
- Border radius
- Icons
- Illustrations
- Component appearance
- Animation
- Branding
- Design language

They only improve structural organization and layout cleanliness while remaining compatible with existing component libraries and design systems.
