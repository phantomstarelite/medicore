
# 🏥 Doctor Appointment Booking System

A **full-stack Doctor Appointment Booking System** built using the **MERN stack** that enables patients to book appointments with doctors, doctors to manage their schedules, and administrators to control the platform.

The project focuses on **real-world healthcare workflows**, **role-based access**, and **scalable full-stack architecture**.

---

## 📌 Project Overview

This application is designed with **three independent user roles**, each having a dedicated interface and responsibilities:

- **Patients** can browse doctors and book appointments.
- **Doctors** can manage availability, appointments, and profiles.
- **Admins** can manage doctors, appointments, and system data.

The system ensures smooth interaction between frontend and backend using REST APIs and secure authentication.

---

## 🗂️ Project Structure

```

root/
│
├── admin/        # Admin Dashboard (React + Vite + Tailwind)
├── frontend/     # Patient & Doctor Interface (React + Vite + Tailwind)
├── backend/      # REST API (Node.js + Express + MongoDB)
│
└── README.md

```

---

## 🧠 Tech Stack

### Frontend (Admin & User)
- React.js
- Vite
- Tailwind CSS
- React Router
- Context API
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

## ✨ Core Features

### 👨‍⚕️ Patient Module
- User authentication
- Browse doctors by specialization
- View doctor profiles and availability
- Select date and time slots
- Book appointments
- View booking history

---

### 👩‍⚕️ Doctor Module
- Doctor login
- Profile management
- Availability toggle (Available / Not Available)
- View upcoming appointments
- Track consultation earnings

---

### 🛠️ Admin Module
- Secure admin dashboard
- Add new doctors (profile image, specialization, fees)
- View and manage appointments
- Cancel appointments if required
- Monitor total doctors, patients, and bookings

---

## 🏗️ Backend Architecture

```

backend/
│
├── config/        # Database & environment configuration
├── controllers/   # Business logic
├── middleware/    # Authentication & authorization
├── models/        # User, Doctor, Appointment schemas
├── routes/        # API routes
├── server.js      # Server entry point

````

The backend follows an **MVC architecture** to keep the code modular, readable, and scalable.

---

## 🔄 Application Flow

1. User registers or logs in.
2. Doctors are fetched dynamically from the database.
3. Appointment slots are generated based on doctor availability.
4. Booking data is stored securely in MongoDB.
5. Role-based dashboards display relevant data to users.
6. Admin controls system-wide data and operations.

---

## 🧪 Environment Variables

Create `.env` files inside each module.

### Backend `.env`
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
````

### Frontend / Admin `.env`

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

---

## ▶️ How to Run the Project

### Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install

# Admin
cd admin
npm install
```

---

### Start the Servers

```bash
# Backend
npm run dev

# Frontend
npm run dev

# Admin
npm run dev
```

---

## 🌍 Local URLs

* Backend API → `http://localhost:5000`
* Frontend → `http://localhost:5173`
* Admin Panel → `http://localhost:5174`

---

## 🔐 Security Considerations

* JWT-based authentication
* Role-based route protection
* Environment variable protection
* Centralized error handling

---

## 🚀 Future Improvements

* Online payment integration
* Email/SMS appointment reminders
* Doctor ratings and reviews
* Video consultation support
* Admin analytics dashboard
* Docker & CI/CD integration

---

## 👨‍💻 Author

**Pratik**
MERN Stack Developer | Web Development | Cybersecurity Enthusiast

GitHub: [https://github.com/phantomstarelite](https://github.com/phantomstarelite)

---

## ⭐ Acknowledgement

This project was built as part of a **hands-on full-stack learning journey**, focusing on understanding **real-world application flow**, **clean architecture**, and **scalable system design**.

---
