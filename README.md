**Randomly(Socket Server)
A real-time chat server built with Node.js, Express.js, and Socket.IO. This server powers the Random Chat Application, enabling seamless communication between users.

***********************************************************************
Note:
This is the Socket-Server of Randomly-chat web app.
Main app repo: https://github.com/webd-rupam/Randomly-Chat-NextJs
***********************************************************************

Features
>🌐 Real-time Communication: Utilizes WebSockets to provide instant messaging capabilities.
>👥 User Management: Tracks connected users and manages chat sessions.
>📦 Message Broadcasting: Sends messages to all connected clients or specific users.
>📈 Scalable Architecture: Designed to handle multiple simultaneous connections efficiently.

Technologies Used
>⚛️ Node.js: JavaScript runtime for building scalable server-side applications.
>🚀 Express.js: Web framework for building APIs and web applications.
>💬 Socket.IO: Library for real-time communication between web clients and servers.

Getting Started
Prerequisites
Node.js
MongoDB Atlas account (if using MongoDB)
Installation
Clone the repository:
bash
Copy code
git clone <repository-url>
Navigate to the project directory:
bash
Copy code
cd socket-server
Install the dependencies:
bash
Copy code
npm install
Set up your MongoDB connection string in the .env file (if applicable).
Running the Server
🚀 To run the server, use:
bash
Copy code
node index.js
The server will listen for incoming WebSocket connections and handle messaging.
License
This project is licensed under the MIT License.
