# Real-Time Chat App with WebSockets

This repository contains a real-time chat application demo using React (Context API), Node.js, Express, Socket.io, and MongoDB. Authentication is handled via JWT. Deployment is demonstrated with Docker and Docker Compose.

## Features

1. **User Registration & Login** (JWT-based)
2. **Online Presence Indicator**
3. **Multiple Chat Rooms** (General, Sports, Tech, etc.)
4. **Typing Indicator**
5. **Message History** (Last 20 messages per room)
6. **Private Messaging** (1-on-1)

## Tech Stack

- **Frontend**: React + Context API, react-router-dom v6
- **Backend**: Node.js + Express + Socket.io, MongoDB (Mongoose)
- **Auth**: JSON Web Tokens (JWT)
- **Deployment**: Docker, Docker Compose (services: `server`, `client`, `mongo`)

## Getting Started (Local Development)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/real-time-chat-app.git
   cd real-time-chat-app
   ```
