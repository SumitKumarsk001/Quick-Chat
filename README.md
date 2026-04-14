📖 Project Overview

Quick Chat is a modern messaging platform that allows users to:

Send and receive messages in real-time
Authenticate securely
Experience a clean and responsive UI

It is designed to demonstrate real-time communication, REST APIs, and full-stack development skills.

🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
Axios
Context API / Redux (if used)
Backend
Node.js
Express.js
MongoDB
Mongoose
Other Tools
Socket.io (for real-time communication)
JWT (Authentication)
Cloudinary (for media upload, if used)
bcrypt.js (Password hashing)
⚡ Features
🔐 User Authentication (Signup/Login)
💬 Real-Time Messaging (Socket.io)
🟢 Online/Offline Status
📱 Responsive UI (Mobile Friendly)
🔎 User Search
📦 RESTful API Integration
☁️ Media Upload Support (if implemented)
🧠 How It Works
Users register and log in securely using JWT authentication.
Once logged in, users can:
See available users
Start conversations
Messages are sent using Socket.io for real-time updates.
Data is stored in MongoDB.
📂 Folder Structure
Quick-Chat/
│── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   └── server.js
│
│── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
│── .env
│── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/SumitKumarsk001/Quick-Chat.git
cd Quick-Chat
2️⃣ Install dependencies
Backend
cd backend
npm install
Frontend
cd frontend
npm install
3️⃣ Setup Environment Variables

Create a .env file in backend:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
4️⃣ Run the project
Backend
npm run dev
Frontend
npm start
