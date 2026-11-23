# SpendWise Dashboard Shell

A responsive personal-finance dashboard shell built with semantic HTML and modern CSS. This is a visual-layout assignment: the dashboard uses realistic static sample content and does not include JavaScript functionality.

## Files

- **`index.html`** — Page structure, sidebar navigation, header, financial summary cards, six spending-category cards, recent activity, and a savings tip.
- **`style.css`** — Theme variables, typography, Grid and Flexbox layouts, responsive rules, card hover/focus interactions, and the optional dark theme.

## Layout and styling

- CSS Grid creates the overall sidebar/content layout, summary cards, category-card grid, and lower dashboard panels.
- Flexbox arranges navigation links, header controls, card content, activity rows, and footer content.
- CSS custom properties in `:root` define the brand, accent, surface, background, text, border, and shadow tokens.
- At widths below **768px**, the page becomes a single-column layout and the navigation becomes horizontally scrollable.
- Category cards animate on hover and keyboard focus using transform and box-shadow transitions of 220ms.
- `prefers-color-scheme: dark` overrides the root theme variables for a dark color scheme.

## Preview locally

1. Clone or download this repository.
2. Open `index.html` in a browser.
3. Use the browser DevTools Device Toolbar to check a mobile viewport below 768px.
4. If your device is set to dark mode, the dashboard will automatically use the dark theme.

## Sample data

All amounts and transactions are static demonstration content in Kenyan shillings (KES). They are not connected to a bank account or live financial data.
