# INHIRE
AI-powered swipe-based job and internship discovery platform with ML-based matching, built using React, Node.js, MongoDB, and FastAPI.

## 📌 Project Overview

InHire is an AI-powered job and internship discovery platform designed to simplify the recruitment and job search process through an intuitive swipe-based interface. Inspired by modern swipe-style applications, the platform allows users to browse opportunities dynamically while leveraging machine learning techniques to provide personalized job recommendations.

The system integrates a full-stack architecture consisting of a React-based frontend, a Node.js and Express backend, MongoDB for data storage, and FastAPI-powered AI services. It enables efficient job discovery, application management, and intelligent matching between candidates and recruiters.

The platform focuses on enhancing user engagement, improving job discovery efficiency, and reducing the time required to find relevant opportunities.

## 🚀 Key Features

- 🔄 Swipe-Based Job Discovery Interface
- 🤖 AI-Powered Job Recommendation System
- 📄 Resume-Based Matching Support
- 👤 User Authentication and Role Management
- 💼 Job Posting and Application Tracking
- 📊 Intelligent Match Scoring Mechanism
- 📁 MongoDB-Based Data Storage
- 🌐 Full-Stack Web Architecture
- ⚡ FastAPI Integration for AI Processing
- 🎯 Personalized Job Suggestions

## 🛠️ Tech Stack

### Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB (MongoDB Atlas)

### AI / Machine Learning
- Python
- FastAPI

### Other Tools
- REST APIs
- Git & GitHub
- JWT Authentication

## ▶️ How to Run the Project

⚠️ Run frontend, backend, and ML service in **three separate terminals**.

---

## 📋 Prerequisites

Make sure these are installed:

- Node.js (v18 or higher)
- Python (v3.9 or higher)
- npm
- MongoDB Atlas or Local MongoDB
- Git

Check versions:

node -v  
python --version  
npm -v  

---

## 📥 Step 1: Clone Repository

git clone https://github.com/sneha03-33/INHIRE.git

cd InHire

---

## 🧠 Terminal 1 — Run ML Service

cd ml-service

Create virtual environment:

python -m venv venv

Activate virtual environment:

Windows:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run FastAPI server:

python main.py

Server runs at:

http://localhost:8000

---

## ⚙️ Terminal 2 — Run Backend

cd backend

Install dependencies:

npm install

Create environment file:

copy .env.example .env

Run backend:

npm run dev

Server runs at:

http://localhost:5000

---

## 🌐 Terminal 3 — Run Frontend

cd frontend

Install dependencies:

npm install

Create environment file:

copy .env.example .env

Run frontend:

npm run dev

Frontend runs at:

http://localhost:5173

---

## 🌍 Open the Application

Open browser and go to:

http://localhost:5173

---

## ✅ Test Flow

1. Register as Job Seeker
2. Complete profile
3. Upload resume
4. Swipe jobs
5. Apply to jobs
6. Login as Company
7. Create job
8. View applicants




