# UnlockED – System Architecture

## 1. Architecture Overview

UnlockED follows a frontend-backend architecture with AI integration and centralized database storage.

## 2. System Components

### Frontend – React
- Student registration and login.
- Career interest assessment interface.
- Skill gap analysis dashboard.
- Personalized learning roadmap.
- Progress tracking.
- Internship and job opportunity display.

### Backend – FastAPI
- Handles API requests.
- Processes student profile information.
- Performs skill gap analysis.
- Communicates with Gemini API.
- Retrieves and stores student information.

### Database – PostgreSQL
Stores:
- Student profiles.
- Career interests.
- Skills and assessment results.
- Learning progress.
- Recommended resources.

### AI Integration – Gemini API
- Generates personalized career recommendations.
- Suggests relevant learning resources.
- Creates structured career roadmaps based on student goals.

## 3. System Workflow

1. Student enters profile details.
2. React frontend sends information to FastAPI.
3. Backend processes the information.
4. Skill gaps are identified.
5. Gemini API generates personalized recommendations.
6. PostgreSQL stores relevant student information and progress.
7. Backend sends results to the frontend.
8. Dashboard displays personalized recommendations.

## 4. Data Flow

Student Input  
↓  
React Frontend  
↓  
FastAPI Backend  
↓  
Skill Gap Analysis  
↓  
Gemini API + PostgreSQL  
↓  
Personalized Recommendations  
↓  
Student Dashboard

## 5. Deployment Plan

| Component | Platform |
|---|---|
| Frontend | Vercel |
| Backend | Render |
| Database | PostgreSQL hosting |
| AI Services | Gemini API |

## 6. Architecture Goal

Build a modular, scalable and user-friendly platform that connects career discovery, skill development and employment opportunities.
