# 🚀 Real-Time Chat & Notification System (VibeLine)

A scalable and production-ready **real-time messaging application** built using the **MERN stack**. The system enables seamless communication with instant message delivery, secure authentication, and efficient group management.

---

## 📌 Project Overview
VibeLine is a modern communication platform that supports **one-to-one and group chats** with real-time updates using Socket.io. It is designed with a **responsive UI, customizable themes, and efficient user interaction features**.  
The application demonstrates strong capabilities in building **real-time, scalable, and user-centric web applications with modern full-stack technologies**.

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Chakra UI  
- Socket.io Client  

### Backend
- Node.js  
- Express.js  
- Socket.io  

### Database
- MongoDB (Mongoose)  

---

## ✨ Features

### 🔐 Authentication & Security
- JWT-based authentication  
- Secure login and signup  
- Protected API routes  

### 💬 Real-Time Messaging
- Instant messaging using Socket.io  
- Typing indicators  
- Live message updates  

### 👥 Chat Management
- One-to-one chat  
- Group chat creation  
- Add/remove members  
- Rename groups  

### 🎨 User Experience
- Light/Dark theme toggle  
- Responsive design (mobile & desktop)  
- Clean and modern UI  

### 🧑‍💼 User Features
- Profile view and edit  
- Custom nicknames per chat  
- Logout functionality  

### 🔍 Smart Search
- Search users globally  
- Start chat instantly  
- Access existing conversations  

---

## ⚙️ System Architecture
- Event-driven communication using Socket.io  
- RESTful APIs built with Express.js  
- MongoDB for scalable data storage  
- JWT for secure authentication  
- Modular and maintainable project structure  

---

## 📂 Project Structure
backend/
  ├── controllers/
  ├── models/
  ├── routes/
  ├── config/
  └── server.js

frontend/
  ├── components/
  ├── pages/
  ├── context/
  └── App.js

screenshots/

---

## 🚀 Getting Started

### 1. Clone the Repository
git clone <your-repo-link>  
cd mern-chat-app  

### 2. Install Dependencies
# Backend  
npm install  

# Frontend  
cd frontend  
npm install  

### 3. Environment Variables
Create a `.env` file in the `backend/` folder:

MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key  
NODE_ENV=development  
PORT=5000  

### 4. Run the Application
# Terminal 1 - Backend  
npm run start  

# Terminal 2 - Frontend  
cd frontend  
npm start  

Frontend: http://localhost:3000  
Backend: http://127.0.0.1:5000  

---

## 🧠 Key Concepts
- Real-time bidirectional communication  
- JWT authentication  
- Event-driven architecture  
- Scalable chat system  
- React state management  

---

## 📈 Use Cases
- Team collaboration tools  
- Customer support chat systems  
- Social messaging platforms  
- Enterprise communication apps  