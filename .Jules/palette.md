## 2024-10-06 - Accessible Accordion & Toggle Buttons in Vanilla JS

**Learning:** Interactive click handlers attached to non-semantic `div` elements (e.g. accordion headers or mobile drawer toggles) make UI elements completely inaccessible to keyboard and screen-reader users. Converting these to `<button>` elements with reset CSS (`width: 100%`, `border: none`, `font: inherit`, `background: transparent`) preserves the original design while providing focusability and state announcements.

**Action:** When building or auditing custom disclosure/accordion components in vanilla HTML/CSS/JS, always use semantic `<button>` triggers with dynamic `aria-expanded` and `aria-controls` attributes, and add CSS `focus-visible` ring indicators.
