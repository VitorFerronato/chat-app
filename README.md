# CHAT APP

<div style="display:flex">
<img align="center" alt="vuejs" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img align="center" alt="vuejs" src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" />
<img align="center" alt="vuejs" src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img align="center" alt="vuejs" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
<img align="center" alt="vuejs" src="https://img.shields.io/badge/Socket.io-010101?&style=for-the-badge&logo=Socket.io&logoColor=white" />
</div>



## 💻 The Project
This is a real-time chat application where two users can communicate through messages, register new users, log in, see other users online, and start a conversation.
</br>
![image](https://github.com/VitorFerronato/chat-app/assets/94748997/9535a290-55f0-450a-85f5-9c10eb4f4105)

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
