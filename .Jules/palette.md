## 2024-09-03 - Accordion and Nav Toggle Accessibility in Single-Page Apps
**Learning:** Custom interactive components like fragrance note accordions and hamburger menu toggles implemented with `div` tags lack keyboard focusability and ARIA state exposure for assistive technologies.
**Action:** Always replace non-semantic `div` click targets with native `<button type="button">` elements, adding `aria-expanded` and `aria-controls`, along with custom `:focus-visible` ring styling to preserve design aesthetic while ensuring full keyboard and screen reader accessibility.
