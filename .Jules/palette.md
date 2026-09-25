## 2024-09-25 - Navigation Toggle Button Accessibility
**Learning:** Custom hamburger menus in static HTML/CSS templates often use `div` elements, making them completely inaccessible to keyboard users and screen readers. Replacing them with `<button>` elements with `aria-label`, `aria-expanded`, `aria-controls`, `:focus-visible` styling, and `Escape` key listeners restores full accessibility without visual disruption.
**Action:** Always check interactive navigation toggles for semantic `<button>` markup and keyboard interaction support.
