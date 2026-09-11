# 🚀 GapWise AI

> An AI-powered resume analysis platform that helps job seekers identify skill gaps and improve their resumes based on target job requirements.

## 📌 Overview

**GapWise AI** is a web application designed to help students and job seekers understand how well their resume matches a target job role.

The platform analyzes the user's resume, extracts relevant information such as skills and experience, identifies missing or weak skills, and provides actionable recommendations for improvement.

The goal of GapWise AI is to make resume analysis faster, simpler, and more useful for candidates preparing for internships and job opportunities.

---

## ✨ Features

- 📄 **Resume Analysis**
  - Upload and analyze your resume.
  - Extract relevant skills, experience, and education details.

- 🎯 **Skill Gap Detection**
  - Compare existing skills with target job requirements.
  - Identify missing or insufficient skills.

- 🤖 **AI-Powered Recommendations**
  - Generate personalized suggestions for improving your skill set.
  - Get recommendations based on the identified gaps.

- 📊 **Resume Insights**
  - Understand your current profile.
  - Identify areas that need improvement.

- 💻 **Responsive Interface**
  - Clean and responsive user interface.
  - Works across desktop and mobile devices.

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI
- Generative AI / LLM-based analysis

### Tools & Deployment
- Git
- GitHub
- Postman
- Vercel
- Render

---

## 🏗️ Project Architecture

```text
                         ┌─────────────────┐
                         │      User       │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │ React Frontend  │
                         └────────┬────────┘
                                  │
                              REST API
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Node.js + Express.js    │
                    │       Backend           │
                    └───────────┬─────────────┘
                                │
                    ┌───────────┴───────────┐
                    │                       │
                    ▼                       ▼
          ┌─────────────────┐     ┌─────────────────┐
          │  AI Analysis    │     │ MongoDB Database│
          │     Engine      │     │                 │
          └─────────────────┘     └─────────────────┘
🔄 How It Works
User uploads their resume.
The application processes the resume and extracts relevant information.
The user provides or selects a target job role.
GapWise AI analyzes the resume against the required skills.
The system identifies missing or weak skills.
AI generates recommendations for improving the candidate's profile.
The user can use these insights to prepare for the target role.
📂 Project Structure
GapWise-AI/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/Ansh-choudhary08/GapWise-AI.git
2. Navigate to the Project
cd GapWise-AI
3. Setup Backend
cd backend
npm install

Create a .env file in the backend directory:

PORT=5000
MONGODB_URI=your_mongodb_connection_string

Start the backend:

npm run dev
4. Setup Frontend

Open another terminal:

cd frontend
npm install

Create the required environment file:

VITE_API_URL=http://localhost:5000

Start the frontend:

npm run dev
🌐 Deployment

The application is deployed using:

Frontend: Vercel
Backend: Render
Database: MongoDB Atlas
🔗 Live Demo

Frontend:
https://gapwise-ai-sigma.vercel.app

Backend:
https://gapwise-ai-yylj.onrender.com

🔐 Environment Variables

Never commit sensitive credentials or API keys to GitHub.

Backend .env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
Frontend .env
VITE_API_URL=your_backend_url

Make sure .env files are included in .gitignore:

.env
.env.local
.env.production
🎯 Future Improvements
📑 Support for additional resume formats.
🔍 Improved job-description matching.
📈 Resume scoring and analytics.
🎓 Personalized learning roadmaps for missing skills.
💼 Job recommendations based on candidate skills.
📊 Skill-gap progress tracking.
🔐 Enhanced authentication and user profiles.
👨‍💻 Author
Ansh Choudhary

GitHub:
https://github.com/Ansh-choudhary08

Portfolio:
https://ansh-choudhary-portfolio.netlify.app/

⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!
