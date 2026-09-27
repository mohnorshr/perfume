## 2024-05-20 - Non-semantic interactive controls in custom luxury UI
**Learning:** Custom interactive elements (e.g. mobile navigation toggles and accordion headers) implemented as `<div>` tags prevent keyboard focus and screen reader interaction.
**Action:** Always use native `<button type="button">` elements with explicit `aria-expanded` and `aria-label` attributes, along with `:focus-visible` styles matching the design tokens.
