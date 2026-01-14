# Mini Component Library (Pure CSS)

A small set of reusable UI components built with pure HTML and CSS.  
This project focuses on consistent UI patterns, predictable class naming, and a simple design system using CSS variables.

---

## Design system

- Colors and spacing are controlled using CSS variables defined in `:root`.
- Naming convention:
  - `c-` for components (e.g., `c-btn`, `c-card`)
  - `--` for variants (e.g., `c-btn--primary`)
  - state classes for behavior (e.g., `is-disabled`, `--error`)

---

## Components

### Buttons
Reusable button styles for actions.

- Primary: `c-btn c-btn--primary`
- Secondary: `c-btn c-btn--secondary`
- Disabled: add the `disabled` attribute

Example:
```html
<button class="c-btn c-btn--primary">Primary</button>

https://jamathdoc.github.io/Mini-ui/