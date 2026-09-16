# InternFlow — Intern Progress Tracking Portal

A full-stack starter application with React/Vite frontend and Node/Express/MongoDB backend.

## Features
- Multiple admin accounts
- Admin-created intern onboarding
- Task creation, assignment, deadlines, and deletion
- Pending → In Progress → Completed statuses
- Intern work submission with notes, GitHub link, and file upload
- Admin feedback
- Responsive professional dashboard

## Run locally

### 1. Backend
```bash
cd server
cp .env.example .env
npm install
npm run dev
```
Set `MONGO_URI` and a strong `JWT_SECRET` in `.env`.

### 2. Frontend (new terminal)
```bash
cd client
npm install
npm run dev
```
Open the Vite URL shown in the terminal, usually http://localhost:5173.

The first account created through the sign-up screen is an admin. Admins can then onboard interns.
