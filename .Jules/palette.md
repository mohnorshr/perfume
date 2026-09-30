## 2024-05-20 - Custom Accordion Keyboard & Screen Reader Accessibility
**Learning:** Custom `<div>` interactive elements (such as accordions) lack keyboard focusability and ARIA accessibility states by default, making them completely inaccessible to keyboard and screen reader users.
**Action:** Always add `role="button"`, `tabindex="0"`, dynamic `aria-expanded` attributes, `:focus-visible` styling, and Space/Enter keydown handling with `preventDefault()` on non-native interactive container elements.
