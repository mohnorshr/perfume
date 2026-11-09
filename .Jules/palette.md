# Palette's Journal

## 2026-06-25 - Accessible Accordions in RTL Dark Luxury Interfaces
**Learning:** Accordion panels built with generic `div` containers and `onclick` listeners lack keyboard focusability and screen reader state perception. In dark luxury themes with minimal visual clutter, replacing `div`s with semantic `<button type="button">`, adding `aria-expanded` and `aria-controls`, and using `:focus-visible` with the theme's secondary gold accent (`--secondary`) provides high keyboard usability without compromising the sleek dark luxury aesthetic.
**Action:** When working on interactive accordion or disclosure widgets in this design system, always use semantic `<button>` triggers, keep `aria-expanded` synchronized in the toggle handler, and use `outline: 2px solid var(--secondary); outline-offset: -2px` for discreet yet accessible keyboard focus.
