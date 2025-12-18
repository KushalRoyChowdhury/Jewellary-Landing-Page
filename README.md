# Luxury Jewelry Landing Page

A premium, high-fidelity UI design demonstration built for a luxury jewelry brand. This project showcases modern web development practices, focusing on rich aesthetics, responsive layouts, and fluid micro-interactions.

![React](https://img.shields.io/badge/React-19-61dafb.svg?style=flat&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38b2ac.svg?style=flat&logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-5.0-646cff.svg?style=flat&logo=vite)

## 🌟 Overview

This landing page serves as a UI/UX demonstration, highlighting how a luxury e-commerce experience can be constructed using the latest web technologies. The design emphasizes elegance, minimalism, and premium visual hierarchy to engage potential customers.

## ✨ Features

- **Modern & Premium Design**: Clean typography, curated color palettes, and a layout that breathes luxury.
- **Fully Responsive**: Optimized for all devices, from large desktop screens to mobile phones.
- **Interactive Animations**: Powered by **Framer Motion** for smooth scroll reveals, extensive hover effects, and staggered animations.
- **Component-Based Architecture**: Modular and reusable React components.
- **Section Breakdown**:
    - **Hero Section**: Immersive introduction with fade-in and scale effects.
    - **Categories**: Visual navigation for different jewelry types (Rings, Necklaces, etc.).
    - **New Arrivals**: Showcase of the latest products.
    - **About Section**: Brand storytelling area.
    - **Testimonials**: Customer social proof slider/grid.
    - **Footer**: Elegant closure with site links and contacts.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) (using `@tailwindcss/vite`)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Utilities**: `clsx`, `tailwind-merge`

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

- Node.js (Latest stable version recommended)
- npm or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/KushalRoyChowdhury/Jewellery-Landing-Page
   cd "Jewellary Landing Page/landing-page"
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the landing page.

## 📂 Project Structure

```
landing-page/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable UI components (Navbar, Hero, etc.)
│   ├── assets/          # Images and other source assets
│   ├── App.jsx          # Main application component layout
│   ├── main.jsx         # Entry point
│   └── index.css        # Tailwind directives and global styles
├── index.html           # HTML entry point
├── package.json         # Dependencies and scripts
└── vite.config.js       # Vite configuration
```

## 🎨 UI Design Highlights

- **Typography**: Uses modern sans-serif fonts to maintain a sleek look.
- **Color Palette**: Defined in Tailwind config (using CSS variables for flexible theming).
- **Motion**:
    - Fade-up animations on scroll.
    - Staggered children animations for lists and grids.
    - Interactive hover states on buttons and product cards.

## 🤝 Contributing

This is a demonstration project, but suggestions are welcome!
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

*This project was created for UI designing demonstration purposes by Kushal Roy Chowdhury.*
