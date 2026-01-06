<div align="center">
  <br />
      <img src="/frontend/public/readme-hero.png" alt="BagIt Banner">    
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logo=Next.js&logoColor=white" /> 
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white" /> 
    <img src="https://img.shields.io/badge/-TailwindCSS-06B6D4?style=for-the-badge&logo=Tailwind%20CSS&logoColor=white" />
  </div>

  <h3 align="center">BagIt – PERN Stack Product Store</h3>

   <div align="center">
     A modern web application designed to simplify shopping, cart management, and order tracking with a clean and scalable architecture.
    </div>
</div>

---

## 📋 Table of Contents

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔐 [Environment Variables](#environment-variables)
6. 🚀 [More](#more)

---

## ✨ <a href="#introduction" target="_blank">Introduction</a>

**BagIt** is a modern, full-stack shopping and bag management platform that allows users to browse products, add items to their bag, manage quantities, and securely complete purchases.

The application focuses on **performance, scalability, and user experience**, offering real-time updates, secure authentication, cloud-based media handling, and analytics-driven insights to improve engagement and conversions.

Whether you are building an e-commerce prototype or a production-ready shopping platform, **BagIt** provides a strong and extensible foundation.

---

## ⚙️ <a href="#tech-stack" target="_blank">Tech Stack</a>

-   **Next.js** – Full-stack React framework with server-side rendering and API routes
-   **TypeScript** – Strong typing for better maintainability and developer experience
-   **Tailwind CSS** – Utility-first styling for fast and responsive UI development
-   **MongoDB** – NoSQL database for flexible and scalable data storage
-   **Mongoose** – Schema-based ODM for MongoDB
-   **Cloudinary** – Cloud-based image storage and optimization
-   **Stripe** – Secure payment processing
-   **PostHog** – Product analytics and user behavior tracking

---

## 🔋 <a href="#features" target="_blank">Features</a>

👉 **Product Browsing**  
Browse products with rich images, descriptions, and pricing.

👉 **Smart Bag (Cart) System**  
Add, remove, and update product quantities in real time.

👉 **Secure Checkout**  
Integrated payment gateway for fast and secure transactions.

👉 **Authentication & Authorization**  
User sign-up, login, and protected routes.

👉 **Order Management**  
View order history, order status, and purchase summaries.

👉 **Cloudinary Image Uploads**  
Optimized image storage and delivery for product media.

👉 **Analytics & Tracking**  
Track user interactions, conversions, and feature usage with PostHog.

👉 **Modern UI & Performance**  
Responsive design with optimized caching and fast load times.

And much more, including scalable architecture and reusable components.

---

## 🤸 <a href="#quick-start" target="_blank">Quick Start</a>

Follow these steps to run **BagIt** locally on your machine.

### Prerequisites

Make sure you have the following installed:

-   [Git](https://git-scm.com/)
-   [Node.js](https://nodejs.org/)
-   [npm](https://www.npmjs.com/)

---

### Cloning the Repository

```bash
git clone https://github.com/itzzSVR-tech/BagIt.git
cd BagIt
```

### Installation

```bash
npm install
```

### Running the Project

```bash
npm run dev
```

Open http://localhost:3000 in your browser to view the application.

---

## 🔐 <a href="#environment-variables" target="_blank">Environment Variables</a>

Create a .env file in the below mentioned directories and add the following:

### Backend (`/backend`)

```bash
PORT=3000
DATABASE_URL=<YOUR_DB_URL>
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<YOUR_CLERK_PUBLISHABLE_KEY>
CLERK_SECRET_KEY=<YOUR_CLERK_SECRET_KEY>

FRONTEND_URL=http://localhost:5173
```

### Frontend (`/frontend`)

```bash
VITE_CLERK_PUBLISHABLE_KEY=<YOUR_CLERK_PUBLISHABLE_KEY>

VITE_API_URL=http://localhost:3000/api
```

## 🚀 <a href="#more" target="_blank">More</a>

### Future Enhancements

-   Wishlist functionality
-   Admin dashboard for product management
-   Inventory tracking
-   Discounts & promo codes
-   Mobile-first optimizations

### ⭐ Support

If you find BagIt useful, consider starring the repository and contributing to its growth. Pull requests and feature suggestions are always welcome!
