# Shopora

Shopora is a portfolio-ready premium e-commerce experience for modern fashion and lifestyle goods. It is built as a client-side React storefront with mock product data, local persistence, responsive layouts, and an editorial visual system.

## Features

- Responsive home, shop, category, product, search, cart, wishlist, checkout, account, orders, and confirmation routes
- Product search, category and price filters, sorting, variants, gallery, related products, and product detail views
- Cart and wishlist persistence with `localStorage`
- Quantity controls, toast feedback, empty states, checkout validation, promo code demo (`SHOPORA10`), and mobile navigation
- Recently viewed products, persistent demo orders, order history, clear wishlist, payment method tabs, and checkout progress
- Dark mode persistence, route transitions, lazy-loaded catalog images, SEO metadata, and accessible labels
- Egyptian storefront localization with EGP pricing and Cairo-friendly shipping messaging
- Editorial product photography, responsive navigation, subtle hover motion, and dark footer contrast

## Tech stack

React 19, TypeScript, Vite, Tailwind CSS, React Router, Lucide React, and Unsplash image URLs for mock photography.

## Installation

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
```

## Project structure

```text
src/
  App.tsx       Store context, routes, pages, and reusable UI
  App.css       Responsive visual system and component styles
  index.css     Tailwind layers and global typography
  main.tsx      React entry point
```

## Screenshots

Add screenshots of the home, shop, product, cart, and checkout routes here when publishing the portfolio case study.

## Live demo

Add the deployed Vercel, Netlify, or GitHub Pages URL here after deployment.
