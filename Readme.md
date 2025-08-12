
# Realtime Chat Application

A lightweight real-time chat application built with **Spring Boot**, **WebSockets**, **STOMP**, and **SockJS**.  
This project enables instant communication between multiple clients through a publish-subscribe messaging model.


## Features

- **Real-time messaging** using WebSocket with STOMP protocol
- **Multiple user support** with sender identification
- **Responsive UI** powered by Bootstrap 5
- **Automatic message scrolling**
- **Clear input fields** after sending messages



## Tech Stack

- **Backend**: Spring Boot, Spring WebSocket, STOMP
- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript
- **Messaging**: SockJS for WebSocket fallback
# Project Structure

Realtime-Chat-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── chat/
│   │   │               ├── controller/
│   │   │               │   ├── ChatController.java
│   │   │               ├── model/
│   │   │               │   ├── Message.java
│   │   │               ├── config/
│   │   │               │   ├── WebSocketConfig.java
│   │   │               └── ChatApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── index.html
│   │       │   ├── js/
│   │       │   │   └── app.js
│   │       ├── templates/
│   │       │   └── chat.html
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── chat/
│                       └── ChatApplicationTests.java
├── .gitignore
├── pom.xml
└── README.md


## Run Locally

Clone the project:

git clone https://github.com/Nawazishkarim07/Realtime-Chat-app.git
cd Realtime-Chat-app



## Installation

- Install Maven dependencies
- mvn clean install


## Usage/Examples

- Start the Spring Boot application
- mvn spring-boot:run
- Visit the app in your browser
  http://localhost:8080
