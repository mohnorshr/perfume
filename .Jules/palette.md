# Palette's Journal - UX & Accessibility Learnings

## 2024-05-20 - RTL Glassmorphism Button Resets for Accordions and Toggles
**Learning:** In dark luxury RTL landing pages, replacing `div` click targets (such as accordions and mobile menu toggles) with semantic `<button type="button">` elements requires explicit button reset rules (`font: inherit; color: inherit; background: transparent; border: none; text-align: inherit; width: 100%`) and `:focus-visible` outline offsets (`outline-offset: -2px`) to ensure RTL text alignment and glassmorphism borders stay visually pristine while providing full keyboard focus and screen reader `aria-expanded`/`aria-controls` states.
**Action:** Always combine semantic `<button>` elements with `:focus-visible` rules and explicit JS `setAttribute('aria-expanded', state)` sync when adding accessibility to custom accordions or menu toggles.
