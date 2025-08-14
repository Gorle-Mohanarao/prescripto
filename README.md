# 🩺 Prescripto - Full Stack Doctor Appointment Booking System

[![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue)](#)
[![License](https://img.shields.io/badge/License-MIT-green)](#license)
[![Deployed on Render](https://img.shields.io/badge/Deployed-Render-orange)](#live-demo)

Prescripto is a **Full Stack MERN Application** that allows patients to seamlessly book appointments with doctors based on their health issues.  
The platform features **three levels of authentication** – **Patient**, **Doctor**, and **Admin** – making it suitable for both individual doctors and large hospitals.  
It includes **online payment integration**, multiple doctor categories, and a user-friendly dashboard for each role.

---

## 🚀 Live Demo
- **Website (Render):** [Live Demo Link](https://prescripto-frontend-javc.onrender.com/)
- **GitHub Repository:** [GitHub Repo](https://github.com/Gorle-Mohanarao/prescripto)

---

## 📌 Features

### 👨‍⚕️ Patient Features
- Secure registration and login.
- Search and filter doctors by specialty:
  - General Physician
  - Dermatologist
  - Gastroenterologist
  - *(and more...)*
- Book and manage appointments.
- Pay fees securely via integrated **payment gateway**.

### 🩺 Doctor Features
- Login and manage profile.
- View and manage upcoming appointments.
- Track earnings.
- Update personal information and availability.

### 🛠 Admin Features
- Manage doctor profiles and categories.
- View and control all appointments.
- Access an overview of system activity.

---

## 🛠 Tech Stack

**Frontend (Patient + Doctor):**  
- React.js  
- Tailwind CSS / CSS3  
- Axios  

**Admin Panel:**  
- React.js (separate interface)  
- Tailwind CSS  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (Mongoose ORM)  

**Payments:**  
- Razorpay / Stripe  

**Deployment:**  
- Render (Backend)  
- Render (Frontend & Admin)  

---

## 📂 Project Structure
```plaintext
Prescripto/
├── admin/                  # Admin Dashboard (React)
│   ├── public/
│   ├── src/
│   └── package.json
├── backend/                # Backend (Node + Express)
│   ├── config/             # DB & payment configs
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── frontend/               # Patient & Doctor Frontend (React)
│   ├── public/
│   ├── src/
│   └── package.json
└── README.md
