# ☕ Coders Coffee

A modern, animated coffee shop landing page built with React, Framer Motion, and Tailwind CSS. Featuring a sleek dark-themed UI with smooth scroll-triggered animations, responsive layout, and a clean component-based architecture.

---

## 📑 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Deployment](#-deployment)
- [How to Use](#-how-to-use)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Build for Production](#build-for-production)
  - [Preview Production Build](#preview-production-build)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✅ Features

- ✅ Fully responsive design optimized for mobile, tablet, and desktop
- ✅ Smooth scroll-triggered animations powered by Framer Motion
- ✅ Dark-themed hero section with dynamic background imagery
- ✅ Interactive hamburger menu navigation
- ✅ Services section showcasing coffee varieties with staggered card animations
- ✅ "Where to Buy" section with an integrated order form and world map
- ✅ App download banner with App Store and Play Store links
- ✅ Footer with company details, quick links, social media icons, and payment methods
- ✅ Social media integration (Facebook, Instagram, Twitter, Telegram, Google)
- ✅ Clean, modular component-based architecture
- ✅ Custom Tailwind CSS color theme with primary orange palette
- ✅ Fast development and build with Vite

---

## 🛠 Tech Stack

| Technology | Purpose |
| --- | --- |
| [React 18](https://react.dev/) | UI library for building component-based interfaces |
| [Vite](https://vite.dev/) | Fast build tool and development server |
| [Tailwind CSS 3](https://tailwindcss.com/) | Utility-first CSS framework for rapid styling |
| [Framer Motion](https://www.framer.com/motion/) | Animation library for React |
| [React Icons](https://react-icons.github.io/react-icons/) | Popular icon packs as React components |
| [PostCSS](https://postcss.org/) | CSS transformations with Autoprefixer |
| [ESLint](https://eslint.org/) | JavaScript/JSX linting and code quality |

---

## 🚀 Deployment

The app is live and deployed on **Vercel**.

🔗 **Live URL:** [https://coders-coffee-react-fm-tcss-js.vercel.app/](https://coders-coffee-react-fm-tcss-js.vercel.app/)

---

## 📖 How to Use

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/tauseefiqbal/coders_coffee-react-fm-tcss-js.git
   cd coders_coffee-react-fm-tcss-js
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open in browser**

   Navigate to `http://localhost:5173` to view the app.

### Build for Production

```bash
npm run build
```

The production-ready files will be generated in the `dist/` folder.

### Preview Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
coders_coffee/
├── public/                  # Static public assets
├── src/
│   ├── assets/              # Images and media files
│   │   ├── coffee/          # Coffee product images
│   │   └── website/         # App store badges, banners, etc.
│   ├── components/
│   │   ├── AppBanner/       # App download banner section
│   │   ├── Footer/          # Footer with links and social icons
│   │   ├── Hero/            # Hero section with animated content
│   │   ├── Navbar/          # Navigation bar with hamburger menu
│   │   ├── Services/        # Coffee services/products cards
│   │   └── WhereToBuy/      # Order form with world map
│   ├── App.jsx              # Root application component
│   ├── index.css            # Global styles
│   └── main.jsx             # Application entry point
├── index.html               # HTML template
├── tailwind.config.js       # Tailwind CSS configuration
├── postcss.config.js        # PostCSS configuration
├── vite.config.js           # Vite configuration
├── eslint.config.js         # ESLint configuration
└── package.json             # Project dependencies and scripts
```

---

## 📸 Screenshots

> _Add screenshots of your application here._

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
