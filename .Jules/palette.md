# Palette's Journal - Critical UX & Accessibility Learnings

## 2025-05-18 - Accessible Interactive Accordions in Dark RTL Luxury Interfaces
**Learning:** In luxury dark-themed single-page web applications (like NOIR ESSENCE), accordion headers are frequently implemented with purely mouse-driven `<div>` elements and click handlers. This completely excludes keyboard users (Tab + Space/Enter navigation) and screen readers (no `aria-expanded` state or semantic role). Providing `:focus-visible` with the secondary gold token (`--secondary`) and proper ARIA relationships (`role="button"`, `aria-expanded`, `aria-controls`) ensures accessibility without conflicting with existing cursor interactions or luxury aesthetics.
**Action:** Always verify custom disclosure/accordion components for keyboard events (`keydown` for Enter and Space), `tabindex="0"`, dynamic `aria-expanded` synchronization, and subtle `:focus-visible` outlines matching the brand palette.
