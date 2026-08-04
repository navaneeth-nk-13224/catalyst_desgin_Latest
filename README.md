# ZCatalyst Design System — Copilot MCP Workflow

AI-powered Figma screen builder for the **ZCatalyst Design System** using GitHub Copilot + the official Figma MCP server.

---

## What This Repo Is

This repository is the **knowledge base and workflow config** that enables GitHub Copilot to build production-quality Figma screens using the ZCatalyst Design System — with zero manual dragging.

You describe a screen ("build a machine cluster list view"), and Copilot generates and executes the Figma Plugin API code to build it, using the correct DS components, variables, and layout patterns.

---

## How It Works

```
GitHub Copilot (Agent Mode)
        ↓  reads
.github/copilot-instructions.md   ← auto-loaded workflow + helper code
docs/rules.md                     ← 21 mandatory build rules
docs/zcatalyst-design-system.md   ← component keys, variants, text nodes
docs/zcatalyst-styles.md          ← color variable keys, text style keys
        ↓  calls
Official Figma MCP Server (mcp.figma.com)
        ↓  executes JavaScript via Plugin API
Figma File (your working file)
```

---

## Setup

1. **Figma MCP** — add to your `.vscode/mcp.json`:
   ```json
   { "servers": { "figma": { "url": "https://mcp.figma.com/mcp", "type": "http" } } }
   ```
2. **Enable the ZCatalyst Design System library** in your Figma working file (Assets → Libraries → toggle ZCatalyst ON)
3. Open this repo in VS Code with Copilot in Agent mode
4. Ask Copilot to build a screen — it reads the docs automatically

See `docs/SETUP-GUIDE.md` for full setup instructions.

---

## Repository Structure

```
.github/
  copilot-instructions.md   Auto-loaded by Copilot — full workflow, VK blocks, helpers, patterns
docs/
  rules.md                  21 mandatory rules (auto-layout, variables, DS components, etc.)
  zcatalyst-design-system.md  Component registry — keys, variants, boolean props, text nodes
  zcatalyst-styles.md       Color variables + text styles with full importable keys
  SETUP-GUIDE.md            One-time setup guide
.vscode/
  mcp.json                  Figma MCP server connection
.claude/
  commands/                 Claude slash commands for building and auditing screens
```

---

## Key Rules

- **All colors** → imported design variables, never raw hex
- **All text** → imported text styles via `setTextStyleIdAsync`
- **All UI elements** → ZCatalyst DS components (never hand-built buttons, tables, badges, etc.)
- **Boxy Table** → always wrap in a card (`cardsBgPrimary` bg, `cardsBorderDefault` border, `radius: 8`)
- **Pagination** → use the table's built-in pagination; do not add a separate Pagination component

Full rules: `docs/rules.md`

---

## Design System File

**File Key**: `dwQLnT4eJ3zCaOwhk7JXIn` — READ ONLY. Never modify.
