# Palette's Journal - Critical UX Learnings

## 2025-05-18 - Keyboard Accessibility and ARIA Semantics on Custom Accordions
**Learning:** In custom interactive widgets built using `div` elements (like perfume notes accordion in NOIR ESSENCE), click handlers alone leave the component completely invisible to keyboard-only and screen reader users. Simply adding `role="button"` and `tabindex="0"` requires supporting both Enter and Space keys via `keydown`, maintaining synced `aria-expanded` and `aria-controls` states, and adding a distinct `:focus-visible` styling that respects the luxury dark aesthetic using `--primary` gold color.
**Action:** When working on custom interactive container elements in vanilla HTML/JS websites, always pair `tabindex="0"` with Enter/Space keyboard handlers, `aria-expanded`/`aria-controls` synchronization, and themed `:focus-visible` styles.
