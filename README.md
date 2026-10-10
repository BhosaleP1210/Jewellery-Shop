#  Jewellery Shop - Luxury E-Commerce Web Application

[![React](https://img.shields.io/badge/React-19.2.5-blue.svg?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8.0-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC.svg?logo=tailwind-css)](https://tailwindcss.com/)
[![React Router](https://img.shields.io/badge/React_Router-v7-CA4245.svg?logo=react-router)](https://reactrouter.com/)

A modern, responsive, and elegant e-commerce web application crafted for luxury jewellery shopping. Built using **React 19**, **Vite**, and **Tailwind CSS**.

---

##  Key Features

-  **Curated Collections & Categories**: Browse through dedicated collections like Rings, Necklaces, Earrings, Bracelets, and Watches.
-  **Interactive Product Catalog**: Real-time filtering, product browsing, and detailed item cards with high-definition visuals and pricing.
-  **Rich Product Detail Pages**: In-depth product view with high-resolution imagery, specifications, descriptions, and dynamic "Add to Cart" interactions.
-  **Full Cart Functionality**: Global state management powered by React Context API (`CartContext`) for adding, updating item quantities, calculating subtotals, and removing items.
-  **Contact & Inquiry Page**: Interactive contact form and store information for customer assistance.
-  **Fully Responsive & Modern UI**: Tailored with luxurious color palettes, smooth hover micro-animations, and clean typography optimized across mobile, tablet, and desktop viewports.

---

##  Tech Stack

- **Frontend Framework**: [React 19](https://react.dev/)
- **Build Tool / Bundler**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & PostCSS
- **Routing**: [React Router v7](https://reactrouter.com/)
- **State Management**: React Context API (`CartProvider`)

---

##  Project Structure

```text
Jewellery-Shop/
├── my-store/
│   ├── public/              # Static assets
│   ├── src/
│   │   ├── assets/          # Images & media assets
│   │   ├── components/      # Reusable UI components (Navbar, Footer, Hero, ProductCard, CategoryCard)
│   │   ├── context/         # React Context providers (CartContext)
│   │   ├── data/            # Static product & category datasets
│   │   ├── pages/           # Application views/routes
│   │   │   ├── Home.jsx
│   │   │   ├── ProductPage.jsx
│   │   │   ├── ProductDetails.jsx
│   │   │   ├── CategoryDetail.jsx
│   │   │   ├── CartPage.jsx
│   │   │   └── ContactPage.jsx
│   │   ├── App.jsx          # Route declarations & provider wrapper
│   │   ├── main.jsx         # Application entry point
│   │   └── index.css        # Global Tailwind styling rules
│   ├── package.json
│   ├── tailwind.config.js
│   └── vite.config.js
└── README.md
```

---

##  Getting Started

Follow these steps to run the application locally on your machine.

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (version 18+ recommended) installed.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BhosaleP1210/Jewellery-Shop.git
   cd Jewellery-Shop/my-store
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm run dev
   ```
   Open `http://localhost:5173` in your browser to view the application.

4. **Build for production:**
   ```bash
   npm run build
   ```

5. **Preview production build:**
   ```bash
   npm run preview
   ```

---

##  Available Scripts

In the `my-store` directory, you can run:

- `npm run dev` - Runs the app in development mode with Hot Module Replacement (HMR).
- `npm run build` - Compiles and bundles the application for production to `dist/`.
- `npm run preview` - Locally previews the production build.
- `npm run lint` - Runs ESLint to check for code quality and syntax issues.

---

##  Contributing

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/BhosaleP1210/Jewellery-Shop/issues).

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
