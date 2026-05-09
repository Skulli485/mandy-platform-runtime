# Mandy Koch — Personal Platform-Runtime

[Live on Vercel](https://mandy-platform-runtime.vercel.app) · [Live on GitHub Pages](https://github.com/Skulli485/mandy-platform-runtime)

## Was das ist
Ein Multi-Page-Personal-Showcase, gebaut mit Modern CSS Features (Mai 2026).
Kein Framework, kein Build-Step, vier Pages, ein Token-System.

## Pages
- **Home** — Hero + Feature-Cards
- **Pricing** — Subgrid-aligned Plan-Cards
- **Profile** — Stat-Cards mit Anchor-Positioned-Tooltips
- **Login** — Form mit :has()-basierter Email-Validation
- **about** — eine persönliche About-Seite mit mordernem CSS, die mein Profil sowie meinen beruflichen Hintergrund und meine Socials zeigt und dabei Features wie Tokens, @container und subgrid verwendet.

## Modern CSS Features
- 3-Layer Token-System (Primitives → Semantic → Component)
- :has() für State-Detection ohne JavaScript
- @container für Component-Level-Responsiveness
- color-mix(in oklch) für brand-derived Tokens
- View Transitions für smooth Page-Switches
- Subgrid für Card-Row-Alignment
- Anchor Positioning für JS-freie Tooltips
- @supports für progressive enhancement
- @property für animatable typed properties

## Brand-Swap-Test
![before](./screenshots/before.png)
![after](./screenshots/after.png)

Eine Zeile in `tokens.css` ändern → ganzes System folgt automatisch.

## Stack
Vanilla HTML + CSS. Modern Browser-Features (Chrome 120+, Edge 120+, Safari 26+).
Kein Build, kein npm, kein Framework.

## Author
Mandy Koch — Morphos Advanced CSS Cohort, Mai 2026