# Online-Food-Delivery-React-frontend-only-

# 🍔 BiteBite Delivery App

![BiteBite Banner](https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1200&h=400&q=80)

> A premium, highly interactive frontend web application for a modern food delivery service. Built with React, Tailwind CSS, and powered by Framer Motion for a fluid, cinematic user experience.

## ✨ Features

- **"Beast Mode" UI/UX:** Premium glassmorphism, floating elements, and satisfying magnetic hover effects.
- **Cinematic Animations:** Staggered list reveals, scroll-based triggers, and word-by-word text animations using Framer Motion.
- **Multi-Page Experience (Simulated Routing):**
  - 🔐 **Auth Screens:** Beautifully designed Login & Signup flows.
  - 🏠 **Landing Page:** Interactive restaurant grid, category pills, and a sleek offers slider.
  - 🏷️ **Offers Page:** Dedicated view for the latest food deals.
  - ℹ️ **About Us:** High-energy page featuring animated statistics and core values.
  - 📞 **Contact Page:** 3D-perspective info cards and an interactive form with satisfying success states.
- **Fully Responsive:** Looks perfect on mobile, tablet, and desktop devices.

## 🛠️ Tech Stack

- **Framework:** [React.js](https://reactjs.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Icons:** [Lucide React](https://lucide.dev/)

## 🚀 Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/bitebite-delivery.git](https://github.com/yourusername/bitebite-delivery.git)
   cd bitebite-delivery
Install the dependencies: npm install

Install the required UI libraries (if not already in package.json): npm install framer-motion lucide-react tailwindcss

Start the development server: npm start

📁 Project Structure:
src/
├── components/
│   ├── AboutPage.jsx     # Animated hero, stats, and values
│   ├── ContactPage.jsx   # 3D interactive cards & animated form
│   ├── LandingPage.jsx   # Main dashboard, restaurants, and nav
│   ├── LoginPage.jsx     # User authentication UI
│   ├── OffersPage.jsx    # Promo codes and discounts
│   └── SignupPage.jsx    # User registration UI
├── App.js                # Main state-based router connecting pages
├── index.css             # Tailwind imports & custom font configs
└── index.js              # React entry point
