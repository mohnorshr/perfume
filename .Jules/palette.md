# Palette UX & Accessibility Journal

## 2024-05-18 - Non-semantic interactive components in landing pages
**Learning:** Single-file landing pages often use `div` elements with `onclick` handlers for accordions and mobile navigation toggles, rendering them inaccessible to screen reader and keyboard users without native semantics or `aria-expanded` state tracking.
**Action:** Always replace non-semantic clickable `div`s with native `<button>` elements, include explicit `:focus-visible` styles, and synchronize `aria-expanded` attributes dynamically in JS click listeners.
