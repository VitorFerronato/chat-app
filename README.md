# Chat App

## 💻 The project
Este é um aplicativo de chat em tempo real onde dois usuários podem se comunicar através de mensagens, registrar novos usuários, fazer login, ver outros usuários online e iniciar uma conversa.

## Funcionalidades

- Registro de usuários
- Login de usuários
- Visualização de outros usuários online
- Comunicação em tempo real entre dois usuários
- Interface amigável com React Bootstrap

## 🚀 Tecnologias Utilizadas

### Frontend

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **React Bootstrap**: Framework de design responsivo para React.

### Backend

- **Node.js**: Ambiente de execução JavaScript do lado do servidor.
- **Express**: Framework web para Node.js.
- **Bcrypt**: Biblioteca para hash de senhas.
- **MongoDB**: Banco de dados NoSQL.
- **Socket.IO**: Biblioteca para comunicação em tempo real.

## Instalação
FRONT
```bash
cd client
npm install
npm run dev
```

BACK ( Outro terminal )
```bash
cd server
npm install
nodemon
```
SOCKET (Outro terminal)
```bash
cd socket
npm install
nodemon
```

Crie um arquivo .env na raiz do projeto e adicione essas configurações
```
ATLAS_URI = mongodb+srv://vitorferronato:*Vue481516@cluster0.jioxnim.mongodb.net/chat-app?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET_KEY = supersecretkey481516
```

## Contribuição
- Faça um fork do projeto.
- Crie uma nova branch (git checkout -b feature/nome-da-sua-feature).
- Commit suas mudanças (git commit -m 'Adiciona nova feature').
- Faça o push para a branch (git push origin feature/nome-da-sua-feature).
- Abra um Pull Request


