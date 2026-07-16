
# 🛒 Modern Next.js E-Commerce Application

A high-performance, responsive e-commerce platform built with Next.js 15, Tailwind CSS v4, TypeScript, and integrated with Stripe for seamless payment processing.

---

## ⚙️ Tech Stack

* **Framework:** **Next.js 15** (App Router, React Server Components)
* **Styling:** **Tailwind CSS v4** (CSS-first configuration, rapid utility-first styling)
* **Language:** **TypeScript** (Strict type safety, robust developer experience)
* **State Management:** **Zustand** (Ultra-lightweight, high-performance client-side store)
* **Payments:** **Stripe SDK** (Secure, production-ready checkout workflows)

---

## ⚡️ Key Features

* **Interactive Product Carousel:** An auto-cycling, responsive hero carousel featuring top-tier products.
* **Dynamic Cart System:** Real-time state management utilizing Zustand to keep the navigation bar cart count synced across client interactions.
* **Intuitive Product UI:** Detailed product pages with precise interactive quantity adjusters (+/- triggers).
* **Stripe Integration:** Production-grade checkout pipeline leveraging Stripe's secure hosted payment gateways.
* **Modern Aesthetics:** Clean, minimalist UI design modeled after popular design systems like `shadcn/ui`.

---

## 🚀 Quick Start

Follow these steps to get your local development environment up and running.

### Prerequisites

Ensure you have the following installed on your machine:

* [Node.js](https://nodejs.org/en/) *(v18.x or higher recommended)*
* [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
* [Git](https://git-scm.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/ronniee7/Ecommerce-App.git
cd Ecommerce-App

```

### 2. Install Dependencies

```bash
npm install

```

### 3. Environment Setup

Create a `.env.local` file in the root of your project directory and add your Stripe API keys:

```env
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_APP_URL=http://localhost:3000

```

### 4. Run the Development Server

```bash
npm run dev

```

Open [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000) in your browser to view the application in action.
