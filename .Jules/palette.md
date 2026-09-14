## 2026-09-14 - Semantic Mobile Navigation Toggle & ARIA Attributes
**Learning:** In single-file HTML components, interactive UI controls like mobile menu toggles are often implemented using non-semantic `<div>` elements, missing keyboard focus states and screen reader support.
**Action:** Always replace interactive `<div>` elements with semantic `<button type="button">` elements, adding `:focus-visible` styling and dynamic `aria-expanded` management.
