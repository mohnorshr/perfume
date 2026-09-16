## 2024-05-20 - Accessible Mobile Navigation Toggle
**Learning:** Single-page application navigation toggles built using non-semantic `<div>` elements hinder keyboard navigation and lack screen reader state indication. Converting them to `<button>` with dynamic `aria-expanded` and `aria-controls` provides essential accessibility without disrupting custom CSS layout.
**Action:** Always check interactive icon/hamburger toggles in header navigation to ensure they use `<button type="button">`, explicit `aria-label`s, and maintain focus-visible outlines.
