# 🏥 Medicare Hospital System

A full-stack healthcare dashboard designed for managing patients, doctors, appointments, and role-based access.  
Built with **React**, **Tailwind CSS**, **Node.js**, **Express**, **Prisma**, and **MySQL**.

---

## 🚀 Getting Started

### 🔧 Backend Setup (`medicare-pro`)
- cd medicare-pro
- npm install
- npx prisma generate
- npm run dev

### 🎨 Frontend Setup (medicare-frontend)
- cd medicare-frontend
- npm install
- npm run dev

If you see 'vite' is not recognized, run npm install first to install dependencies.

### 🔐 Role-Based Access

Admin: Full access to manage doctors, patients, and appointments
Doctor: View assigned patients, update records
Patient: Book appointments, view prescriptions and history

### 🧠 Tech Stack
Layer	Technology
Frontend	React, Tailwind CSS
Backend	Node.js, Express
ORM	Prisma
Database	MySQL
Auth	JWT-based authentication
Dev Tools	Vite, Nodemon

### 📦 Environment Variables
Create a .env file in medicare-pro with:

DATABASE_URL="mysql://user:password@localhost:3306/medicare"
JWT_SECRET="your-secret-key"
⚠️ .env is excluded from Git tracking via .gitignore

### Note : the current ADMIN username and password is
email - admin@medicare.pro
password - Admin@123
