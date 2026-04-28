# 🚀 DevCollabX

🔗 Live Demo: https://devcollabx-client.onrender.com/
📦 Client Repo: https://github.com/KrGuddu/devcollabx-client  
📦 Server Repo: https://github.com/KrGuddu/devcollabx-server  

---

## 📌 About the Project

**DevCollabX** is a real-time collaborative code editor where developers can join or create rooms using a unique Room ID and code together instantly.

It enables multiple users to:
- Join a shared coding room
- Write and edit code simultaneously
- See live updates in real time
- Collaborate without needing authentication or login

The system is powered by WebSockets (Socket.IO) for instant communication between connected clients.

---

## ✨ Features

- 🧑‍💻 Real-time collaborative coding environment  
- 🔗 Join or create rooms using unique Room ID  
- ⚡ Live code synchronization using WebSockets (Socket.IO)  
- 🧠 Monaco Editor for powerful in-browser code editing  
- 👥 Multiple users can join the same session  
- 📡 Instant updates across all connected clients  
- 🚀 Lightweight and fast collaboration system  

---

## 🛠️ Tech Stack

### Frontend
```bash
- React.js  
- Socket.IO Client  
- UUID (for generating Room IDs)  
- CSS / Tailwind  
```

### Backend
```bash
- Node.js  
- Express.js  
- Socket.IO (WebSocket communication)  
- UUID (Room management)  
- CORS  
```

### Utilities
```bash
- UUID for unique room generation  
- WebSockets for real-time sync  
```
---

## 📁 Project Structure
```bash
DevCollabX
│
├── devcollabx-client # Frontend (React)
│ ├── src
│ ├── components
│ ├── pages
│ └── ...
│
└── devcollabx-server # Backend (Node/Express)
├── models
├── routes
├── controllers
└── ...
```


---

## ⚙️ Installation & Setup

### 1. Clone Repositories

```bash
git clone https://github.com/KrGuddu/devcollabx-client.git
git clone https://github.com/KrGuddu/devcollabx-server.git

```
### 2. Backend Setup

```bash
cd devcollabx-server
npm install
```

Create .env file:
```bash
PORT=4000
```

Run server:
```bash
npm start
```
### 3. Frontend Setup
```bash
cd devcollabx-client
npm install
npm run dev
```

Build for production:
```bash
npm run build
```
### 🌐 Deployment
```bash
Frontend: Render
Backend: Render
```

---
## 🚀 Future Improvements
- 🧑‍💻 Real-time code editor enhancements
- 💬 Chat system for collaborators
- 📌 Kanban board for task tracking
- 📂 File sharing system
- 🔔 Notifications system
- 🤖 AI-assisted coding suggestions
---

## 🤝 Contributing
Contributions are welcome!
```bash
1. Fork the repository
2. Create your feature branch (git checkout -b feature-name)
3. Commit your changes (git commit -m "Add feature")
4. Push to branch (git push origin feature-name)
5. Open a Pull Request
```

---
## 👨‍💻 Author
**Mr. Guddu Kumar**  
Frontend / React Developer

🌐 Portfolio: https://krguddu.netlify.app

🐙 GitHub: https://github.com/KrGuddu