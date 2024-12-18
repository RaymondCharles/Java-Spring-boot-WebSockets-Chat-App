# Java-Spring-boot-WebSockets-Chat-App
![chat app image](https://github.com/user-attachments/assets/11f86c62-4b09-4ea5-908e-1a61ff33d0ba)


## Features
- Real-time messaging using WebSocket.
- Multiple users can join the chat room.
- Notifications when users join or leave the chat.
- Each user gets a unique avatar color based on their username.
- A lightweight Spring Boot backend with WebSocket support.

## Technology Stack
- Backend: Spring Boot (WebSocket, STOMP)
- Frontend: HTML, CSS, JavaScript
- WebSocket Library: SockJS, STOMP
- Build Tool: Maven

## How It Works
1. User Registration and Chat Interface
Users enter their username to join the chat room.
Once connected, users can send messages to all other users in the chat.
2. Real-Time Messaging
Messages are sent in real-time to all connected clients using WebSocket.
When a user sends a message, it is broadcast to all other users.
3. User Avatar Colors
A unique color is assigned to each user based on their username. This color is used to display an avatar in the chat interface.
4. Join and Leave Notifications
Whenever a user joins or leaves the chat, a notification is broadcasted to inform other users.

## How to Run the Application

1. Clone the Repository
To get started, clone the repository to your local machine:

bash
Copy code
git clone https://github.com/RaymondCharles/Java-Spring-boot-WebSockets-Chat-App
cd spring-boot-websocket-chat-app

2. Build and Run the Application
Make sure you have Maven installed. You can build and run the application with the following command:

bash
Copy code
mvn spring-boot:run

3. Access the Application
Once the application is running, open your browser and go to:

arduino
Copy code
http://localhost:8080

You will be prompted to enter your username to join the chat. After that, you can send messages in real-time to other connected users.

