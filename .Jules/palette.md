## 2026-10-15 - Mobile Navigation Toggle Accessibility in Single-Page RTL Apps
**Learning:** Hamburger navigation toggles rendered as non-semantic `<div>` elements hide state changes from screen readers and fail keyboard interaction standards (`Escape` key closing, focus states).
**Action:** Always replace non-semantic toggle containers with `<button type="button">`, manage `aria-expanded` and `aria-controls` states, and add `Escape` key listeners that auto-close the menu drawer and restore focus.
