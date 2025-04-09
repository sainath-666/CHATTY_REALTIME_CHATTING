# Chatty 💬

A modern full-stack real-time chat application built with the MERN stack and Socket.io.

## ✨ Features

- **Real-time messaging** powered by Socket.io
- **User authentication** with JWT
- **Online status indicators** for active users
- **Image sharing** via Cloudinary integration
- **Responsive design** for all devices
- **Dark/Light mode** toggle
- **Message notifications**
- **Clean, modern UI** built with TailwindCSS and Daisy UI

## 🚀 Tech Stack

**Frontend:**

- React + Vite
- TailwindCSS + Daisy UI
- Zustand for state management
- Socket.io client

**Backend:**

- Node.js + Express
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- Cloudinary

## 📁 Project Structure

```
fullstack-chat-app/
├─ backend/
│  ├─ src/
│  │  ├─ controllers/
│  │  │  ├─ auth.controller.js
│  │  │  └─ message.controller.js
│  │  ├─ lib/
│  │  │  ├─ cloudinary.js
│  │  │  ├─ db.js
│  │  │  ├─ socket.js
│  │  │  └─ utils.js
│  │  ├─ middleware/
│  │  │  └─ auth.middleware.js
│  │  ├─ models/
│  │  │  ├─ message.model.js
│  │  │  └─ user.model.js
│  │  ├─ routes/
│  │  │  ├─ auth.route.js
│  │  │  └─ message.route.js
│  │  ├─ seeds/
│  │  │  └─ user.seed.js
│  │  └─ index.js
├─ frontend/
│  ├─ public/
│  │  ├─ avatar.png
│  │  ├─ chat.png
│  │  └─ vite.svg
│  ├─ src/
│  │  ├─ components/
│  │  │  ├─ skeletons/
│  │  │  │  ├─ MessageSkeleton.jsx
│  │  │  │  └─ SidebarSkeleton.jsx
│  │  │  ├─ AuthImagePattern.jsx
│  │  │  ├─ ChatContainer.jsx
│  │  │  ├─ ChatHeader.jsx
│  │  │  ├─ MessageInput.jsx
│  │  │  ├─ Navbar.jsx
│  │  │  ├─ NoChatSelected.jsx
│  │  │  └─ Sidebar.jsx
│  │  ├─ constants/
│  │  │  └─ index.js
│  │  ├─ lib/
│  │  │  ├─ axios.js
│  │  │  └─ utils.js
│  │  ├─ pages/
│  │  │  ├─ HomePage.jsx
│  │  │  ├─ LoginPage.jsx
│  │  │  ├─ ProfilePage.jsx
│  │  │  ├─ SettingsPage.jsx
│  │  │  └─ SignUpPage.jsx
│  │  ├─ store/
│  │  │  ├─ useAuthStore.js
│  │  │  ├─ useChatStore.js
│  │  │  └─ useThemeStore.js
│  │  ├─ App.jsx
│  │  ├─ index.css
│  │  └─ main.jsx
│  ├─ index.html
│  ├─ tailwind.config.js
└─ README.md

```

## 🛠️ Getting Started

### Prerequisites

- Node.js and npm
- MongoDB

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/sainath-666/CHATTY_REALTIME_CHATTING.git
   cd CHATTY_REALTIME_CHATTING
   ```

2. **Install dependencies**

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Start the development servers**

   ```bash
   # Start backend (from backend directory)
   npm run dev

   # Start frontend (from frontend directory)
   npm run dev
   ```

## 🌐 Deployment

### Build the app

```bash
npm run build
```

### Start the production server

```bash
npm start
```

## 👨‍💻 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<div align="center">
  <p>Made with ❤️ by Your Sainathreddy</p>
</div>
