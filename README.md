# 📦 EszyStock – Inventory Management System

**EszyStock** is a modern **inventory management web application** designed to help businesses efficiently manage stock, sales, and operations.
Built using **Next.js 16**, **React 19**, **Prisma**, and **Tailwind CSS**, it delivers performance, scalability, and a clean user experience.

---

## 🚀 Features

* 📊 Interactive dashboard with analytics
* 📦 Inventory & stock management
* 📈 Sales tracking and reporting
* 👥 User authentication & role-based access
* ⚡ Fast UI powered by Next.js & React
* 🗄️ Database management using Prisma ORM
* 🎨 Modern UI with Tailwind CSS
* 📱 Fully responsive design

---

## 🛠 Tech Stack

### Frontend

* **Next.js 16**
* **React 19**
* **Tailwind CSS**
* **Lucide Icons**
* **Recharts**

### Backend & Tools

* **Prisma ORM**
* **Node.js**
* **TypeScript**
* **Dotenv**

---

## 📁 Project Structure

```
inventory-management/
│
├── app/                # App Router (Next.js)
├── components/         # Reusable components
├── lib/                # Utility functions
├── prisma/             # Prisma schema & migrations
├── public/             # Static assets
├── styles/             # Global styles
├── .env                # Environment variables
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/codewithmanohar/eszystock.git
cd eszystock
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file in the root directory:

```env
DATABASE_URL="your_database_url_here"
```

---

### 4️⃣ Setup Prisma

```bash
npx prisma generate
npx prisma migrate dev
```

---

### 5️⃣ Start the development server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:3000
```

---

## 🧪 Available Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start development server |
| `npm run build` | Build for production     |
| `npm start`     | Start production server  |
| `npm run lint`  | Run ESLint               |

---

## 📊 Charts & Analytics

* Built using **Recharts**
* Supports:

  * Area charts
  * Bar charts
  * KPI dashboards
* Optimized for performance and clarity

---

## 🔐 Authentication & Security

* Secure authentication system
* Role-based access control
* Environment-based configuration

---

## 📌 Future Enhancements

* Role-based dashboards (Admin / Staff)
* Stock alerts & notifications
* Export reports (PDF / Excel)
* Dark mode support
* API integrations

---

## 👨‍💻 Developer

**Manohar Kumar**
Full Stack Developer

