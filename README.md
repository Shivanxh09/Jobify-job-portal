# 🧑‍💼 Job Portal Full-Stack Application

A complete job portal web application built using the **MERN Stack**, enabling job seekers and recruiters to interact through a modern, responsive platform.

## 🏗️ Project Structure
root/ ├── frontend/ # React + Vite-frontend └── backend/ # Node.js + Express + MongoDB-backend
---

## 🚀 Features

### 👤 User Side
- Browse and apply for jobs
- Create/manage profiles
- Upload resumes
- Filter and search jobs

### 🧑‍💼 Admin/Recruiter Side
- Post and manage job listings
- View and manage applicants
- Company profile management

---

## 🛠️ Tech Stack

| Layer      | Technologies                            |
|------------|------------------------------------------|
| Frontend   | React, Vite, Tailwind CSS, Redux Toolkit |
| Backend    | Node.js, Express.js, MongoDB, Mongoose   |
| Auth       | JWT (JSON Web Tokens), Bcrypt            |
| Hosting    | GitHub (codebase), (Deployment TBD)      |

---


## ⚙️ Installation & Running Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### 2. Setup Backend
```bash
cd backend
npm install
```
Create a .env file in the backend folder and add:
<br>env</br>
<br>MONGO_URI=your_mongodb_connection_string</br>
<br>JWT_SECRET=your_jwt_secret</br>
<br>PORT=5000</br>


Then run the backend server:</br>

```bash

npm start
```
The backend will run on:
http://localhost:5000/

### 3. Setup Frontend
```bash

cd frontend
npm install
npm run dev
```

The frontend will start on:

http://localhost:5173/

Check the terminal output for the exact port. Open the URL in your browser to access the app.

### ✅ Final Notes
Ensure both frontend and backend are running for full functionality.

Frontend should be configured to make API calls to http://localhost:5000 (via .env or proxy).

Use tools like Postman to test backend APIs.


