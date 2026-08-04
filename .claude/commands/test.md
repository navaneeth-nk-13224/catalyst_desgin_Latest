# Audit Screen

Audit a built Figma screen for ZCatalyst Design System compliance.

## Instructions

Run this audit after building any screen:

1. **Variable bindings** — run the audit snippet to find any unbound color fills:
```js
const det = figma.currentPage.findOne(n => n.name.startsWith('F'));
const issues = [];
det.findAll(n => {
  if ('fills' in n && n.fills?.length) {
    const f = n.fills[0];
    if (f.type === 'SOLID' && !f.boundVariables?.color) issues.push(n.name + ' (' + n.id + ')');
  }
});
return issues.length ? 'Unbound: ' + issues.join(', ') : 'All fills bound ✓';
```

2. **Component compliance** — check no raw frames are used as tables/pagination/buttons
3. **Auto-layout** — every container must have `layoutMode !== 'NONE'`
4. **Sub Header** — must be configured (title + at least one action button)

## Example Usage

```
/sc:test Audit the Machine Clusters screen for compliance
```
