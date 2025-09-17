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
  - **ADMIN** → Manage patients, doctors, appointments.  
  - **DOCTOR** → accept/reject appointments.  
  - **PATIENT** → Can view/edit their profile, Can register themselves, book/delete appointments, view doctors.
    
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
⚠️ if .env not there use the above format to create a new one

### Note : the current ADMIN username and password is
- email - admin@medicare.pro
- password - Admin@123
