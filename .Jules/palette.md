## 2025-02-18 - Mobile Navigation Toggle Accessibility
**Learning:** Single-page landing pages built with vanilla JS often implement custom `<div>` burger menus without keyboard focus states or ARIA expand/collapse metadata, making mobile navigation unusable for screen readers and keyboard-only users.
**Action:** Always replace unsemantic mobile menu containers with standard `<button>` elements containing `aria-label`, `aria-expanded`, `aria-controls`, and visible focus indicators (`:focus-visible`).
