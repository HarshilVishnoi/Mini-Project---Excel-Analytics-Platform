# 📊 Excel Graph - Data Visualization & Analysis Tool

![MERN Stack](https://img.shields.io/badge/MERN-FullStack-green)
![JWT Auth](https://img.shields.io/badge/Secure-JWT_Authentication-blue)
![Live](https://img.shields.io/badge/Live-Online-brightgreen)

**Excel Graph** is a powerful data visualization platform that transforms your spreadsheet data into interactive graphs and charts. Built with the MERN stack, it offers secure user authentication and real-time data rendering capabilities.

---

## 🌐 Live Demo

- 🔗 **Frontend**: [https://exelencefrontend.onrender.com](https://exelencefrontend.onrender.com)
- 🔗 **Backend**: [https://exelencebackend.onrender.com](https://exelencebackend.onrender.com)

---

## ✨ Key Features

📈 **Dynamic Graph Generation**  
- Upload Excel/CSV files  
- Multiple chart types (Line, Bar, Pie)  
- Customizable axes and labels  

🔒 **Secure Authentication**  
- JWT protected routes  
- Google OAuth integration  
- Session management  

⚡ **Real-time Updates**  
- Instant visualization changes  
- Collaborative editing support  
- History tracking  

---

## 🛠️ Tech Stack

### Frontend
- React.js + Vite
- Chart.js (Data Visualization)
- Tailwind CSS (Styling)
- Axios (HTTP Client)

### Backend
- Node.js + Express
- MongoDB (Database)
- Mongoose (ODM)
- Passport.js (Authentication)
- JWT (Session Management)

### Deployment
- Render (Hosting)
- MongoDB Atlas (Cloud Database)

---

## 🚀 Installation Guide

### Prerequisites
- Node.js (v18+)
- MongoDB (Local or Atlas URI)
- Google OAuth Credentials

### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/excel-graph.git
cd excel-graph
```

# Backend Setup
```
cd server
npm install
cp .env.example .env
# Fill in your environment variables
npx nodemon server.js
```

# Frontend Setup (in new terminal)
```
cd client
npm install
npm run dev


```
