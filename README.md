<div align="center">
  <br />
      <img src="/frontend/public/readme-hero.png" alt="BagIt Banner">    
  <br />

  <div>
    <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" /> 
    <img src="https://img.shields.io/badge/-TailwindCSS-06B6D4?style=for-the-badge&logo=Tailwind%20CSS&logoColor=white" />
    <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white" />
    <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
  </div>

  <h3 align="center">BagIt – PERN Stack Product Store</h3>

   <div align="center">
     A modern web application designed to simplify shopping, cart management, and bidding with a clean and scalable architecture.
    </div>
</div>

---

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔐 [Environment Variables](#environment-variables)
6. 🚀 [More](#more)

---

## ✨ <a href="introduction" target="_blank">Introduction</a>

**BagIt** is a modern, full-stack shopping and bag management platform that allows users to browse products, add items to their bag by bidding and manage quantities.

The application focuses on **performance, scalability, and user experience**, offering real-time updates, secure authentication, cloud-based media handling, and analytics-driven insights to improve engagement and conversions.

Whether you are building an e-commerce prototype or a production-ready shopping platform, **BagIt** provides a strong and extensible foundation.

---

## ⚙️ <a href="tech-stack" target="_blank">Tech Stack</a>

-   **React/Vite** – Frontend framework with fast and responsive UI development
-   **TypeScript** – Strong typing for better maintainability and developer experience
-   **Tailwind CSS** – Utility-first styling for fast and responsive UI development
-   **PostgreSQL (Neon)** – SQL database for flexible and scalable data storage
-   **Daisy UI** – Tailwind CSS component library for fast and responsive UI development

---

## 🔋 <a href="features" target="_blank">Features</a>

👉 **Product Browsing**  
Browse products with rich images and descriptions.

👉 **Smart Bag (Cart) System**  
Add, remove, and update product quantities in real time.

👉 **Authentication & Authorization**  
User sign-up, login, and protected routes.

👉 **Modern UI & Performance**  
Responsive design with optimized caching and fast load times.

And much more, including scalable architecture and reusable components.

---

## 🤸 <a href="quick-start" target="_blank">Quick Start</a>

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

### Backend (`/backend`)

#### Installation

```bash
bun install
```

#### Running the Project

```bash
bun dev
```

Open http://localhost:3000 in your browser to view the application.

### Frontend (`/frontend`)

#### Installation

```bash
bun install
```

#### Running the Project

```bash
bun dev
```

Open http://localhost:5173 in your browser to view the application.

---

## 🔐 <a href="environment-variables" target="_blank">Environment Variables</a>

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

## 🚀 <a href="more" target="_blank">More</a>

### Future Enhancements

-   Wishlist functionality
-   Admin dashboard for product management
-   Inventory tracking
-   Discounts & promo codes
-   Mobile-first optimizations

### ⭐ Support

If you find BagIt useful, consider starring the repository and contributing to its growth. Pull requests and feature suggestions are always welcome!
