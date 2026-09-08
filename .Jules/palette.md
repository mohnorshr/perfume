## 2024-05-18 - Accessible Accordion Headers in RTL/Arabic Single-Page Interfaces
**Learning:** Non-interactive `div` elements used as accordion headers prevent keyboard users from focusing/toggling content and screen readers from announcing collapse/expand states.
**Action:** Always replace non-interactive `div` toggle headers with native `<button type="button">` elements, adding `aria-expanded` and `aria-controls`, and ensure reset styling preserves RTL layout and focus-visible accessibility.
