# EtharaChats 💬

EtharaChats is a real-time full-stack group chat web application built using HTML, CSS, JavaScript, Node.js, HTTP Server, and Socket.IO.

The application allows users to join a shared chat room by entering their identity details such as name and gender. Users can send and receive messages instantly in real time while also viewing currently online users.

---

# ✨ Features

## Frontend Features
- Responsive modern UI
- Orange + Pink + Black theme
- Landing page
- Join chat popup modal
- Real-time messaging
- Online users sidebar
- Gender badges
- Typing indicator
- Timestamps on messages
- Smooth auto-scroll
- Mobile responsive design

---

## Backend Features
- Real-time communication using Socket.IO
- User join/leave notifications
- Online users tracking
- Typing events
- Error handling
- Lightweight backend
- No database required
- No authentication complexity

---

# 🛠️ Tech Stack

## Frontend
- HTML5
- CSS3
- Vanilla JavaScript

## Backend
- Node.js
- HTTP Server
- Socket.IO

---

# 📁 Project Structure

```bash
EtharaChats/
│
├── server/
│   ├── server.js
│   ├── users.js
│   └── package.json
│
└── client/
    ├── index.html
    ├── style.css
    └── app.js
```

---

# ⚙️ Installation & Setup

## 1. Install Node.js

Download and install Node.js:

https://nodejs.org

Verify installation:

```bash
node -v
npm -v
```

---

## 2. Clone or Create Project

```bash
mkdir EtharaChats
cd EtharaChats
```

Create folders:

```bash
mkdir server
mkdir client
```

---

# 🚀 Backend Setup

Move into server directory:

```bash
cd server
```

Initialize npm:

```bash
npm init -y
```

Install Socket.IO:

```bash
npm install socket.io
```

---

# ▶️ Run Backend Server

Inside `server` folder:

```bash
node server.js
```

Server will start at:

```bash
http://localhost:3000
```

---

# 🌐 Run Frontend

Open:

```bash
client/index.html
```

in your browser.

You can also use VS Code Live Server extension.

---

# 🔌 Socket Events

## Client → Server

| Event Name | Description |
|------------|-------------|
| join-chat | User joins chat |
| send-message | Sends a message |
| typing | Typing indicator |

---

## Server → Client

| Event Name | Description |
|------------|-------------|
| receive-message | Receives new message |
| online-users | Updated online users |
| system-message | Join/leave notifications |
| typing | User typing status |
| error-message | Error handling |

---

# 📱 Responsive Design

The UI is fully responsive and works on:
- Desktop
- Tablet
- Mobile devices

---

# 🎨 Theme Colors

| Color | Usage |
|------|------|
| Orange | Primary highlights |
| Pink | Accent highlights |
| Black | Main background |

---

# 🧠 How It Works

1. User opens EtharaChats
2. User clicks "Join Chat"
3. User enters:
   - Name
   - Gender
4. User joins shared real-time chat room
5. Messages are broadcast instantly using Socket.IO
6. Online users list updates automatically

---

# ⚠️ Error Handling

The app handles:
- Empty messages
- Invalid user details
- Duplicate sessions
- Socket disconnections
- Failed events

---

# 🚀 Deployment

## Backend Hosting
You can deploy backend on:
- Railway
- Render
- Fly.io

## Frontend Hosting
You can deploy frontend on:
- Vercel
- Netlify
- GitHub Pages

---

# 🔧 Production Configuration

Update this line in `client/app.js`:

```javascript
const socket = io("http://localhost:3000");
```

Replace with your deployed backend URL:

```javascript
const socket = io("https://your-backend-url.com");
```

---

# 🔮 Future Improvements

- Private chat
- Multiple rooms
- Emojis
- Image sharing
- Voice chat
- Database integration
- Message persistence
- Admin moderation
- User avatars
- Push notifications

---

# 👨‍💻 Author

Developed for the EtharaChats real-time communication project.

---

# 📄 License

This project is open-source and free to use.
