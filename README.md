# ☕ Coders Coffee

A modern, animated coffee shop landing page built with **React**, **Vite**, **Tailwind CSS**, and **Framer Motion**.

![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.4-06B6D4?logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-FF0050?logo=framer&logoColor=white)

---

## Features

- **Animated Hero Section** — Eye-catching landing area showcasing a featured product with spring animations and decorative elements.
- **Services Showcase** — Responsive grid of coffee types (Black, Hot, Cold) with staggered card entrance animations.
- **Where to Buy** — Global order form with name, email, country, and zipcode inputs alongside a world map graphic.
- **App Banner** — Promotional section with App Store and Google Play download links over a full-width coffee background.
- **Footer** — Multi-column layout with company info, quick links, social media icons, and payment method badges.
- **Responsive Navbar** — Logo with hamburger menu and animated mobile sidebar.
- **Fully Responsive** — Optimized for mobile, tablet, and desktop screens.
- **Smooth Animations** — Powered by Framer Motion with spring physics and staggered transitions throughout.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| [React](https://react.dev/) | UI component library |
| [Vite](https://vitejs.dev/) | Build tool & dev server |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [Framer Motion](https://www.framer.com/motion/) | Animations & transitions |
| [React Icons](https://react-icons.github.io/react-icons/) | Icon library |

---

## Project Structure

```
coders_coffee/
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── eslint.config.js
├── public/
└── src/
    ├── App.jsx              # Root component
    ├── main.jsx             # Entry point
    ├── index.css            # Global styles & Tailwind directives
    ├── assets/
    │   ├── coffee/          # Coffee product images
    │   └── website/         # Banner, store badges, payment icons
    └── components/
        ├── Navbar/Navbar.jsx
        ├── Hero/Hero.jsx
        ├── Services/Services.jsx
        ├── WhereToBuy/WhereToBuy.jsx
        ├── AppBanner/AppBanner.jsx
        └── Footer/Footer.jsx
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/tauseefiqbal/coders_coffee-react-fm-tcss-js.git
cd coders_coffee-react-fm-tcss-js

# Install dependencies
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Production Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

---

## Customization

- **Images** — Replace files in `src/assets/coffee/` and `src/assets/website/` with your own.
- **Content** — Edit individual component files in `src/components/` to update text, links, or layout.
- **Styling** — Modify `tailwind.config.js` to adjust the theme (colors, fonts, spacing).

---

## License

MIT
