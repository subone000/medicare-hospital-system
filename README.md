# 🏥 Medicare Pro - Hospital Management System

A full-stack **role-based hospital management system** built with **React (frontend)** and **Node.js + Express + Prisma (backend)**.  
It manages patients, doctors, and appointments with secure role-based access.

---

## 🚀 Roles & Access
- **Admin** → Manage patients, doctors, appointments.  
- **Doctor** → accept/reject appointments.  
- **Patient** → View/edit profile, Self-register, view doctors, book/delete appointments.  

---

## 🛠️ Tech Stack
- **Frontend:** React, Bootstrap  
- **Backend:** Node.js, Express.js, Prisma ORM  
- **Database:** MySQL  
- **Auth:** JWT + bcrypt  

---

### 📑 Submission

✅ Source code uploaded

✅ Demo video → demo.mp4

✅ Presentation → presentation.pdf

---

## ▶️ How to Run
```bash
# Backend
cd medicare-pro
npm install
npx prisma migrate dev
npm run dev

# Frontend
cd medicare-frontend
npm install
npm start
