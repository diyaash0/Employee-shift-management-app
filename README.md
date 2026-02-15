# Employee Shift Management System

A full-stack web application built to simplify and centralize employee shift scheduling.  
This system offers intuitive admin and user interfaces to create, manage, and visualize employee shifts efficiently.

It combines a **React frontend** with a **Node.js + Express backend** and a **MongoDB database**, reflecting real-world scheduling and data handling scenarios.

---

## 📌 Application Overview

### Admin Features
- Dashboard with scheduling overview
- Create, update, and manage employee shifts
- Manage team members
- View shift statistics and activity

### User Features
- View assigned shifts
- Track schedules
- Access shift-related statistics

---

## 🚀 Key Features

- 📅 Drag-and-drop calendar for easy shift planning  
- 🌍 Timezone-aware scheduling  
- 🔐 Secure login & JWT-based authentication  
- 📊 Dynamic charts and analytics  
- 📱 Fully responsive user interface  
- ⚙️ RESTful API backend

---

## 🧱 Tech Stack

### Frontend
- React
- React Router
- Tailwind CSS
- ScheduleX Calendar
- Recharts
- Axios
- Vite

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Tokens (JWT)
- bcryptjs
- dotenv
- moment-timezone

---

## ⚙️ Installation & Setup

### 1. Clone the Project
```bash
git clone https://github.com/diyaash0/Employee-shift-management-app.git
cd Employee-shift-management-app

### 2. Backend Setup
```bash
cd backend
npm install
cp .env.example .env
npm start

### 3. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev

