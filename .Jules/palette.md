## 2024-05-20 - Accordion Accessibility in RTL Single-Page Apps
**Learning:** Accordion components built using custom `div` elements require explicit ARIA attributes (`role="button"`, `aria-expanded`, `aria-controls`) and keydown event listeners (`Enter`/`Space`) to support keyboard navigation and screen reader accessibility.
**Action:** Always complement click triggers on non-button interactive elements with appropriate ARIA attributes and keyboard event handlers.
