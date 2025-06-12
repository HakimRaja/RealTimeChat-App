# Real-Time Chat Application 💬

A real-time chat app with notifications, built using the **MERN stack** and **Socket.IO**. This project demonstrates the application of **Parallel and Distributed Computing** principles, allowing real-time messaging, notifications, and concurrent user interactions.

> Developed by: **Hakim Mahfooz Raja**  

---

## 📂 Project Structure
├── frontend # React app for UI

├── backend # Node.js + Express REST API

└── socketio # WebSocket server using Socket.IO

## Getting Started

To run the full system, you must run all 3 services **simultaneously**.

### 1. Clone the repository
```bash
https://github.com/HakimRaja/RealTimeChat-App.git
cd RealTimeChat-App
```

### 2. Run the Frontend (React + Vite)
```bash
cd frontend
npm install
npm run dev
```
### 3. Run the Backend (Node + Express + MongoDB)
```bash
cd ../backend
npm install
npm run dev
```

### 4. Run the Socket.IO Server
```bash
cd ../socketio
npm install
npm run dev
```

### 🔐 Features

✅ User Authentication (JWT + bcrypt)

💬 Create chats and send messages

🧠 Real-time message delivery & notifications using Socket.IO

📡 RESTful API for users, chats, and messages

📦 Data persistence using MongoDB

🔄 Frontend-Backend-Socket run in parallel with real-time sync



