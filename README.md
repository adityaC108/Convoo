# Convoo

Convoo is a clean, fast, and responsive real-time chat application built to provide seamless communication with instant message delivery. It focuses on simplicity, speed, and real-time interactions using Socket.io and a modern MERN-based tech stack.

## Features

- Secure JWT-based user login, signup, and protected route access with hashed passwords.

- Manage and update user details including avatar, status, and email with Cloudinary support.

- Send, receive, and store messages with real-time communication powered by Socket.io.

- Track user online/offline status and update UI through live socket events.

- Robust client/server validations with graceful fallbacks and clear user-friendly error messages.

## Tech Stack
### Frontend

- React.js

- Tailwind CSS

- Zustand

- DaisyUI

### Backend

- Node.js

- Express.js

- MongoDB

- Socket.io

- JWT Authentication

- Cloudinary

## Future Enhancements

- End-to-End Encryption

- Voice & Video Calling

- Secure Media & File Sharing

- Group Chats & Community Channels

- Message Reactions & Typing Indicators

- Push Notifications

## Installation

1. Clone the Repository

```bash
  git clone <your-repo-url>
  cd CONVOO
```

2. Setup Backend

```bash
  cd backend
  npm install
```

  Create a .env file inside /backend and add:

```bash
  MONGO_URI=your_mongodb_url
  PORT=5001
  JWT_SECRET=your_secret_key
  CLOUDINARY_CLOUD_NAME=your_cloud_name
  CLOUDINARY_API_KEY=your_api_key
  CLOUDINARY_API_SECRET=your_api_secret
```

Start backend server:

```bash
  npm start
```
3. Setup Frontend

```bash
  cd frontend
  npm install
  npm run dev

```
4. Access the Application

Frontend:

```bash
  http://localhost:5173/
```
Backend:

```bash
  http://localhost:5001/
```

Thank you for exploring CONVOO! Feel free to contribute or share your suggestions.
