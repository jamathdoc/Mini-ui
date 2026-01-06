# Mini Component Library (Pure CSS)

A small set of reusable UI components built with pure HTML + CSS.

## Design system
- Colors and spacing are controlled using CSS variables in `:root`.
- Naming convention:
  - `c-` for components (e.g., `c-btn`)
  - `--` for variants (e.g., `c-btn--primary`)
  - `is-` for states (e.g., `is-disabled`)

## Components

### Buttons
- Primary: `c-btn c-btn--primary`
- Secondary: `c-btn c-btn--secondary`
- Disabled: add `disabled` attribute or `is-disabled`

### Inputs
- Default: `c-input`
- Error: `c-input c-input--error`
- Error message: `c-help c-help--error`

### Cards
- Container: `c-card`

### Badges
- Base: `c-badge`
- Variants: `c-badge--info`, `--success`, `--warning`, `--danger`

### Alerts
- Base: `c-alert`
- Variants: `c-alert--info`, `--success`, `--warning`, `--danger`

### Navbar
- Use `c-navbar` structure from `index.html`

### Modal (CSS-only demo)
- Uses `:target` to open/close
- Open link: `href="#demo-modal"`
- Close by clicking backdrop or close button link to `#modal`
