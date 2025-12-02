# Linkedin Clone

A LinkedIn clone built with **React** (frontend) and **Node.js/Express** (backend), deployed on Render.

## Live Demo
[Frontend](https://linkedin-frontend-kfyc.onrender.com)

## Features
- User Authentication (Sign Up, Login, Logout)
- Profile Creation & Update (Skills, Education, Experience)
- Create, View, and Like Posts
- Network Connections
- Real-time Notifications using Socket.io
- Search and Suggested Users

## Tech Stack
- **Frontend:** React, React Router, Axios, Zustand, Vite
- **Backend:** Node.js, Express, MongoDB, Mongoose, Socket.io
- **Authentication:** JWT in HttpOnly Cookies
- **Deployment:** Render

## Folder Structure
Linkedin/
├─ backend/
│ ├─ config/
│ ├─ controllers/
│ ├─ models/
│ ├─ routes/
│ └─ server.js
├─ frontend/
│ ├─ src/
│ │ ├─ components/
│ │ ├─ context/
│ │ ├─ pages/
│ │ └─ main.jsx
│ └─ index.html
└─ README.md

bash
Copy code

## Installation
1. Clone the repo:
```bash
git clone https://github.com/KunalVishwakarma55/Linkedin.git
Backend setup:

bash
Copy code
cd Linkedin/backend
npm install
Frontend setup:

bash
Copy code
cd ../frontend
npm install
Create .env files for backend & frontend.

Run backend:

bash
Copy code
npm run dev
Run frontend:

bash
Copy code
npm run dev
