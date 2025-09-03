# ✨ Full Stack Realtime Chat App

Highlights:

- 🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
- 🎃 Authentication && Authorization with JWT
- 👾 Real-time messaging with Socket.io
- 🚀 Online user status
- 👌 Global state management with Zustand
- 🐞 Error handling both on the server and on the client
- ⭐ At the end Deployment like a pro for FREE!
- ⏳ And much more!

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

##  1. Clone the repo
    ```shell
    git clone https://github.com/your-username/chat-app.git
    cd chat-app
    ```
## 2. Install dependencies 
# Backend
    ```shell
    cd backend
    npm install
    ```
# Frontend
    ```shell
    cd frontend
    npm install
   ```
### Run the app     
```shell
npm run build
```

### Start the app

```shell
npm start
```
### Project Structure

Assignment/
│
├── backend/                # Express + MongoDB + Socket.io server
│   ├── lib/                # Database, utils, socket, cloudinary
│   ├── models/             # User & Message models
│   ├── routes/             # Auth & Message routes
│   ├── controllers/        # Business logic
│   ├── middleware/         # Auth middleware
│   └── index.js            # Main entrypoint
│
├── frontend/               # React + Vite client
│   ├── components/         # Navbar, Message components, etc.
│   ├── pages/              # Login, Signup, Home, Profile, Settings
│   ├── store/              # Zustand state stores
│   ├── App.jsx             # Main App with routes
│   └── index.css           # Global styles
│
└── README.md

### Tech Stack
Frontend: React, Vite, TailwindCSS, DaisyUI, Zustand

Backend: Node.js, Express, MongoDB, JWT, bcrypt, Socket.io

Cloud: MongoDB Atlas, Cloudinary

### Future Improvements

Group chat support

Message read receipts

Dark/Light theme toggle

File sharing (PDF, Docs)

Push notification

![Sample User 1](sample-users/Sample-user1.png)

![Sample User 1](sample-users/sample-user2.png)

