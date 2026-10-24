## 2025-05-20 - Custom Accordion and Mobile Toggle Accessibility
**Learning:** In vanilla HTML/JS projects using custom div elements for interactive controls (like accordions and hamburger menus), screen readers and keyboard users cannot interact with or perceive state changes without semantic <button> tags, aria-expanded, and aria-controls attributes.
**Action:** Always replace interactive non-semantic divs with <button> elements and handle aria-expanded states in JS toggle handlers.
