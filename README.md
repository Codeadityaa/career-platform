
# 🌟 AI Job Recommendation Platform

> **Live Frontend**: [https://ai-job-recommend-front-end.vercel.app/](https://ai-job-recommend-front-end.vercel.app/)  
> **Live Backend**: [https://ai-job-recommend-backend.onrender.com/](https://ai-job-recommend-backend.onrender.com/)

---

## 📄 About This Project

The **AI Job Recommendation Platform** helps users discover the best job opportunities tailored to their skills by analyzing their resume or search preferences.  
It is a full-stack web application built with **React**, **Node.js**, **MongoDB**, **Socket.IO**, and more modern technologies.

🔒 **Note:**  
This GitHub repository shows only the folder structure.  
If you want access to the **full project source code** (both frontend and backend),  
please **contact me directly** via:
- 📧 Email: sineraja97@gmail.com 

- 📱 LinkedIn: [your-linkedin-profile](https://www.linkedin.com/in/sine-raja-591156177/)

---

## 🚀 Core Functionalities

- Upload your resume and get **AI-powered job matches**.
- **Search and filter** jobs by title, location, category, experience, and salary.
- Real-time **chat functionality** for recruiters and applicants (via Socket.IO).
- Companies can **post jobs** and **manage applications**.
- **Beautiful responsive UI** built with Tailwind CSS.
- Fully **deployed** frontend (Vercel) and backend (Render).

---

## ⚙️ Tech Stack

| Frontend | Backend | Deployment | Database | Real-Time |
|:---|:---|:---|:---|:---|
| React.js | Node.js | Vercel (Frontend) | MongoDB Atlas | Socket.IO |
| Tailwind CSS | Express.js | Render (Backend) | Mongoose ODM | WebSockets |
| Axios | Cloudinary API (for uploads) |  |  |  |

---

## 📦 Project Structure

```
Frontend/
├── src/
│   ├── components/
│   ├── employeeComponent/
│   ├── JobSeeker/
│   ├── LandingPages/
│   ├── realtimeChat/
│   ├── animations/
│   ├── assets/
│   └── App.js
Backend/
├── jobControllers/
├── jobRoutes/
├── jobModel/
├── jobMiddleware/
├── configuration/
├── jobDatabase/
├── conversations/
├── utilities/
└── backendApp.js
```

---

## 🎯 Future Improvements (Coming Soon)

- AI Chatbot for career counseling.
- Admin dashboard for job analytics.
- More advanced resume parsing and skill extraction.

---

# 📢 Contact Me

If you are a recruiter, hiring manager, or developer and want to collaborate,  
or if you want access to the full source code, feel free to **reach out**:

- 📧 Email: sineraja97@gmail.com 

- 📱 LinkedIn: [your-linkedin-profile](https://www.linkedin.com/in/sine-raja-591156177/)

---

# ⭐ GitHub Topics/Tags

_(add these as explained before)_

```
AI · Job Recommendation · Resume Matching · Job Search · Career Platform · React · Node.js · MongoDB · Socket.IO · TailwindCSS · Vercel · Render
```

---


# 📦 Backend - `README.md`


# 🛠️ AI Job Recommend - Backend

[![Node.js](https://img.shields.io/badge/Node.js-Backend-green.svg)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-Framework-lightgrey.svg)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen.svg)](https://www.mongodb.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.io-RealTime-black.svg)](https://socket.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📜 Description

This is the **backend server** for the AI Job Recommend platform, responsible for handling:
- User authentication
- Job posting and searching
- Resume matching and analysis
- Real-time messaging (Socket.IO)

Built with **Express.js**, **MongoDB**, and **Socket.IO**.

---

## 🚀 Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.IO
- Cloudinary (for file uploads)
- Render.com (Backend hosting)
  
---

## ⚙️ Project Structure

```
configuration/
conversations/
jobControllers/
jobDatabase/
jobMiddleware/
jobModel/
jobRoutes/
node_modules/
utilities/
backendApp.js
server.js
socket.js
package.json
```

---

## 🌐 API Base URL

```bash
https://ai-job-recommend-backend.onrender.com/
```

Example:  
`GET /api/v1/job/all`

---

## 🛡️ Environment Variables (`.env`)

```bash
DATABASE_URI=your_mongodb_uri
FRONTEND_URL=https://ai-job-recommend-front-end.vercel.app/
CLOUDINARY_NAME=your_cloudinary_name
COOKIE_LIFETIME=your_cookie_lifetime
```

---

## 🧠 Run Locally

```bash
npm install
npm run dev
```

Server runs at `http://localhost:8000` (or your set PORT).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).



# 🌟 Frontend - `README.md`

# 🎯 AI Job Recommend - Frontend

[![React](https://img.shields.io/badge/React-Frontend-blue.svg)](https://reactjs.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Styling-38bdf8.svg)](https://tailwindcss.com/)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Hosting-black.svg)](https://vercel.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📜 Description

This is the **frontend client** for the AI Job Recommend platform, built using **ReactJS** and **TailwindCSS**.

It allows users to:
- Search and apply for jobs
- Upload resumes for AI-based job recommendations
- View matched jobs
- Real-time chat with companies

---

## 🚀 Tech Stack

- ReactJS
- Tailwind CSS
- Axios
- Framer Motion
- React Icons
- React Toastify

---

## 📂 Project Structure

```
public/
src/
 ├── animations/
 ├── assets/
 ├── components/
 ├── employeeComponent/
 ├── JobSeeker/
 ├── LandingPages/
 ├── realtimeChat/
.env
.gitignore
package.json
tailwind.config.js
```

---

## 🌐 Live URL

> [**Live Demo**](https://ai-job-recommend-front-end.vercel.app/)

---

## ⚙️ Environment Variables (`.env`)

```bash
REACT_APP_BACKEND_URL=https://ai-job-recommend-backend.onrender.com/
```

---

## 🧠 Run Locally

```bash
npm install
npm start
```

Frontend will start on `http://localhost:3000`.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

