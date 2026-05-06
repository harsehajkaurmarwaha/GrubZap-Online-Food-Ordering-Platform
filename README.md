Setup: 
Follow the steps below to run the project locally on your machine.

🌐 1. Setup Frontend (Client)

cd client
npm install
npm run dev
Dev Server: http://localhost:5173

Tech: React, Tailwind CSS, React Router

🖥️ 3. Setup Backend (Server)

cd ../server
npm install
npm run dev
API Server: http://localhost:5000

Handles: Authentication, Orders, Restaurant Data

a) Backend Environment Setup Create a .env file inside /server with the following:
PORT=5000
DATABASE_URL=your_database_url_here
JWT_SECRET=your_jwt_secret_here

