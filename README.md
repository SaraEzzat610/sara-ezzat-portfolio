# Sara Ezzat — Multi-page React Portfolio

A responsive bilingual (English / Arabic) portfolio built with React and Vite.

## Pages
- Home: `/`
- About: `/about`
- Experience: `/experience`
- Skills: `/skills`
- Projects: `/projects`
- Contact: `/contact`

## Run locally
1. Install Node.js (LTS).
2. Extract this ZIP and open a terminal inside `sara-portfolio-react`.
3. Run:

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

Upload the contents of the generated `dist` folder to your hosting public root.
The included `.htaccess` enables direct visits and refreshes on the portfolio's internal routes for Apache/cPanel hosting. For Nginx or other hosting, configure the server to fall back to `/index.html` for application routes.

## Included
- English and Arabic language toggle with RTL support.
- Dark and light themes.
- Separate navigable pages.
- 15 portfolio project links.
- Lightweight cursor ring and pointer-following blue glow on desktop.
- Reduced-motion and touch-device fallbacks.
- Responsive layout and accessible button contrast.
