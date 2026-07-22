# 🛡️ Defend Your Experience AI

## Day 52 - 60 Days of Claude Challenge

An AI-powered interview preparation platform designed to help candidates confidently explain, defend, and improve their professional experiences.

The project transforms a traditional resume into an interactive AI coaching experience where users can practice explaining their projects, skills, achievements, and technical decisions through adaptive AI interviews.

---

# 📌 Overview

Many candidates have strong projects and skills but struggle to communicate their experience effectively during interviews.

**Defend Your Experience AI** helps solve this problem by:

- Extracting important claims from resumes
- Conducting personalized AI interviews
- Evaluating answers based on multiple factors
- Providing actionable coaching feedback

The goal is to help users become more confident and interview-ready.

---

# 🎯 Objectives

The main objectives of this project are:

- Convert resume information into structured claims
- Simulate realistic technical interviews
- Identify strengths and weaknesses in answers
- Improve communication and storytelling skills
- Generate personalized improvement reports

---

# 🚀 Features

## 1. AI Resume Claim Extraction

The system analyzes resume/profile text and extracts important experience claims.

Supported categories:

- Projects
- Skills
- Internships
- Certifications
- Academic achievements
- Behavioral strengths


Example:


Input:
Built an AI chatbot using Python and APIs

Output:

Claim:
AI chatbot development project

Category:
Project


---

## 2. Adaptive AI Interview

The AI interviewer creates personalized questions based on extracted claims.

Features:

- Claim-based questions
- Conversation history tracking
- Adaptive questioning
- Interview progress management
- Closing summary generation

---

## 3. AI Answer Evaluation

User answers are evaluated across four important dimensions:

| Evaluation Area | Description |
|---|---|
| Confidence | How confidently the answer is explained |
| Depth | Understanding of concepts and technical details |
| Communication | Clarity and structure of explanation |
| Evidence | Supporting examples and proof |

Scores are generated between:


0 - 100


---

## 4. Defense Report Generation

After completing the interview, the AI generates a personalized report.

The report includes:

### Claim Breakdown

- Strong points
- Weak areas
- Missing evidence
- Suggested improvements


### Coaching Summary

- Strongest areas
- Biggest risks
- Stories to prepare
- Concepts to revise

---

# 🔄 System Workflow


Resume / Profile Text
|
↓
AI Claim Extraction
|
↓
Adaptive Interview
|
↓
Answer Scoring
|
↓
Defense Report
|
↓
Personalized Coaching


---

# 🔌 API Documentation

Backend API design is available in:


API.md


## Available Endpoints

### Test AI Connection


POST /api/test


Purpose:
- Verify frontend → backend → AI communication


---

### Extract Resume Claims


POST /api/extract-claims


Purpose:
- Convert resume text into structured claims


---

### Generate Interview Questions


POST /api/interview-turn


Purpose:
- Create adaptive AI interview conversations


---

### Score Answers


POST /api/score-answer


Purpose:
- Evaluate interview responses silently


---

### Generate Final Report


POST /api/generate-report


Purpose:
- Create complete Defense Report

---

# 🏗️ Architecture Principles

## Reliability

The system follows:

- Input validation
- AI response validation
- Error handling
- Rate limiting
- Fallback responses


## Security

Version 1.0 scope:

- No authentication
- Public API endpoints
- CORS allowlist protection
- Frontend origin restriction

Authentication is intentionally out of scope for v1.0.

---

# 🛠️ Tech Stack

## Frontend

- React / HTML / CSS / JavaScript
- Responsive UI


## Backend

- Node.js
- Express.js
- REST API Architecture


## AI Layer

- Large Language Model API
- Structured JSON responses
- AI evaluation pipeline


## Documentation

- Markdown
- GitHub

---

# 📂 Project Structure


Day52/
│
├── README.md
├── API.md
├── Day52.md
├── notes.md
├── learnings.md
├── prompts.md
└── reflection.md


---

# 📈 Current Progress

## Completed

✅ Product idea definition  
✅ User workflow design  
✅ Backend API architecture  
✅ AI interview flow planning  
✅ Error handling strategy  
✅ Documentation structure  


## Version


v1.0 Design Phase


---

# 🔮 Future Improvements

Future versions can include:

- User authentication
- Resume file upload
- Voice-based mock interviews
- Interview history dashboard
- Performance analytics
- Personalized preparation roadmap

---

# 🏆 Challenge Progress

## Day 52 / 60 Completed

Today’s focus:

- AI Product Design
- Backend API Planning
- Interview Workflow Architecture
- AI Coaching System Design

**Learn → Build → Document → Improve 🚀**
