## 2024-05-18 - Mobile Nav Toggle Accessibility
**Learning:** Single-page luxury landing pages often use decorative `div` elements for mobile toggle menus, rendering them inaccessible to screen reader and keyboard-only users.
**Action:** Always replace `div` toggle controls with `<button>` elements, add localized `aria-label` matching `lang="ar"`, update `aria-expanded` dynamically in JS, and enforce `:focus-visible` styling.
