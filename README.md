# Real-Time Code Execution Platform

A scalable and secure real-time code execution platform built using Node.js, React, Socket.IO, Docker, and AWS EC2.  
This platform allows users to execute code in isolated Docker containers with real-time output streaming and multi-user support.

---

## Features

- Real-time code execution
- Live output streaming using WebSockets
- Secure isolated execution using Docker containers
- Multi-user support
- Responsive frontend UI
- Cloud deployment on AWS EC2
- Scalable microservices-based architecture

---

## Tech Stack

### Frontend
- React.js
- Vite
- Socket.IO Client
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js
- Socket.IO
- Docker

### Cloud & DevOps
- AWS EC2
- Docker Containers

---

Installation & Setup
Clone Repository
git clone https://github.com/your-username/Real-Time-Code-Execution-Platform.git
cd Real-Time-Code-Execution-Platform

Backend Setup
cd backend
npm install
npm start

Backend runs on: http://localhost:5000


Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs on: http://localhost:5173

How It Works
User writes code in the frontend editor.
Code is sent to backend using Socket.IO.
Backend creates isolated Docker execution environment.
Code executes securely inside container.
Output is streamed back to frontend in real-time.

Key Highlights
Secure sandboxed code execution
Real-time communication architecture
Docker containerization for isolation
Cloud deployment support
Scalable backend design

Future Improvements
Authentication & Authorization
Support for multiple programming languages
Collaborative coding rooms
Code saving functionality
Kubernetes deployment
AI-powered code suggestions
Deployment


Author
Chananya Arora
GitHub: https://github.com/Chananya1912

License
This project is licensed under the MIT License.
