
# 📊 Weight Tracker App

A simple and clean full-stack application that allows users to record and track their weight over time.
Built using **React (Vite)** on the frontend and **Node.js + Express + MongoDB** on the backend.

---

## 🚀 Features

### **Frontend**

* Add new weight entries
* Display weight history
* Clean, responsive UI
* Fast Vite + React development setup

### **Backend**

* REST API built with Express.js
* MongoDB database using Mongoose
* Handles saving and retrieving weight data

---

## 🧱 Tech Stack

**Frontend**

* React (JSX)
* Vite
* CSS

**Backend**

* Node.js
* Express.js
* MongoDB (Mongoose)

---

## 📂 Project Structure

WEIGHTTRACKER
│
├── backend
│   ├── models
│   ├── node_modules
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
├── frontend
│   ├── components
│   ├── node_modules
│   ├── public
│   ├── src
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── eslint.config.js
│   └── vite.config.js
│
└── README.md




---

## ▶️ Running the Project

### **1. Run the backend** 

```
cd backend
npm install
node server.js
```

Backend runs on **[http://localhost:5000](http://localhost:5000)**

### **2. Run the frontend**

Open another terminal:

```
cd frontend
npm install
npm run dev
```

Frontend runs on **[http://localhost:5173](http://localhost:5173)**

---

## 🔌 Connecting Frontend to Backend

Update API URLs in frontend as:

```js
fetch("http://localhost:5000/api/weights")
```

---

## 📈 Future Improvements

* Add weight goal tracking
* Add charts and graphs
* Add user login
* Deploy frontend + backend online

---

