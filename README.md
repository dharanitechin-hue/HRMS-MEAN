# HRMS — MEAN Stack Mini Project

A complete local HRMS mini-project using **MongoDB + Express.js + Angular + Node.js**. The Express/Mongoose backend is the same working API used by the MERN version; the frontend has been rebuilt in Angular while keeping the same HRMS workflow and visual design.

## Features
- Admin and Employee login with JWT + bcrypt
- Role-protected Angular routes and server-side authorization
- Admin dashboard, employee CRUD, departments
- Attendance check-in/check-out
- Leave application and approval/rejection
- Payroll records
- Announcements
- Responsive SaaS-style sidebar, navbar, cards and tables
- Local MongoDB seed data

## Requirements
- Node.js + npm
- MongoDB Community Server running locally

## Backend setup
```powershell
cd backend
copy .env.example .env
npm install
npm run seed
npm run dev
```

Use this in `backend/.env`:
```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/hrms
JWT_SECRET=replace_with_your_long_random_secret
```

Backend: `http://localhost:5000`

## Frontend setup
Open a second terminal:
```powershell
cd frontend
npm install
npm start
```

Angular app: `http://localhost:4200`

## Demo accounts
Admin: `admin@hrms.com` / `admin123`

Employee: `employee1@hrms.com` / `employee123`

## Stack
Frontend: Angular, HTML5, CSS3, Angular Router, Angular HttpClient

Backend: Node.js, Express.js, REST API, JWT, bcrypt

Database: MongoDB, Mongoose

## Notes
- Keep the backend terminal and Angular terminal running at the same time.
- Do not commit `backend/.env`.
- This project is designed for learning, college demonstration, and portfolio use.
