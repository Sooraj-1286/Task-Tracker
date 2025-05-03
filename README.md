# 📋 Task-Tracker

A full-stack **Task Management System** built with **ReactJS**, **ExpressJS**, and **MongoDB/PostgreSQL**, featuring secure **JWT authentication** and efficient **project/task tracking**. Users can manage up to 4 projects, with complete CRUD support for tasks.

---

## 🚀 Features

- 🔐 User Authentication (JWT)
- 🧑‍💼 Multiple users support
- 🗂️ Each user can manage up to **4 projects**
- ✅ Create, Read, Update, Delete (CRUD) for tasks
- 📅 Task status tracking, creation, and completion dates
- 🌍 User metadata: name, country, email
- 🧾 RESTful API design

---

## 🛠️ Tech Stack

| Frontend        | Backend         | Database        | Auth       |
|-----------------|------------------|------------------|------------|
| ReactJS         | NodeJS + Express | MongoDB / PostgreSQL | JWT + bcrypt |

---

## 📦 Folder Structure
├── client/ # React app
├── server/ # Express server
└── README.md

## 🧑‍💻 Installation & Running Locally

### 🖥️ Prerequisites

- Node.js (v16+)
- MongoDB or PostgreSQL installed (or use MongoDB Atlas / Railway / Supabase)
- Git

---

### 📁 Backend Setup

```bash
cd backend
npm install
Create a .env file (you can copy from .env.example):

ini
Copy
Edit
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run the server:

bash
Copy
Edit
npm run dev
🌐 Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
The app will run on http://localhost:3000

🧪 Test Credentials (Optional)
You can use the following credentials to log in for demo purposes:

txt
Copy
Edit
Email: demo@example.com
Password: demo123
🔄 API Endpoints Overview
Auth
POST /api/auth/signup![Screenshot 2025-05-04 000155](https://github.com/user-attachments/assets/9a22730e-12a2-408b-9506-07994d160ad3)


POST /api/auth/login![Screenshot 2025-05-04 000155 - Copy](https://github.com/user-attachments/assets/6817a33d-21bb-4766-971b-eb43790a1e12)


Projects
POST /api/projects

GET /api/projects

DELETE /api/projects/:id
![Screenshot 2025-05-04 000231](https://github.com/user-attachments/assets/95e598b2-e465-45b8-a31f-7c62419b5e3b)
![Screenshot 2025-05-04 000505](https://github.com/user-attachments/assets/3c7d9b75-adc6-4b7e-851a-ae1f4081c9dc)

Tasks
POST /api/tasks
![Screenshot 2025-05-04 000839](https://github.com/user-attachments/assets/83258436-7720-4d11-a88f-2cfe4cec0d0b)
![Screenshot 2025-05-04 000851](https://github.com/user-attachments/assets/1cb60db2-e4c8-4200-a22e-2ec5b0e9974b)

GET /api/tasks/:projectI![Screenshot 2025-05-04 000905](https://github.com/user-attachments/assets/9960fa8c-2dbd-428f-ab47-6e2ceb5e362b)
d

PUT /api/tasks/:taskId

DELETE /api/tasks/:taskId

![Screenshot 2025-05-04 000921](https://github.com/user-attachments/assets/00e25a1b-9472-4b5a-9d66-7412ee093c9c)


