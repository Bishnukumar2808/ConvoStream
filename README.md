# 💬 Chat App

A real-time **Chat Application** built with the **MERN stack** and **Socket.IO**, featuring user authentication, private chats, and group messaging.

---

## 🚀 Features
- 🔐 **Authentication & Authorization** (JWT-based)
- 👥 **One-to-One and Group Chats**
- 🟢 **Real-time Messaging** with Socket.IO
- 🖼 **Profile Picture & User Info**
- 📝 **Update Group (Rename, Add/Remove Members)**
- 🌙 **Responsive UI with Dark Mode**
- ⚡ **Optimized for Performance**

---

## 🛠 Tech Stack
- **Frontend**: React.js (Vite), Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Atlas)  
- **Authentication**: JWT  
- **Real-time**: Socket.IO  

---

## 📂 Project Structure
backend/
│── config/ # Database connection, environment config
│── controllers/ # Business logic for users, chats, messages
│── middleware/ # Auth middleware (JWT verification)
│── models/ # MongoDB models (User, Chat, Message)
│── routes/ # Express routes (auth, chat, message APIs)
│── server.js # Entry point
│── .env # Environment variables

frontend/
│── public/ # Static files
│── src/
│ ├── components/ # Reusable UI components (ChatBox, SingleChat, etc.)
│ ├── config/ # Config (axios instance)
│ ├── Context/ # React context (chat state, auth state)
│ ├── Pages/ # Pages (Homepage, ChatPage)
│ ├── App.jsx # Root component
│ ├── main.jsx # Vite entry point
│ ├── index.css # Global styles
│ ├── App.css # App-specific styles
│── .env # Frontend environment variables



---

## 🔑 Environment Variables

### Backend (`/backend/.env`)

PORT=5000
MONGO_URI=mongodb+srv://srijanswapnil:srijanswapnil@cluster0.kd25r.mongodb.net/chat-app?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=hello
NODE_ENV=production
FRONTEND_URL=https://localhost:5173

##Frontend (/frontend/.env)
VITE_API_BASE_URL=http://localhost:5000

⚙️ Installation
1. Clone the repository
git clone https://github.com/srijanswapnil/chat-app.git
cd chat-app

2. Install dependencies
Backend
cd backend
npm install

Frontend
cd ../frontend
npm install

▶️ Running the App
Start Backend
cd backend
npm start

Start Frontend
cd frontend
npm run dev
