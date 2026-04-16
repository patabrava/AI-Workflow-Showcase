# CLAUDE.md

## Project

Presentation deck showcasing AI-powered development workflows with Claude Code. Contains a vintage editorial HTML slide deck and a chart-enhanced variant with Chart.js/SVG visualizations.

## Stack

- Single-file HTML with inline CSS/JS
- Fonts: Fraunces (display) + Work Sans (body)
- Chart.js 4.x for data visualizations
- SVG for radial gauge animations
- Scroll-snap slide navigation
- No build tools, no frameworks

## Guidelines

### 1. Think Before Coding

- State assumptions explicitly. If uncertain, ask.
- If multiple interpretations exist, present them — don't pick silently.
- If a simpler approach exists, say so. Push back when warranted.
- If something is unclear, stop. Name what's confusing. Ask.

### 2. Simplicity First

- No features beyond what was asked.
- No abstractions for single-use code.
- No speculative "flexibility" or "configurability."
- No error handling for impossible scenarios.
- If 200 lines could be 50, rewrite it.

### 3. Surgical Changes

- Don't "improve" adjacent code, comments, or formatting.
- Don't refactor things that aren't broken.
- Match existing style, even if you'd do it differently.
- Remove imports/variables/functions that YOUR changes made unused.
- Don't remove pre-existing dead code unless asked.
- Every changed line should trace directly to the request.

### 4. Goal-Driven Execution

- Transform vague tasks into verifiable goals.
- For multi-step tasks, state a brief plan with verification checks.
- Loop until verified. Weak criteria require clarification.

## Conventions

- German language for all slide content
- Color palette: cream (#f5f3ee), dark (#1a1a1a), terracotta (#c1664a), warm (#e8d4c0)
- Use `var` for all top-level JS variables (no `let`/`const` at top level)
- CSS custom properties for all colors and spacing
- Responsive via `clamp()` — no fixed pixel values for typography/spacing
