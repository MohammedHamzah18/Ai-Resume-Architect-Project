# AI Resume Architect

A MERN stack resume builder that helps candidates create structured resumes, score them for ATS readiness, generate stronger bullet points, and tailor content to a target role.

## Features

- JWT authentication with protected resume APIs
- Resume CRUD with MongoDB via Mongoose
- AI-style resume analysis engine with ATS score, keyword gaps, strengths, risks, rewritten summary, and bullet recommendations
- Responsive React dashboard, editor, and live resume preview
- Print-ready resume export from the browser
- Production-focused project structure with environment configuration

## Tech Stack

- MongoDB + Mongoose
- Express + Node.js
- React + Vite
- JWT + bcrypt

## Getting Started

```bash
npm run install:all
copy server\.env.example server\.env
npm run dev
```

By default, the API runs on `http://localhost:5000` and the client runs on `http://localhost:5173`.

Set `MONGO_URI` in `server/.env` for persistent storage. If no MongoDB URI is available, the API runs in an in-memory demo mode so the app can still be evaluated locally.
