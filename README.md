InterviewAI – AI-Powered Interview Preparation Platform

Overview

InterviewAI is a full-stack MERN application that helps users prepare for interviews using AI-generated reports and resume analysis.

Features

- User Authentication (JWT)
- AI-powered Interview Reports
- Resume Analysis
- Skill Gap Detection
- Personalized Preparation Plan
- Resume PDF Generation

Tech Stack

- React.js
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Google Gemini AI
- Puppeteer

Local Setup

Backend

cd Backend
npm install
npm start

Frontend

cd Frontend
npm install
npm run dev

Environment Variables

Create Backend/.env

GOOGLE_GENAI_API_KEY=your_api_key
MONGO_URI=your_mongodb_connection_string