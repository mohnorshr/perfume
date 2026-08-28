# Palette's Journal - Critical UX Learnings

## 2024-05-20 - Interactive Accordions and Custom Mobile Toggles
**Learning:** In single-page websites using custom DIVs or semantic wrappers for accordion headers and mobile menu toggles, keyboard accessibility and screen reader support are often missing. Converting clickable headers and toggles to `<button>` elements with `aria-expanded`, `aria-controls`, and proper `:focus-visible` styling provides seamless screen reader announcements and keyboard navigation.
**Action:** Always replace click-handler `<div>` elements for disclosure widgets with `<button>` elements, manage `aria-expanded` dynamically via JS, and add custom focus indicators matching the design theme.
