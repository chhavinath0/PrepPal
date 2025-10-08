# 🤖 PrepPal – AI-Powered Interview Preparation Platform

PrepPal is an **AI-driven interview preparation platform** that helps candidates get ready for real-world interviews.  
Users can **upload their resume**, **set interview difficulty**, **choose duration and job role**, and receive **personalized AI-generated interview questions**.  
The platform conducts an **interactive interview** with **speech recognition**, and at the end, it provides a **detailed feedback report** based on **technical**, **behavioral**, and **communication** skills.

---

## 🚀 Features

### 🧠 AI Interview Generation
- Powered by **Google Gemini 2.5 Flash** (Generative AI).
- Dynamically generates customized questions based on:
  - Uploaded resume
  - Selected role
  - Difficulty level
  - Chosen duration

### 🎤 Real-Time Interaction
- Integrated **Speech Recognition API** for answering questions verbally.
- Mimics an actual interview environment with sequential question flow.

### 📋 Smart Feedback System
- AI evaluates user responses and generates feedback on:
  - **Technical proficiency**
  - **Behavioral alignment**
  - **Communication clarity**

### 💾 Resume Upload
- Users can upload their resumes (PDF format), which are parsed to extract relevant skills and experiences.

### 🌐 Fully Deployed
- Backend hosted on **Vercel**.
- Frontend built using **Vite + React** for blazing-fast performance.
- Persistent data storage using **MongoDB Atlas**.

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React (Vite), TailwindCSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas |
| **AI Model** | Google Gemini 2.5 Flash |
| **Hosting** | Vercel (API + Frontend) |
| **Speech** | Web SpeechRecognition API |

---



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/chhavinath0/PrepPal.git
cd PrepPal

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/chhavinath0/PrepPal.git
cd PrepPal
cd server
npm install


PORT=8000
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_google_generative_ai_key


npm start
front end setup
cd ../client
npm install
npm run dev
