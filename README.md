# Hi there, I'm MD RAJA KHAN 👋

Welcome to my GitHub profile! I am an aspiring web developer passionate about building clean, responsive, and user-friendly web applications.

# Online Examination Management System 🎓

A highly scalable and secure online assessment platform built using the MERN stack. Engineered for high performance, this application reliably supports 100+ concurrent users without degradation, providing a seamless experience for both exam administration and test-taking.

---

## ✨ Features

- **High-Performance Architecture:** Engineered to support **100+ concurrent users** seamlessly without any performance degradation.
- **Role-Based Dashboards:** Crafted tailored interfaces for administrators and students, streamlining the entire process of exam creation, distribution, and management.
- **Automated Grading System:** Implemented advanced automated result generation logic for instant and accurate score calculation.
- **Optimized Database:** Designed and optimized **MongoDB schemas** to significantly improve data retrieval efficiency, reducing latency and ensuring high system reliability.
- **Secure Authentication:** Robust user authentication ensuring secure access to assessments and sensitive result data.
- **Responsive UI:** Clean, intuitive interface built for seamless navigation across all devices.

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- JWT Authentication
- Bcrypt.js

### Database
- MongoDB
- Mongoose

---

# 📂 Project Structure

```bash
online-examination-system/
│
├── frontend/
│
└── backend/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/MDRAJAKHAN/online-examination-system.git
```

---

# 🚀 Backend Setup

## Go to backend folder

```bash
cd backend
```

## Install dependencies

```bash
npm install
```

## Create `.env` file

```env
MONGO_URI=mongodb://127.0.0.1:27017/examDB
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

## Start backend server

```bash
node server.js
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 💻 Frontend Setup

## Open new terminal

```bash
cd frontend
```

## Install dependencies

```bash
npm install
```

## Start frontend

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 📦 Required Packages

## Frontend Packages

```bash
npm install axios react-router-dom
```

```bash
npm install -D tailwindcss postcss autoprefixer
```

---

## Backend Packages

```bash
npm install express mongoose cors dotenv bcryptjs jsonwebtoken
```

---

# 🎯 How It Works

1. **Administrators** log in to their tailored dashboard to quickly create subjects, configure exams, and manage question banks.
2. **Students** log in to view their assigned exams on a dedicated student interface.
3. The platform easily handles **100+ students** starting and submitting their exams concurrently.
4. Upon exam completion, the custom **automated result generation logic** instantly calculates the score.
5. Optimized data retrieval ensures administrators can instantly pull massive result datasets without system lag.

---

# 🔐 Authentication

- Secure JWT-based authentication
- Strict separation of concerns between Admin and Student routes
- Password hashing via bcrypt.js

---

# 👨‍💻 Author

## MD RAJA KHAN

- LinkedIn: https://linkedin.com/in/md-raja-khan-6b9070226
- GitHub: https://github.com/MDRAJAKHAN

---
