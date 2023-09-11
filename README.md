# Chatify: Real-Time Chat Application

Chatify is a real-time chat application built with modern web technologies, including MongoDB, Express, React, Node.js, Socket.io, and Chakra UI. It allows users to effortlessly create and join group chats for teamwork and community engagement, engage in private conversations, and securely share files through one-on-one chat. With Socket.io, Chatify delivers instant message delivery and synchronization, providing a seamless real-time messaging experience.

## Features

- **Group Chats:** Create and join group chats with ease, making it perfect for team collaboration and community interaction.

- **Private Conversations:** Engage in one-on-one private conversations with other users, ensuring secure and confidential communication.

- **File Sharing:** Share files securely within your one-on-one chats, making it convenient to exchange documents, images, and more.

- **Real-Time Messaging:** Experience instant message delivery and synchronization, thanks to Socket.io, providing a responsive and real-time chat environment.

- **Sleek UI:** Enjoy an intuitive user interface designed with Chakra UI, offering a modern and visually appealing chat experience.

## Getting Started

### Prerequisites

Before running Chatify, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Installation


shell
Copy code
cd chatify
Install server dependencies:

shell
Copy code
cd server
npm install
Install client dependencies:

shell
Copy code
cd ../client
npm install
Configuration
Create a .env file in the server directory and configure the following environment variables:

makefile
Copy code
MONGODB_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key_for_jwt
Update the client-side configuration if needed (e.g., API endpoint URLs) in the client codebase.

Usage
Start the server:

shell
Copy code
cd ../server
npm start
Start the client:

shell
Copy code
cd ../client
npm start
Access Chatify in your web browser at http://localhost:3000.
