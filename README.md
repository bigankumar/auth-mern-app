# 🔐 MERN Authentication App

A full-stack **MERN (MongoDB, Express, React, Node.js)** authentication system that allows users to **sign up and log in securely**.
The backend uses **Node.js, Express, MongoDB Atlas**, and **bcrypt** for password hashing.

---

## 🚀 Features

* User Signup API
* User Login API
* Password hashing using **bcrypt**
* Request validation using **Joi**
* MongoDB Atlas cloud database
* Express.js REST API
* Clean MERN folder structure

---

## 🛠 Tech Stack

**Frontend**

* React.js
* CSS

**Backend**

* Node.js
* Express.js
* MongoDB
* Mongoose

**Security & Validation**

* bcrypt
* Joi

---

## 📁 Project Structure

auth-mern-app
│
├── backend
│   ├── Controllers
│   │   └── AuthController.js
│   ├── Middlewares
│   │   └── AuthValidation.js
│   ├── Models
│   │   ├── db.js
│   │   └── user.js
│   ├── Routes
│   │   └── AuthRouter.js
│   ├── index.js
│   └── package.json
│
└── frontend
├── src
├── public
└── package.json

---

## ⚙️ Installation

### 1️⃣ Clone the repository

git clone https://github.com/bigankumar/auth-mern-app.git

---

### 2️⃣ Go to project folder

cd auth-mern-app

---

### 3️⃣ Install backend dependencies

cd backend
npm install

---

### 4️⃣ Start backend server

npm start

Server will run on:

http://localhost:8080

---

## 🔑 Environment Variables

Create a `.env` file inside **backend** folder.

PORT=8080
MONGO_CONN=your_mongodb_connection_string

---

## 📡 API Endpoints

### Signup

POST /auth/signup

Example Request Body

{
"name": "Bigan",
"email": "[bigan@example.com](mailto:bigan@example.com)",
"password": "123456"
}

---

### Login

POST /auth/login

Example Request Body

{
"email": "[bigan@example.com](mailto:bigan@example.com)",
"password": "123456"
}

---

## 🧪 Testing API

You can test the APIs using:

* Postman
* Thunder Client
* Insomnia

---

## 📌 Future Improvements

* JWT Authentication
* Protected Routes
* Refresh Tokens
* Frontend Login & Signup UI
* Deploy MERN app online

---

## 👨‍💻 Author

**Bigan Kumar**

GitHub:
https://github.com/bigankumar

---

⭐ If you like this project, consider giving it a star on GitHub.
