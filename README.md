# 🏘️ NeighborNet – AI-Powered Community Support Platform

NeighborNet is an AI-powered community support platform that connects people who need assistance with volunteers who can help during emergencies and everyday situations. The platform leverages AI-based semantic matching to intelligently pair users with suitable volunteers based on their requests, skills, and location.

---

## 📌 Project Overview

NeighborNet aims to build a smart, secure, and efficient community support network by enabling users to:

- Request help during emergencies
- Offer volunteer services
- Communicate through real-time messaging
- Share useful community resources
- Find the most suitable volunteer using AI semantic matching

The platform enhances community collaboration by reducing response time and improving the accuracy of volunteer matching.

---

## ✨ Features

- 🔐 Secure User Authentication
- 👤 User Profile Management
- 🤝 Request and Offer Help
- 💬 Real-Time Messaging
- 📍 Community Resource Sharing
- 🤖 AI-Based Semantic Matching
- 📱 Responsive User Interface
- ⚡ Fast and Interactive React Application

---

## 🏗️ System Architecture

```
                 React Frontend
                        │
                        ▼
                 REST API Layer
                        │
                        ▼
             Node.js + Express Server
                        │
                        ▼
                   MongoDB Database
                        │
                        ▼
            AI Semantic Matching Engine
```

---

## 🛠️ Technology Stack

### Frontend
- React.js
- JavaScript
- HTML
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI
- Semantic Matching Algorithm

### API
- RESTful APIs

---

## 📂 Project Structure

```
NeighborNet/
│
├── client/                 # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── database/
│
├── AI/
│   └── Semantic Matching
│
├── README.md
└── package.json
```

---

## 🚀 How It Works

### Step 1 – User Registration

Users create an account and securely log in.

---

### Step 2 – Create Request

A user posts a request for assistance by providing details such as:

- Type of help
- Description
- Location

---

### Step 3 – Volunteer Registration

Volunteers register and specify:

- Skills
- Availability
- Interests

---

### Step 4 – AI Semantic Matching

The AI engine analyzes:

- User request
- Volunteer skills
- Context similarity

It then recommends the most suitable volunteer.

---

### Step 5 – Real-Time Communication

Matched users communicate using the built-in messaging system.

---

### Step 6 – Request Completion

Once the assistance is completed, the request is marked as resolved.

---

## 🤖 AI Component

NeighborNet uses **Semantic Matching**, an AI technique that understands the meaning of text rather than relying on exact keyword matching.

### Example

**User Request**

> "Need someone to deliver medicines."

**Volunteer Skill**

> "Medical assistance and medicine delivery"

Even though the wording is different, the AI recognizes that both describe the same intent and creates a match.

---

## 📡 REST API Examples

### User Authentication

```
POST /signup
POST /login
```

### User Management

```
GET /users
```

### Messaging

```
POST /message
GET /messages
```

### Community Requests

```
POST /request
GET /requests
```

---

## 🗄️ Database

MongoDB stores dynamic community information including:

- User Profiles
- Volunteer Details
- Help Requests
- Messages
- Community Resources
- Location Information

---

## 📈 Advantages

- Intelligent volunteer matching
- Faster emergency response
- Secure authentication
- Real-time communication
- Scalable architecture
- User-friendly interface
- Flexible NoSQL database

---

## 🎯 Future Enhancements

- Voice Assistant Integration
- Multi-language Support
- Live Location Tracking
- Push Notifications
- Video Calling
- AI Chatbot
- Emergency SOS Button
- Mobile Application
- Admin Analytics Dashboard

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/DHUYUKSHAA/NeighborNet.git
```

### Navigate to Project

```bash
cd NeighborNet
```

### Install Frontend Dependencies

```bash
cd client
npm install
npm start
```

### Install Backend Dependencies

```bash
cd server
npm install
npm start
```

---

## 👩‍💻 Author

**Dhuyukshaa**

B.E. Electronics and Communication Engineering

GitHub: https://github.com/DHUYUKSHAA

---

## 📄 License

This project is developed for educational, research, and learning purposes.

---

## ⭐ Acknowledgements

- React.js
- Node.js
- Express.js
- MongoDB
- Artificial Intelligence (Semantic Matching)
- Open Source Community
