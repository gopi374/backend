# 🌐 Portfolio Web Application (Full-Stack)

A **full-stack Portfolio Web Application** built to showcase my skills, projects, and experience.  
This project demonstrates the complete workflow of **frontend + backend + database integration** using modern web technologies.

---

## 📌 Project Overview

This portfolio web app is designed to present my personal profile, projects, and information in a clean and responsive interface, backed by a powerful server and database.

The project follows a **separation of concerns** approach:
- **Frontend** handles UI/UX
- **Backend** manages APIs and data
- **Database** stores application data securely

---

## 🛠️ Tech Stack

### 🎨 Frontend
- **HTML5** – Structure
- **CSS3** – Styling & Layout
- **JavaScript (ES6)** – Interactivity
- Responsive Design principles

👉 *Frontend is deployed using **Netlify***  

---

### ⚙️ Backend
- **Node.js** – Runtime environment
- **Express.js** – Server framework
- **RESTful APIs** – Client-server communication

👉 *Backend is deployed using **Render***  

---

### 🗄️ Database
- **MongoDB Atlas** – Cloud NoSQL database
- **Mongoose** – ODM for MongoDB

---

## ✨ Features

- Fully responsive portfolio website
- REST API built with Express.js
- MongoDB Atlas cloud database integration
- Environment variable configuration for security
- Ready-to-connect frontend and backend
- Scalable backend structure
- Clean and beginner-friendly codebase

---
backend/
│── server.js # Main server file
│── package.json # Project metadata & dependencies
│── package-lock.json # Dependency lock file
│── .env # Environment variables (ignored)
│── .gitignore # Git ignored files


---

## 🔐 Environment Variables

Create a `.env` file in the root of the backend folder:

```env
PORT=3000
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/DB

🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/gopi374/backend.git

2️⃣ Navigate to Project Folder
cd backend

3️⃣ Install Dependencies
npm install

4️⃣ Start the Server
npm start

✅ Successful Run Output

When everything is configured correctly, you will see:

Server is running on port 3000
MongoDB connected successfully

🌍 Deployment Details
Service	Platform
Frontend	Netlify
Backend	Render
Database	MongoDB Atlas
🔗 API Connectivity

The frontend communicates with the backend using HTTP requests (Fetch API).
The backend processes requests, interacts with MongoDB, and returns JSON responses.

🧠 Learning Outcomes

Through this project, I learned:

Building REST APIs with Express.js

Connecting MongoDB Atlas to Node.js

Using environment variables securely

Deploying full-stack applications

Debugging real-world backend issues

Git & GitHub workflow

📈 Future Enhancements

Add authentication (Login / Signup)

Admin panel to manage content

Form submission with database storage

Email integration

Frontend framework (React.js)

API documentation with Swagger

👤 Author

Gopi Banjara

GitHub: https://github.com/gopi374

Portfolio: https://backend-p1.netlify.app/

📄 License

This project is open-source and intended for learning, practice, and personal portfolio use.

⭐ If you found this project useful, feel free to star the repository!



## 📁 Project Structure (Backend)

