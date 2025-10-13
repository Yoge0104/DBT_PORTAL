# DBT Portal Repo Overview

## Structure
- **DBT_PORTAL/enhanced-dbt-pcr-poa**: Primary frontend project containing `index.html`, `style.css`, and `app.js` files.

## Stack & Tooling
- **Frontend**: Vanilla HTML, CSS, and JavaScript.
- **Charts**: Uses Chart.js from CDN within `index.html`.

## Conventions
1. **Styling**: Centralized styles in `style.css`; inline `<style>` blocks exist within `index.html` for page-specific overrides.
2. **Scripting**: All client-side behavior handled in `app.js`.
3. **Layout**: Sections toggled via JavaScript and classes (`active`).

## Tips for Future Contributors
1. Keep UI components responsive; ensure mobile menu toggles function correctly.
2. When adding new sections, register them in navigation and ensure `app.js` handles visibility toggling.
3. Reuse utility classes or extend `style.css` thoughtfully to maintain consistency.