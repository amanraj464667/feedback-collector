# 📬 Feedback Collector App

A full-stack feedback submission platform built using **React (Vite)** for the frontend and **Express + MongoDB** for the backend. Users can submit feedback, and admins can view all submitted feedback in a clean interface.

---

## 🛠 Tech Stack

- **Frontend:** React, Tailwind CSS, Vite, React Hot Toast
- **Backend:** Express.js, MongoDB (via Mongoose), dotenv, CORS
- **Deployment:** Frontend on Netlify, Backend on Render

---

## 📁 Project Structure

feedback-collector/ │ ├── frontend/ # React Vite app │ └── src/ │ └── FeedbackForm.jsx │ └── .env │ └── vite.config.js │ └── package.json │ ├── backend/ # Express + MongoDB API │ └── server.js │ └── .env │ └── models/ │ └── routes/ │ └── package.json


---

## 🚀 Features

- ✨ Submit feedback with name, email, and message
- ✅ Input validation and toast notifications
- 🔐 Admin panel to view submitted feedback
- 🌐 Backend connected to MongoDB Atlas
- 📡 Full deployment on Vercel (frontend) and Render (backend)

---

## 🔧 Environment Variables

### Frontend (`frontend/.env`)
VITE_BACKEND_URL=https://your-render-backend-url.onrender.com


### Backend (`backend/.env`)
MONGODB_URI=your-mongodb-connection-uri PORT=5000


> ⚠️ Don't forget to add `.env` to your `.gitignore` file.

---

## 🧑‍💻 Getting Started Locally

### 1. Clone the Repo
git clone [https://github.com/your-username/feedback-collector.git](https://github.com/amanraj464667/feedback-collector.git)

### 2. Setup backend
cd backend
npm install
npm start

### 3. Setup Frontend
cd frontend
npm install
npm run dev




