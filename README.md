# 🌐 Cloud-Based Recruitment Automation System – Frontend

Live URL: https://recurit.netlify.app/

## 📌 Overview

This is the frontend of the Cloud-Based Recruitment Automation System.  
It provides dashboards for Recruiters and Candidates to manage job postings, resume uploads, candidate ranking, analytics, and application tracking.

The frontend is built using React (Vite) and Tailwind CSS and deployed on Netlify.

---

## 🚀 Tech Stack

- React (Vite)
- Tailwind CSS
- Axios (API calls)
- JWT Authentication
- Chart.js / Recharts (Analytics)
- Netlify (Hosting)

---

## 🖥 Features

### 👤 Candidate Dashboard
- Register/Login
- Upload Resume (PDF)
- View Match Score
- Check Application Status:
  - Under Review
  - Shortlisted
  - Selected
  - Rejected

### 🧑‍💼 Recruiter Dashboard
- Login/Register
- Upload Job Description
- View Ranked Candidates
- Manual Shortlist / Reject
- View Analytics Dashboard:
  - Candidates per Job
  - Average Match Score
  - Skill Frequency
  - Shortlisted Ratio

### 🤖 Chatbot (Optional)
- Recruiter queries:
  - “Show top 5 shortlisted candidates”
- Candidate queries:
  - “Check my application status”

---

## ⚙️ Installation (Local Setup)

```bash
git clone https://github.com/Kishorp28/front.git
cd frontend
npm install
npm run dev
