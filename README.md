# 🎯 AI Resume Analyzer

An AI-powered resume analyzer that matches your resume against a job description and gives detailed feedback.

## Features
- Upload PDF or DOCX resume
- Paste any job description
- Get an AI-powered match score (0-100%)
- See matched and missing skills
- Get strengths and improvement suggestions
- Beautiful dark UI with animated score chart

## Tech Stack
- **Frontend:** React, Recharts, Lucide Icons
- **Backend:** Flask, Python
- **AI:** Groq API (Llama 3.3 70B)
- **Libraries:** PyPDF2, python-docx

## Setup

### Backend
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

Add your Groq API key to .env file:
GROQ_API_KEY=your_key_here

Run Flask:
python app.py

### Frontend
cd frontend
npm install
npm start

Open http://localhost:3000 in your browser.

## How to Use
1. Upload your resume (PDF or DOCX)
2. Paste a job description
3. Click Analyze Resume
4. Get your match score and detailed feedback

## Built by
Muhammad Ubaid Idrees — BS AI Student
Dawood University of Engineering & Technology, Karachi