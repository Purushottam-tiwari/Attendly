# Attendly - Smart Attendance Management System

## 🚀 Live Demo

**Website:** https://attendly-alpha.vercel.app/

## 📌 Overview

Attendly is a full-stack attendance management platform designed to simplify attendance tracking for educational institutions. It provides a seamless experience for students and administrators to manage attendance records, monitor attendance percentages, and access attendance-related information in real time.

The system helps students stay informed about their attendance status while enabling efficient attendance management through a modern and responsive web interface.

---

## ✨ Features

### Student Features

* Secure authentication and authorization
* View attendance percentage
* Track attendance history
* Monitor subject-wise attendance
* Responsive dashboard
* Real-time attendance updates

### Admin Features

* Student management
* Attendance management
* Dashboard analytics
* Attendance reporting
* User authentication and access control

### General Features

* Modern responsive UI
* JWT-based authentication
* Protected routes
* Real-time data handling
* Cloud deployment

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* React Router DOM

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Authentication

* JSON Web Tokens (JWT)

### Deployment

* Vercel (Frontend)
* Cloud Database (MongoDB Atlas)

---

## 📂 Project Structure

```bash
Attendly/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── package.json
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Purushottam-tiwari/Attendly.git
cd Attendly
```

### Install Dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd server
npm install
```

### Environment Variables

Create a `.env` file inside the server directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Run Application

Backend

```bash
npm run dev
```

Frontend

```bash
npm start
```

---

## 🔒 Security Features

* Password encryption
* JWT authentication
* Protected API routes
* Environment variable protection

---

## 🎯 Future Enhancements

* QR Code Attendance
* Face Recognition Attendance
* Attendance Notifications
* Excel/PDF Report Export
* Role-Based Access Control
* Mobile Application Support

---

## 👨‍💻 Author

**Purushottam Kumar Tiwari**

* GitHub: https://github.com/Purushottam-tiwari
* LinkedIn: [www.linkedin.com/in/purushottam-tiwari-4335a5268](http://www.linkedin.com/in/purushottam-tiwari-4335a5268)

---

## 📜 License

This project is licensed under the MIT License.

⭐ If you found this project useful, please give it a star on GitHub.
