# Nice Gadgets — Phone Catalog

A modern, responsive online store for phones, tablets and accessories. Users can browse products by category, explore detailed product pages, and manage a shopping cart and a favorites list.

## Live Preview

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Open_Site-5d5fff?style=for-the-badge)](https://droopy-bit.github.io/phone-catalog/)

Deployed on GitHub Pages: [https://droopy-bit.github.io/phone-catalog/](https://droopy-bit.github.io/phone-catalog/)

## Design Reference

The UI is based on a Figma mockup: [View design](https://www.figma.com/design/WMdJ24eHk4EkSr25mrt7Y2/Phone-catalog--V2--Original-Dark?node-id=0-1&p=f&t=cJcShOMtDvI8N62l-0)

## Technologies Used

**Core**
- React 18
- TypeScript
- SCSS Modules

**Routing & State**
- React Router (HashRouter) — client-side routing
- React Context API — cart and favorites state

**Build & Deployment**
- Vite — build tool and dev server
- gh-pages — deployment to GitHub Pages

## Getting Started

Follow these steps to set up the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/droopy-bit/phone-catalog.git
cd phone-catalog
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the project locally

```bash
npm start
```

The app will be available at the address shown in your terminal.

## Features

- **Responsive design** — adapts to mobile, tablet and desktop screens
- **Navigation** — header with category links and a mobile burger menu
- **Home page** — banner slider, "Shop by category" section and product sliders
- **Product catalog** — separate pages for phones, tablets and accessories
- **Product details** — photo gallery and full specifications
- **Shopping cart** — add items, change quantities, live item counter
- **Favorites** — save products and view them on a dedicated page
- **Breadcrumbs** — easy navigation between pages
