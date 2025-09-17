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

If you get 'vite' is not recognized, ensure dependencies are installed with npm install.

### 🔐 Role-Based Access
  - **ADMIN** → Manage patients, doctors, appointments.  
  - **DOCTOR** → accept/reject appointments.  
  - **PATIENT** → can manage their profile, can self-register, book/delete appointments, view doctors.
    
### 🧠 Tech Stack

| Layer       | Technology         |
|-------------|--------------------|
| Frontend    | React, Tailwind CSS|
| Backend     | Node.js, Express   |
| ORM         | Prisma             |
| Database    | MySQL              |
| Auth        | JWT-based          |
| Dev Tools   | Vite, Nodemon      |

### 📦 Environment Variables
Create a .env file in medicare-pro with:

DATABASE_URL="mysql://user:password@localhost:3306/medicare"
JWT_SECRET="your-secret-key"

⚠️ if .env not there use the above format to create a new one.

### 🔐 Demo Admin Credentials  
Use the following credentials to log in as an admin during evaluation:  
**Email**: `admin@medicare.pro`  
**Password**: `Admin@123`  
*Note: These are default credentials for demo purposes only.*

### 🧭 How to Explore the App

This app supports three user roles: **Admin**, **Doctor**, and **Patient**. Here's how to experience each flow:

🔐 Admin Access  
Use the demo credentials listed above to log in as an admin.

Once logged in, the admin can:  
- 🩺 Add and manage doctor accounts  
- 👥 View and manage patient records  
- 📅 Oversee appointment scheduling  

👨‍⚕️ Doctor Access  
After creating a doctor account via the admin dashboard:  
- Log in using the newly created doctor credentials  
- Access the **Doctor Dashboard**  
- Accept or reject appointment requests from patients  

🧑‍⚕️ Patient Access  
To explore the patient flow:  
- Click **Sign Up** on the login page to create a patient account  
- Log in as a patient to:  
  - View and edit your profile  
  - Book or cancel appointments  
  - Browse available doctors  

This walkthrough demonstrates the full role-based access system and dashboard functionality.
