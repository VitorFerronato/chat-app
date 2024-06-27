# Chat App

## 💻 The Project
This is a real-time chat application where two users can communicate through messages, register new users, log in, see other users online, and start a conversation.

## Features

- User registration
- User login
- View other users online
- Real-time communication between two users
- User-friendly interface with React Bootstrap

## 🚀 Technologies Used

### Frontend

- **React**: JavaScript library for building user interfaces.
- **React Bootstrap**: Responsive design framework for React.

### Backend

- **Node.js**: JavaScript runtime environment for server-side development.
- **Express**: Web framework for Node.js.
- **Bcrypt**: Library for password hashing.
- **MongoDB**: NoSQL database.
- **Socket.IO**: Library for real-time communication.

## Installation
Create a .env file in the root of the project and add these configurations:
```bash
ATLAS_URI = mongodb+srv://vitorferronato:*Vue481516@cluster0.jioxnim.mongodb.net/chat-app?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET_KEY = supersecretkey481516
```

FRONT
```bash
cd client
npm install
npm run dev
```

BACK
```bash
cd server
npm install
nodemon
```

SOCKET
```bash
cd socket
npm install
nodemon
```

## Contribution
- Fork the project.
- Create a new branch (git checkout -b feature/your-feature-name).
- Commit your changes (git commit -m 'Add new feature').
- Push to the branch (git push origin feature/your-feature-name).
- Open a Pull Request.
