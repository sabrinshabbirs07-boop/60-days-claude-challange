# 🛡️ Defend Your Experience AI

## Day 52 — 60 Days of Claude Challenge

An AI-powered interview preparation platform that helps candidates confidently explain, defend, and improve their professional experiences.

The goal of this project is to transform a resume from a static document into an interactive AI coaching experience where users can practice defending their projects, skills, and achievements through adaptive interviews.

---

# 📌 Project Overview

During technical interviews, many candidates struggle to clearly explain:

- Their projects
- Technical decisions
- Skills and expertise
- Real-world impact
- Problem-solving approach

**Defend Your Experience AI** solves this problem by analyzing resume/profile information, extracting important claims, conducting AI-powered interviews, evaluating answers, and generating a personalized Defense Report.

---

# 🎯 Objective

Build an AI mentor that helps users:

✅ Discover their strongest resume claims  
✅ Practice explaining their experience  
✅ Identify weak areas in their answers  
✅ Improve communication and technical storytelling  
✅ Prepare better for interviews  

---

# 🚀 Core Workflow


Resume / Profile Input
|
↓
AI Claim Extraction
|
↓
Adaptive AI Interview
|
↓
Answer Evaluation
|
↓
Defense Report Generation
|
↓
Personalized Coaching


---

# ✨ Features

## 1. AI Resume Claim Extraction

The system converts resume text into structured and defensible claims.

Categories supported:

- Project
- Skill
- Internship
- Certification
- Academic Achievement
- Behavioral Strength

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

The AI interviewer generates questions based on extracted claims.

Features:

- Personalized questions
- Conversation memory
- Claim-focused questioning
- Maximum question limit
- Closing interview flow

---

## 3. AI Answer Scoring

Each answer is evaluated across four dimensions:

| Metric | Purpose |
|---|---|
| Confidence | How confidently the answer is delivered |
| Depth | Technical understanding |
| Communication | Clarity of explanation |
| Evidence | Supporting proof/examples |

Scores are generated between:


0 - 100


---

## 4. Defense Report Generation

After the interview session, AI generates a detailed coaching report.

Includes:

### Claim Breakdown

- Convincing points
- Weak points
- Missing evidence
- Suggested improvements


### Coaching Summary

- Strongest areas
- Biggest risks
- Stories to prepare
- Concepts to revise

---

# 🔌 API Architecture

Backend API documentation:


API.md


## Available Endpoints

### Test Connection


POST /api/test


Purpose:
- Verify frontend → backend → AI communication


---

### Extract Claims


POST /api/extract-claims


Purpose:
- Convert resume text into structured claims


---

### Interview Session


POST /api/interview-turn


Purpose:
- Generate adaptive AI interviewer responses


---

### Score Answer


POST /api/score-answer


Purpose:
- Evaluate user answers silently in the background


---

### Generate Report


POST /api/generate-report


Purpose:
- Create final Defense Report and coaching insights

---

# 🏗️ System Design Principles

## Reliability

The system follows:

- Input validation
- AI response validation
- Error handling
- Rate limit handling
- Fallback responses

---

## Security

Version 1.0:

- No authentication
- Public endpoints
- CORS allowlist protection
- Frontend-origin restriction

(Authentication is intentionally out of scope according to PRD.)

---

# 🛠️ Tech Stack

## Frontend

- React / HTML / CSS / JavaScript
- Responsive UI

## Backend

- Node.js
- Express.js
- REST API Architecture

## AI

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
├── notes.md
├── learnings.md
├── prompts.md
└── reflection.md


---

# 📈 Current Progress

## Completed

✅ Product idea defined  
✅ User workflow designed  
✅ Backend API architecture created  
✅ AI interaction flow planned  
✅ Error handling strategy documented  


## Version


v1.0 Design Phase


---

# 🔮 Future Improvements

- User authentication
- Resume file upload
- Voice interview mode
- Interview history tracking
- Performance analytics dashboard
- Personalized preparation roadmap

---

# 🏆 Challenge Progress

## Day 52/60 — Completed

This day focused on designing an AI-powered interview defense system with:

- Product thinking
- Backend architecture
- API planning
- AI workflow design

**Learning → Building → Documenting → Improving 🚀**
