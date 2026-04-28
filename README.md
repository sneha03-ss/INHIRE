# 🚀 InHire — AI-Powered Swipe-Based Hiring Platform  

<p align="center">
<img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ML-FastAPI-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Database-MongoDB-darkgreen?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Working-brightgreen?style=for-the-badge"/>
</p>

---

# 🌟 Overview

**InHire** is an intelligent job and internship discovery platform designed to transform traditional recruitment into a **smart, swipe-based, AI-powered hiring experience**.

Instead of manually browsing job listings, users can **swipe through opportunities**, while the system intelligently recommends roles based on **skill similarity and machine learning analysis**.

This project demonstrates a **complete full-stack microservice architecture** integrating frontend UI, backend APIs, machine learning logic, and database management.

---

# 🎯 Key Features

✨ Swipe-Based Job Discovery  
🧠 AI-Powered Skill Matching  
📄 Resume & Skill Analysis  
📊 Job Compatibility Score  
🔐 Secure JWT Authentication  
📡 REST API Communication  
📂 Recruiter Job Posting System  
⚡ Microservice-Based Architecture  
📈 Real-Time Matching Engine  

---

# 🧠 Machine Learning Engine

The recommendation engine uses **Natural Language Processing techniques** to match candidates with job roles.

### Algorithms Used

- TF-IDF Vectorization  
- Cosine Similarity  
- Skill Matching Logic  

### Match Score Formula
Match Score = Cosine Similarity(User Skills, Job Skills)

This enables **accurate and efficient job recommendations**.

---

# 🏗️ System Architecture

             ┌─────────────────────────────┐
             │         Frontend            │
             │       React + Vite          │
             │                             │
             │ • User Interface            │
             │ • Swipe Job System          │
             │ • Profile Management        │
             └────────────┬────────────────┘
                          │
                          │ REST API Calls
                          ▼
             ┌─────────────────────────────┐
             │          Backend            │
             │      Node.js + Express      │
             │                             │
             │ • Authentication (JWT)      │
             │ • Job Management            │
             │ • User Management           │
             │ • API Routing               │
             └────────────┬────────────────┘
                          │
                          │ ML Requests
                          ▼
             ┌─────────────────────────────┐
             │        ML Service           │
             │         FastAPI             │
             │                             │
             │ • Skill Processing          │
             │ • TF-IDF Vectorization      │
             │ • Cosine Similarity         │
             │ • Match Score Calculation   │
             └────────────┬────────────────┘
                          │
                          │ Database Access
                          ▼
             ┌─────────────────────────────┐
             │         Database            │
             │          MongoDB            │
             │                             │
             │ • Users Collection          │
             │ • Jobs Collection           │
             │ • Applications              │
             └─────────────────────────────┘


---

# 🛠️ Tech Stack

## 🎨 Frontend

- React.js (Vite)
- Tailwind CSS
- JavaScript
- HTML5
- CSS3

## ⚙️ Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## 🤖 Machine Learning

- Python
- FastAPI
- TF-IDF
- Cosine Similarity

---

# 📂 Project Structure
INHIRE
│

├── frontend/ # React Frontend

├── backend/ # Node.js Backend

├── ml-service/ # FastAPI ML Engine

│

├── README.md

├── package.json

├── requirements.txt


---

# ⚙️ Installation Guide

Follow these steps to run the project locally.

---

## 1️⃣ Clone Repository
git clone https://github.com/sneha03-ss/INHIRE.git

cd INHIRE

---

## 2️⃣ Start ML Service


cd ml-service

python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
Runs at:


http://127.0.0.1:8000


---

## 3️⃣ Start Backend


cd backend

npm install
npm start


Runs at:


http://localhost:5000


---

## 4️⃣ Start Frontend
cd frontend

npm install
npm run dev


Runs at:


http://localhost:3000


---

# 🔐 Environment Variables

Create `.env` inside **backend/**


PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/inhire
JWT_SECRET=your_secret_key
ML_SERVICE_URL=http://localhost:8000


---

# 🔄 Workflow


---

# 🎯 Applications

✔ Recruitment Platforms  
✔ Internship Matching Systems  
✔ Resume Screening Tools  
✔ Job Recommendation Systems  
✔ Hiring Automation Platforms  

---

# 🚀 Future Enhancements

- Resume Parsing using NLP  
- Real-time Notifications  
- Cloud Deployment (AWS)  
- Advanced Deep Learning Models  
- Resume Ranking System  




