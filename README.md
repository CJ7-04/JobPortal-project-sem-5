# JobPortal

A full-stack **Job Portal** application where job seekers can browse and apply for jobs, and recruiters can post and manage job listings.  
This project is built using modern web technologies with a clean, responsive UI and a robust backend API.

---

## 🚀 Features

- **User Authentication & Authorization**
  - Signup & Login for Job Seekers and Recruiters
  - Role-based access control
- **Job Management**
  - Recruiters can post, update, and delete jobs
  - Job seekers can browse and search jobs
- **Application Management**
  - Job seekers can apply for jobs
  - Recruiters can review and manage applications
- **Responsive UI**
  - Mobile-friendly design using Bootstrap
- **REST API Integration**
  - Backend API tested and documented with Postman

---

## 🛠 Tech Stack

### **Frontend**
- [React.js](https://reactjs.org/) – Component-based UI
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) – Core logic
- [Bootstrap](https://getbootstrap.com/) – Styling and responsiveness

### **Backend**
- [Node.js](https://nodejs.org/) – Runtime environment
- [Express.js](https://expressjs.com/) – Web framework
- [MongoDB](https://www.mongodb.com/) – NoSQL database

### **API Testing**
- [Postman](https://www.postman.com/) – API development & testing

---

## 📂 Folder Structure

```bash
JobPortal/
│
├── client/           # React frontend
├── server/           # Node.js + Express backend
│   ├── models/       # MongoDB schemas
│   ├── routes/       # API endpoints
│   ├── controllers/  # Business logic
│   └── config/       # Database & environment configs
├── README.md
└── package.json
