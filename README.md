# mern-authentication
A fully featured, production-ready authentication system built using the MERN Stack. This project includes modern security practices like JWT, Refresh Tokens, 2FA, CSRF protection, rate limiting, and role-based access control.


# Tech Stack
Frontend: React, Axios
Backend: Node.js, Express, MongoDB
Security: JWT, Bcrypt, CSRF tokens, OTP


# MERN-AUTH
 ├── backend      # Node.js + Express + MongoDB
 └── frontend     # React


# Features

1. User Registration & Login
2. Password Hashing (bcrypt)
3. JWT Access & Refresh Tokens
4. Auto Token Refresh Middleware
5. Protected Backend & Frontend Routes
6. Role-Based Authorization (Admin/User)
7. Two-Factor Authentication (OTP)
8. CSRF Protection
9. Rate Limiting (Brute-force protection)
10. Secure Cookies (httpOnly, secure)
11. Input Sanitization (NoSQL Injection Protection)
12. Modern, clean authentication UI


# Running the Project

Clone the repo.
Create environment variables.
Install dependencies.
Start backend & frontend separately.

backend :-
cd backend
npm install
npm run dev

frontend :-
cd frontend
npm install
npm run dev