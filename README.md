
# Alumni Connect Platform

Alumni Connect Platform is a full-stack web application designed to strengthen connections between alumni and students. It facilitates mentorship, career guidance, professional networking, and event management. The project features a modern React frontend and a Node.js/Express backend with real-time chat, file uploads, and secure authentication.

## Features
- Alumni and student authentication
- Real-time messaging (Socket.io)
- Event creation and management
- File/image uploads (Cloudinary)
- Follow and mentorship system
- Admin controls
- Responsive UI with React, TailwindCSS, and Vite

## Installation & Setup

### Prerequisites
- Node.js (v18+ recommended)
- npm

### 1. Clone the Repository
```bash
git clone https://github.com/Kushagra1taneja/Hack-the-Future-SpiritX.git
cd Hack-the-Future-SpiritX
```

### 2. Backend Setup
```bash
cd backend
npm install
# Create a .env file with your MongoDB URI and Cloudinary credentials
# Example .env:
# MONGO_URI=your_mongo_uri
# CLOUDINARY_CLOUD_NAME=your_cloud_name
# CLOUDINARY_API_KEY=your_api_key
# CLOUDINARY_API_SECRET=your_api_secret
npm start
```

### 3. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
# The app will run at http://localhost:5173/
```

## Usage
- Register/login as alumni or student
- Explore events, connect with users, send messages
- Admins can manage users and events

## Project Structure
- `backend/` - Node.js/Express API, Socket.io, MongoDB models
- `frontend/` - React app (Vite, TailwindCSS)
- `uploads/` - Uploaded files/images

## Contributing
Pull requests are welcome! Please follow best practices and add meaningful commit messages.
