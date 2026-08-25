## 2024-05-20 - Accessible Mobile Navigation Toggle
**Learning:** Pure `<div>` mobile navigation triggers prevent screen reader users and keyboard-only users from discovering or activating navigation menus on mobile viewports.
**Action:** Replace unsemantic clickable `div` triggers with `<button type="button">`, explicit ARIA labels (`aria-label`, `aria-controls`), dynamic state indicators (`aria-expanded`), and clean `:focus-visible` ring styling.
