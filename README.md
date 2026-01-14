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
```

### Inputs
Form inputs with support for error states.

- Default input: `c-input`
- Error input: `c-input c-input--error`
- Error message text: `help help--error`

Example:
```html

<label for="email">Email</label>
<input id="email" class="c-input c-input--error" />
<p class="help help--error">This field is required.</p>
```
### Cards
Reusable containers for grouping related content.

- Base container: c-card

Example:
```html

<div class="c-card">
  <h3>Card Title</h3>
  <p>Card content goes here.</p>
</div>
```

### Badges
Small status or label indicators.

Base: c-badge

Variants:

c-badge--info

c-badge--success

c-badge--warning

c-badge--danger

### Alerts
Feedback messages for users.

Base: c-alert

Variants:

c-alert--info

c-alert--success

c-alert--warning

c-alert--danger

### Navbar
A reusable navigation component.

Uses the c-navbar structure defined in index.html

Designed to be reused across pages without modification

### Modal (CSS-only demo)
A modal example built without JavaScript.

Uses :target to open and close

Open the modal using a link with href="#demo-modal"

Close the modal by clicking the backdrop or a close link pointing to #contact

## Live Demo
https://jamathdoc.github.io/Mini-ui/