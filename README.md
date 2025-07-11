# 💜 QuickChat — Full Stack Real-Time Chat App

**QuickChat** is a real-time, full-stack chat application built using the **MERN stack** (MongoDB, Express, React, Node.js) with **Socket.IO** for bi-directional communication and **Cloudinary** for image upload. Users can register, log in, and chat with others instantly, with support for sending messages and images.

---

## 🌐 Live Demo

🟣 **Deployed on:** [chatquickk.vercel.app](https://chatquickk.vercel.app)

---

## 📁 Project Structure

```
chat-app/
│
├── client/     # Frontend - React + Vite
│
├── server/     # Backend - Express, MongoDB, Socket.io
│
└── .gitignore
```

---

## 🚀 Tech Stack

- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Express.js, MongoDB, Mongoose
- **Authentication:** JWT
- **Real-Time:** Socket.IO
- **Media Uploads:** Cloudinary
- **Hosting:** Vercel (Frontend), Railway/Render (Backend — set via VITE_BACKEND_URL)

---

## 📦 Features

- ✅ Real-time messaging via Socket.IO
- ✅ Image sending via Cloudinary
- ✅ JWT-based authentication
- ✅ Online/offline status indicator
- ✅ Message seen/unseen tracking
- ✅ Mobile responsive chat UI

---

## 🛠️ Installation & Setup

### 🔧 Backend (server)

1. Navigate to `server/`:
   ```bash
   cd server
   ```

2. Create `.env` file in `/server`:
   ```env
   MONGODB_URI=your_mongodb_uri
   PORT=5000
   JWT_SECRET=your_jwt_secret

   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start development server:
   ```bash
   npm run server
   ```

---

### 💻 Frontend (client)

1. Navigate to `client/`:
   ```bash
   cd client
   ```

2. Create `.env` file in `/client`:
   ```env
   VITE_BACKEND_URL=http://localhost:5000
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start React app:
   ```bash
   npm run dev
   ```

---

## 🔒 Environment Variables

| Key                | Location       | Description            |
| ------------------ | -------------- | ---------------------- |
| `VITE_BACKEND_URL` | `/client/.env` | Backend server URL     |
| `MONGODB_URI`      | `/server/.env` | MongoDB connection URI |
| `PORT`             | `/server/.env` | Backend port           |
| `JWT_SECRET`       | `/server/.env` | JWT signing key        |
| `CLOUDINARY_*`     | `/server/.env` | Cloudinary credentials |

---

## 🧑‍💻 Scripts

| Script           | Description                |
| ---------------- | -------------------------- |
| `npm run server` | Runs backend using Nodemon |
| `npm run dev`    | Runs frontend with Vite    |

---

## 🛡️ License

This project is currently **not licensed**. You're free to explore the code, but for reuse/distribution, please contact the author.

---

## 🙋‍♂️ Author

Made with 💜 by [@priyyannshhu](https://github.com/priyyannshhu)

---

## 📣 Contributing

Contributions, feedback, and suggestions are welcome! Feel free to fork this repo and raise a pull request.

---

## 🚨 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/priyyannshhu/chat-app.git
   cd chat-app
   ```

2. **Setup Backend:**
   ```bash
   cd server
   npm install
   # Create .env file with your credentials
   npm run server
   ```

3. **Setup Frontend:**
   ```bash
   cd ../client
   npm install
   # Create .env file with backend URL
   npm run dev
   ```

4. **Open your browser and navigate to `http://localhost:5173`**

---

## 🎯 Key Features Explained

### 💬 Real-Time Messaging
Socket.IO enables instant bidirectional communication between users, ensuring messages are delivered and received in real-time without page refreshes.

### 🖼️ Image Sharing
Integrated Cloudinary service allows users to upload and share images seamlessly within conversations.

### 🔐 Secure Authentication
JWT-based authentication system ensures secure user sessions and protected routes.

### 📱 Responsive Design
Built with Tailwind CSS for a mobile-first, responsive user interface that works across all devices.

### 🟢 Online Status
Real-time online/offline status indicators help users know when their contacts are available.

---

## 🌟 Show Your Support

If you like this project, please give it a ⭐ on GitHub!

---

*Built with 💜 using the MERN stack and modern web technologies.*
