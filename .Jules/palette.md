## 2024-10-07 - Semantic Buttons for RTL Accordions & Mobile Navs
**Learning:** Converting interactive div containers (`.note-header`, `.nav-toggle`) in single-file vanilla HTML layouts to semantic `<button type="button">` with CSS button resets (`text-align: right` for RTL, `background: none`, `border: none`) ensures native keyboard navigation (Tab / Enter) and ARIA support (`aria-expanded`, `aria-controls`) without disturbing flex layouts or CSS themes.
**Action:** Always inspect custom interactive divs in vanilla templates for keyboard focusability and ARIA attribute state management.
