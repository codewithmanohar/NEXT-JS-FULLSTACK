# 📦 EazyStocks – Full-Stack Inventory Management System

Build a **modern, full-stack Inventory Management System** using **Next.js**, **Stack Auth**, **Prisma**, and **PostgreSQL**.
EazyStocks provides secure authentication, real-time inventory tracking, analytics dashboards, and complete CRUD functionality in a production-ready architecture.

---

## 📋 Table of Contents

* Introduction
* Tech Stack
* Features
* Quick Start
* Environment Setup
* Screenshots
* Deployment
* Useful Links


---

## 🚀 Introduction

**EazyStocks** is a full-stack inventory management application designed to help businesses track products, monitor stock levels, and analyze inventory value in real time.

This project demonstrates **modern web development best practices**, including:

* Server Actions
* Secure authentication
* Database-driven architecture
* Clean UI with Tailwind CSS

It’s ideal for developers who want to learn **Next.js App Router**, **Stack Auth**, and **Prisma** while building a real-world application.

🎥 **Full tutorial available on YouTube**

---

## ⚙️ Tech Stack

* **Next.js 15** – App Router & Server Components
* **React 19** – Modern component-based UI
* **Tailwind CSS** – Utility-first styling
* **Stack Auth** – Modern authentication solution
* **Prisma** – Type-safe ORM & migrations
* **PostgreSQL** – Relational database
* **Lucide Icons** – Clean & modern icons
* **Recharts** – Data visualization & analytics
* **TypeScript** – Type safety & better DX
* **Vercel** – Deployment & hosting

---

## ⚡ Features

* 🔐 **Authentication** – Secure login & registration with Stack Auth
* 📊 **Dashboard Analytics** – Inventory insights & metrics
* 📦 **Product Management** – Full CRUD operations
* 🔍 **Search & Filtering** – Quickly find products
* 📄 **Pagination** – Optimized performance for large inventories
* ⚠️ **Low Stock Alerts** – Track critical stock levels
* 💰 **Inventory Value Tracking** – Monitor total stock value
* 📈 **Visual Charts** – Interactive analytics using Recharts
* 📱 **Responsive UI** – Works on desktop & mobile
* 🎨 **Modern Design** – Clean UI with Tailwind CSS
* 🚀 **Server Actions** – Secure form handling
* 🔄 **Real-time Updates** – Instant UI refresh after changes

---

## 👌 Quick Start

### Prerequisites

* Node.js **v18+**
* Git
* PostgreSQL (local or cloud like Neon)

---

### Clone the Repository

```bash
git clone https://github.com/codewithmanohar/eazystocks.git
cd eazystocks
npm install
```

---

## 🔐 Environment Setup

Create a `.env.local` file in the root directory:

```env
DATABASE_URL="postgresql://username:password@localhost:5432/eazystocks"
NEXT_PUBLIC_STACK_PROJECT_ID="your_stack_project_id"
NEXT_PUBLIC_STACK_PUBLISHABLE_CLIENT_KEY="your_publishable_key"
STACK_SECRET_SERVER_KEY="your_secret_key"
```

---

### Database Setup

```bash
npx prisma migrate dev
npx prisma generate
```

---

### Run the App

```bash
npm run dev
```

Visit: **[http://localhost:3000](http://localhost:3000)**

---

## 🖼️ Screenshots

*Add screenshots here to showcase:*

* Dashboard
* Inventory List
* Add Product Form
* Analytics Charts

---

## ☁️ Deployment

### Deploy on Vercel

1. Push your code to GitHub
2. Go to **[https://vercel.com](https://vercel.com)**
3. Import your repository
4. Add environment variables
5. Click **Deploy**

Your app will be live at:

```
https://eazystocks.vercel.app
```

---

### Production Database Options

* **Neon** – Serverless PostgreSQL
* **Supabase** – Open-source Firebase alternative
* **PlanetScale** – MySQL-compatible DB



## 🔗 Useful Links

* Next.js Docs – [https://nextjs.org/docs](https://nextjs.org/docs)
* Stack Auth – [https://stack-auth.com](https://stack-auth.com)
* Prisma – [https://www.prisma.io/docs](https://www.prisma.io/docs)
* Tailwind CSS – [https://tailwindcss.com/docs](https://tailwindcss.com/docs)
* Lucide Icons – [https://lucide.dev](https://lucide.dev)
* Recharts – [https://recharts.org](https://recharts.org)
* Vercel – [https://vercel.com/docs](https://vercel.com/docs)



### ⭐ About

**EazyStocks** – A modern Next.js inventory management system
🌐 Live Demo: [https://eazystocks.vercel.app](https://eazystocks.vercel.app)
