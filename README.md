# MERN Chat App 
A full-stack real-time chat application built using the **MERN stack** — MongoDB, Express, React, and Node.js — with real-time communication powered by **Socket.io**. It includes features like user authentication, one-on-one and group chats, live online status, and a responsive UI.

---
## Features

-  User Registration & Login (JWT Auth)
-  One-on-one and Group Messaging
-  Real-time Chat using Socket.io
-  Online User Indicators
---

##  Tech Stack
- **Frontend**: React, Chakra UI, Axios  
- **Backend**: Node.js, Express.js, MongoDB, Mongoose  
- **Real-Time**: Socket.io  
- **Authentication**: JWT (JSON Web Tokens)  
---

##  How to open
```bash
git clone https://github.com/your-username/mern-chat.git
cd mern-chat
```bash
npm install concurrently --save-dev       # If not already installed
npm run install-all                       # Install frontend + backend packages
```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```bash
npm run dev



