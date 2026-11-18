# ZenPay

ZenPay is a responsive landing page for a next-generation digital payment platform. It presents the product, its features, billing, card offers, customer testimonials and a call to action, in a dark theme with a cyan accent.

**Live site:** https://idyllic-narwhal-6d9c26.netlify.app

## Tech stack

| Area | Technology |
|---|---|
| UI library | React |
| Build tool | Vite |
| Styling | Tailwind CSS v4 (`@tailwindcss/vite`) with custom CSS gradients |
| Font | Poppins (Google Fonts) |
| Linting | Oxlint |
| Version control | Git and GitHub |
| Hosting | Netlify (auto-deploys on every push to `main`) |

## Sections

- Navbar
- Hero
- Stats
- Business
- Billing
- Card deal
- Testimonials
- Clients
- Call to action
- Footer

## Project structure

```
ZenPay/
├── public/
├── src/
│   ├── assets/        images, icons and logo
│   ├── components/    page sections and reusable UI parts
│   ├── constants/     text content and data used by components
│   ├── App.jsx
│   ├── index.css      Tailwind import, theme and custom gradients
│   ├── main.jsx
│   └── style.js       shared style classes
├── index.html
├── vite.config.js
└── package.json
```

## Getting started

Requirements: Node.js 20 or newer and npm.

```bash
git clone https://github.com/yash-01-sketch/ZenPay.git
cd ZenPay
npm install
npm run dev
```

The app runs at http://localhost:5173.

## Scripts

| Command | What it does |
|---|---|
| `npm run dev` | Starts the development server with hot reload |
| `npm run build` | Creates the production build in `dist/` |
| `npm run preview` | Serves the production build locally |

## Deployment

The site is hosted on Netlify and connected to this GitHub repository.

- Build command: `npm run build`
- Publish directory: `dist`

Every `git push` to `main` triggers a new deploy.

## License

Copyright © 2026 ZenPay. All rights reserved.
