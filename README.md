# Chat Application 🗨️

A real-time chat application with frontend and backend components.  
Built using ReactJS with a frontend UI + backend server with MongoDB.


## Features

- Real-time chats between users  
- Separate frontend & backend codebases  
- User interface built with modern ReactJS 
- Backend server for chat handling (e.g. via WebSocket and MongoDB)  
- Basic styling and UX  

## Folder Structure

Chat-Application/
- ├── backend/ # Backend server (Node.js, APIs, database, etc.)
- ├── frontend/ # UI code (HTML, CSS, JS)
- ├── package.json # Project metadata & scripts
- ├── .gitignore # Files/folders to ignore in Git
- └── README.md # This file


## Requirements

- Node.js (version >= 14)  
- npm or yarn  
- Optional: a database (if backend uses one)  

---

## Getting Started

1. Clone the repo:
- git clone https://github.com/nithin521/Chat-Application.git
- cd Chat-Application
   
## Install dependencies:

- cd backend
- npm install
- cd ../frontend
- npm install

## Run the backend server:
- cd backend
- npm start

## Run the frontend:
- cd frontend
- npm start

Open your browser and navigate to the frontend URL (commonly http://localhost:3000) to start chatting.

## Configuration
In the backend folder, set environment variables (if required), e.g.:
- PORT=5000
- DATABASE_URL=your_database_connection_string

In the frontend folder, configure API endpoints (in JS / config) to point to the backend server URL.
Usage
Open the UI in a browser.
Send messages and receive replies in real time.
UI is responsive and easy to use.

## API Endpoints
Method	Endpoint	Description
- GET	/status	Check server status
- POST	/login	User login
- POST	/register	Register new user
- GET	/messages	Fetch message history
- POST	/messages/send	Send a new message

## Future Improvements
- Persist chat history (in database)
- Typing indicators
- Online/offline status for users
- Improved UI/UX (mobile responsive, themes)
- Deployment setup (Docker, cloud hosting, etc.)

---
