# TalkTown - Chat Application

## Overview
The **TalkTown** application is a feature-rich real-time chat platform designed to connect users seamlessly. It provides secure and instant communication with group chat capabilities, ensuring an engaging and smooth user experience across devices. Built with modern web technologies, it ensures scalability, responsiveness, and performance.

## Features
- **User Authentication**: Secure login and registration using encrypted credentials.
- **Real-Time Messaging**: Instant communication enabled by WebSocket technology.
- **Group Chats**: Users can create and join group conversations effortlessly.
- **Typing Indicators**: Displays when a user is typing in a chat.
- **Read Receipts**: Indicates when messages are delivered and read.
- **Media Sharing**: Share images and files in chats.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.

## Technologies Used
- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript
  - React.js
- **Backend**:
  - Node.js
  - Express.js
- **Database**:
  - MongoDB
- **Real-Time Communication**:
  - Socket.IO
- **Authentication**:
  - JSON Web Tokens (JWT)
- **Other Tools**:
  - Axios (for API calls)
  - Cloudinary (for media storage)

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/Dkrishnavamsi/TalkTown.git
   ```

2. Navigate to the project directory and set up the backend:
   ```bash
   cd TalkTown/backend
   npm install
   npm start
   ```

3. Set up the frontend:
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. Access the application at `http://localhost:3000`.

## Usage
1. **Register/Login**: Create an account or log in with existing credentials.
2. **Start Chatting**: Create or join one-on-one or group chats.
3. **Share Media**: Upload and share images or files during conversations.
4. **Monitor Activity**: Use typing indicators and read receipts for real-time status updates.

## Project Structure
```
TalkTown
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── config
│   └── server.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── utils
│   │   └── App.js
└── README.md
```

---
For any queries or contributions, please reach out through the [GitHub repository](https://github.com/Dkrishnavamsi/TalkTown).

