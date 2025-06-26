# 💬 Real-Time Chat Application

A real-time chat app built with **React**, **Node.js**, **Express**, **Socket.IO**, and **MongoDB Atlas**. Users can join chat rooms and exchange messages instantly.

---

## Features

- Join chat rooms by name
- Real-time communication using WebSockets
- Displays list of active users in the room
- Clean UI with React
- MongoDB for storing data (optional, depending on setup)

---

## Tech Stack

- Frontend: React, HTML, CSS
- Backend: Node.js, Express
- Realtime: Socket.IO
- Database: MongoDB Atlas (Cloud)
- Deployment: Can be hosted on platforms like Heroku, Render, or Railway

---

## Project Structure

project_chat_application/
│
├── client/           # React Frontend
├── server/           # Node.js + Express Backend
├── .env.example      # Example environment config
├── .gitignore
├── README.md
└── ...

---

## How to Run Locally

### Prerequisites

- Node.js installed
- MongoDB Atlas cluster (free)
- Git installed

---

### 1. Clone the repository

git clone https://github.com/your-username/chat-app.git
cd chat-app

---

### 2. Set up environment variables

Create a `.env` file in the server directory and add:

PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key

---

### 3. Install dependencies

For backend:
cd server  
npm install

For frontend:
cd ../client  
npm install

---

### 4. Run the app

Start backend:
cd ../server  
npm start

Start frontend (in new terminal):
cd ../client  
npm start

Visit: http://localhost:3000

---

## Usage

1. Open the app in the browser
2. Enter your name and a room name
3. Share the same room name with a friend
4. Start chatting live 

##  License

This project is for learning and demo purposes. No license attached.

---

## Author

- **Faizan Khan**  
- GitHub: https://github.com/Faizan11khan

