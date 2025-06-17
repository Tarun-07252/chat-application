# Real-time Chat Application

![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.1-green)

Real-time chat application with WebSocket support.

## Features
- Instant messaging
- Multiple chat rooms
- User authentication
- Message history

## Tech Stack
- Java 17
- Spring Boot 3.1
- WebSocket
- Thymeleaf
- Spring Security

## Run Locally
```bash
mvn spring-boot:run
```

Access at: `https://localhost:8443`


## Project Structure
```plaintext
src/
├── main/
│   ├── java/com/example/chat/application/
│   │   ├── controller/
│   │   │   ├── ChatController.java
│   │   │   └── WebController.java
│   │   ├── model/
│   │   │   ├── ChatMessage.java
│   │   │   └── ChatRoom.java
│   │   ├── service/
│   │   │   ├── ChatService.java
│   │   │   └── ChatRoomService.java
│   │   ├── config/
│   │   │   ├── WebSocketConfig.java
│   │   │   └── SecurityConfig.java
│   │   └── ChatApplication.java
│   ├── resources/
│   │   ├── static/
│   │   │   └── css/
│   │   │       └── style.css
│   │   ├── templates/
│   │   │   ├── login.html
│   │   │   ├── chatroom.html
│   │   │   └── room.html
│   │   └── application.properties
└── test/
    └── java/com/example/chat/application/
