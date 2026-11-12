# Palette's Journal - Critical Learnings

## 2025-05-18 - Accordion Micro-interactions and RTL Keyboard Navigation
**Learning:** In custom single-page Arabic/RTL landing pages, interactive disclosure widgets (accordions) built with raw `div` tags lack keyboard accessibility, focus rings, and screen reader announcements (`aria-expanded`, `aria-controls`, `role="region"`). Converting headers to `<button type="button">` with `:focus-visible` using the theme's accent token (`var(--secondary)`) ensures accessible keyboard navigation without altering the existing luxurious dark aesthetic.
**Action:** When inspecting RTL landing pages with custom accordion or tab components, prioritize converting unsemantic clickable divs to button controls and verifying keyboard accessibility with Playwright.
