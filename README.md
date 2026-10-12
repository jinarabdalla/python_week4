# SpendWise Dashboard Shell

SpendWise is a responsive personal-finance dashboard shell built with semantic HTML and modern CSS. This project focuses on layout and visual presentation using CSS Grid, Flexbox, CSS custom properties, responsive design, and subtle card interactions. All financial figures are static sample content; no JavaScript functionality is required.

## Project files

- **`index.html`** — Provides the dashboard structure: sidebar navigation, header, monthly summary cards, six spending categories, recent transactions, budget overview, and footer. It also loads Google Fonts and the stylesheet.
- **`style.css`** — Defines the theme variables and all visual styling. CSS Grid controls the main dashboard, summary/category sections, and lower panels. Flexbox arranges navigation links, header controls, card content, and transaction rows.
- **`README.md`** — Describes the project and how its files are organized.

## Design and CSS features

- **Theme variables:** The `:root` selector defines brand, accent, background/surface, primary text, secondary text, border, radius, and shadow variables.
- **Typography:** Uses Google Fonts **Manrope** for headings and **DM Sans** for body text.
- **Grid and Flexbox:** Grid builds the overall two-column desktop shell and card layouts. Flexbox aligns navigation, header items, card details, and transaction rows.
- **Responsive layout:** Below 768px, the dashboard becomes a single-column layout. A tablet-sized breakpoint adjusts cards to two columns where space permits.
- **Card micro-interactions:** Spending cards lift slightly and gain a stronger shadow on hover and keyboard focus. The transition lasts 220ms and uses transform and box-shadow.
- **Dark theme:** A `prefers-color-scheme: dark` media query overrides the theme variables in `:root`.
- **Accessibility:** Semantic sections, navigation labels, visible focus styles, and reduced-motion preferences are included.

## How to view

1. Open `index.html` in a browser, or use the Live Server extension in Visual Studio Code.
2. Resize the browser window or open DevTools → Device Toolbar to test the responsive layout.
3. Use a system dark appearance setting to preview the optional dark theme.

## Note

This is a visual dashboard foundation with realistic sample values only. Navigation links and the notification control are presentation elements and do not perform app actions.
