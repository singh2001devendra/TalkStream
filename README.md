
# Talk-Stream Application

## Overview
This project is a real-time chat application developed using the MERN stack (MongoDB, Express, React, and Node.js) with **Socket.IO** for real-time communication. It allows users to register, log in, and join chat rooms to communicate in real-time. The app includes features for private messaging, group chats, and online/offline status updates.

## Features

🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
🎃 Authentication && Authorization with JWT
👾 Real-time messaging with Socket.io
🚀 Online user status (Socket.io and React Context)
👌 Global state management with Zustand
🐞 Error handling both on the server and on the client
⭐ At the end Deployment like a pro for FREE!
⏳ And much more

### User Interface
- **Login/Register**: Secure login and registration system.
- **Chat Dashboard**: A user dashboard that lists available chat rooms, recent contacts, and active users.
- **Real-Time Messaging**: Real-time communication in chat rooms and direct messages.
- **Online Status**: Shows the online/offline status of contacts in real-time.

### Chat Functionality
- **Private Messaging**: One-on-one direct messages between users.
- **Group Chats**: Multiple users can join a chat room to communicate together.
- **Message Timestamps**: Each message includes a timestamp for context.
- **Typing Indicator**: Shows when another user is typing in a chat.

### User Presence and Notifications
- **Online/Offline Status**: Updates as users connect and disconnect.
- **Read Receipts**: Shows whether messages have been read (optional).
- **Notifications**: Real-time notifications for new messages.

## Technology Stack
- **Frontend**: React, Redux, Bootstrap, Socket.IO-client
- **Backend**: Node.js, Express, Socket.IO
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)

## Assumptions and Design Choices
- **Socket.IO**: Used for real-time, bidirectional communication, enabling instant message updates and presence status.
- **Database Storage**: MongoDB stores user information, message history, and room details.
- **Authentication**: JWT is used to securely handle user sessions.
- **Notifications**: Notifications are only for unread messages; no push notifications are included in this version.

## Setup Instructions

### Prerequisites
- **Node.js**: Version 14+
- **MongoDB**: Running locally or MongoDB Atlas account
- **NPM** or **Yarn**

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/chat-app.git
    cd chat-app
    ```

2. **Install Backend Dependencies**:
    ```bash
    cd server
    npm install
    ```

3. **Install Frontend Dependencies**:
    ```bash
    cd ../client
    npm install
    ```

4. **Environment Variables**:
   - In the `/server` directory, create a `.env` file and add the following:
     ```env
     MONGO_URI=
     JWT_SECRET=
     PORT=5000
     ```
   - In the `/client` directory, create a `.env` file and add any frontend environment variables if needed.

### Running the Application

1. **Start the Backend Server**:
    ```bash
    cd server
    npm start
    ```

2. **Start the Frontend Server**:
    ```bash
    cd ../client
    npm start
    ```

3. **Access the Application**:
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

### Running Tests
- **Backend Tests**: Use a testing framework like Mocha or Jest (if set up).
    ```bash
    cd server
    npm test
    ```
- **Frontend Tests**: Run tests with React Testing Library or Jest.
    ```bash
    cd client
    npm test
    ```

## Future Enhancements
- **Push Notifications**: Add push notifications for new messages when the user is offline.
- **Message Reactions**: Allow users to react to messages with emojis.
- **Media Sharing**: Enable users to share images, videos, or other files.
- **User Status Updates**: Let users set status messages (e.g., "Available," "Busy").
- **Message Search**: Implement search functionality for chat history.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



