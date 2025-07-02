# 💬 Cross-Platform Chat Application (Flutter + Node.js + MongoDB)

This project is a real-time chat room application built as part of **Technical Task #1738** for the **Full Stack Developer Role** at Arishti CyberTech.

---

## 🚀 Tech Stack

Live API URL
```https://chat-app-backend-hxs7.onrender.com```

### 💻 Backend
- Node.js
- Express.js
- MongoDB (via Mongoose)
- Socket.io
- JWT (Authentication)
- CORS, Bcrypt

### 📱 Frontend
- Flutter
- Riverpod (State Management)
- Hive (Local message storage)
- socket_io_client
- http package (API calls)

---

## ✅ Features Implemented

1. **Real-Time Messaging**
   - Multiple users can join a chat room and exchange messages instantly using **Socket.io**.
   - Room-based message broadcasting handled via the backend.

2. **User Authentication**
   - Secure registration & login using **JWT tokens**.
   - Only authenticated users can join chat rooms.

3. **Message Persistence**
   - Messages are stored in **MongoDB** and also cached locally in **Hive** on the device.

4. **Offline Storage with Hive**
   - Messages are saved locally to avoid reloading the same data.
   - On app launch, local chat history is loaded instantly.

5. **Message History Fetch**
   - When a user joins a chat room, recent messages from MongoDB are fetched and synced to local Hive DB.

6. **State Management with Riverpod**
   - Token and authentication logic managed via `flutter_riverpod` for cleaner and scalable state handling.

7. **REST API Testing**
   - All backend APIs tested and documented using **Postman**.

---

## ⚙️ Setup Instructions

### Backend

1. Clone the repo:
   ```bash
   git clone https://github.com/JayeshPatil18/chat-app/chat-app-backend.git
   cd chat-app-backend

   
2. Install dependencies:
   ```bash
   npm install

   
3. Start the server:
   ```bash
   node server.js

