# Palette's Journal - Critical UX Learnings

## 2024-09-24 - Semantic Buttons for RTL Mobile Navigation Toggles
**Learning:** In RTL luxury landing pages built as a single file, mobile navigation toggles are frequently implemented as non-interactive `div` elements lacking focus states or ARIA state metadata (`aria-expanded`, `aria-label`, `aria-controls`), preventing screen reader users and keyboard navigators from toggling navigation menus.
**Action:** Always replace non-interactive toggle `div`s with native `<button type="button">`, bind `aria-expanded` updates directly to the toggle event handler, and provide `:focus-visible` outline styles with proper contrast against dark theme CSS variables.
