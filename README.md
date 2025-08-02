# 📝 ThinkBoard — MERN Stack Note Taking App ✨


<p align="center">
  <a href="https://thinkboard-i2n1.onrender.com/" target="_blank"><b>🔗 Live Demo</b></a>
</p>



## 📋 Overview

ThinkBoard is a **Full-Stack Note Taking Application** built with the **MERN Stack (MongoDB, Express, React, Node.js)**. It allows users to **Create, Update, and Delete Notes** with a beautiful responsive UI.



## 🚀 Features

* 🯡 **Full-Stack MERN Architecture**
* ✨ **CRUD Functionality** for Notes (Title & Description)
* 🛡️ **Rate Limiting** using Upstash Redis for API Protection
* ⚙️ REST API built with Express & Mongoose
* 🌐 Fully Responsive Frontend with React & TailwindCSS
* 📝 Designed for **Absolute Beginners** to understand Full-Stack Concepts
* 📦 **Deployed on Render.com** (Backend & Frontend)



## 🧪 .env Configuration

Create a `.env` file inside `/backend` directory:

```bash
MONGO_URI=<your_mongo_db_uri>
UPSTASH_REDIS_REST_URL=<your_upstash_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_upstash_redis_rest_token>
NODE_ENV=development
```

---

## 🔧 Getting Started Locally

### Backend (Express API)

```bash
cd backend
npm install
npm run dev
```

### Frontend (React App)

```bash
cd frontend
npm install
npm run dev
```

### Build Frontend for Production

```bash
cd frontend
npm run build
```



