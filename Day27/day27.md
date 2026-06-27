# Prior Authorization Story Simulator

## Day 27/60 — Claude Challenge

An interactive healthcare education simulator that explains the complex Prior Authorization (PA) process through a story-based experience.

Users follow Rahul's healthcare journey as he navigates diagnosis, insurance approval, denial, appeal, and final authorization while learning how the healthcare system works through Priya, a healthcare operations specialist.

---

## Project Overview

The Prior Authorization Story Simulator is a single-file HTML application built using:

- HTML
- Tailwind CSS CDN
- Vanilla JavaScript

The goal of this project is to transform a complicated healthcare workflow into an easy-to-understand interactive learning experience.

Instead of reading documentation, users experience the process through:

- Interactive conversations
- Decision-based choices
- Progress tracking
- Healthcare workflow explanations

---

## Features

### Interactive Story Experience

Follow Rahul's journey through 8 healthcare stages:

1. Doctor Visit
2. Insurance Roadblock
3. Understanding Prior Authorization
4. Insurance Review Process
5. Denial Stage
6. Appeal Process
7. Approval and Authorization
8. Final Takeaways

---

## Characters

### Rahul — Patient

Represents the patient's perspective:

- Questions about treatment
- Insurance concerns
- Understanding the healthcare process


### Priya — Healthcare Operations Specialist

Explains:

- Prior Authorization workflow
- Insurance requirements
- Appeal strategies
- Healthcare system challenges

---

## Gameplay Flow

After every story chapter:

- Users choose between two options
- Choices affect:
  - Timeline
  - Score
  - Dialogue path

The experience can be restarted to explore different outcomes.

---

## Progress Tracking

The application includes:

- Scene progress bar
- Day counter
- Score system
- Story completion tracking

---

## Healthcare Workflow Covered

The simulator explains:

Provider  
↓  
PA Request  
↓  
Payer Review  
↓  
Approval or Denial  
↓  
Appeal Process  
↓  
PA Saved on File

---

## Learning Outcomes

Users understand:

- Why Prior Authorization exists
- How insurance reviews medical requests
- Why documentation matters
- How denials can be appealed
- How healthcare teams measure PA performance

---

## Technical Implementation

### Frontend

- HTML5
- Tailwind CSS
- JavaScript


### JavaScript Concepts Used

- createElement()
- appendChild()
- DOM manipulation
- State management
- Event handling
- Dynamic rendering


Important implementation:

No direct innerHTML usage for chat messages.

Every conversation bubble is created dynamically using:

createElement + appendChild

[PROJEC HTML FILE](https://github.com/sabrinshabbirs07-boop/60-days-claude-challange/blob/main/Day27/pa-story-simulator.html)



