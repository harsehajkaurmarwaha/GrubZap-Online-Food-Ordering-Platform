# GrubZap – Online Food Ordering Platform

GrubZap is a full-stack online food ordering platform developed by Harsehaj Kaur. The application enables users to discover nearby restaurants, browse dynamic menus, and place orders efficiently. It also includes a scalable backend and a dedicated admin interface for restaurant and order management.

Live Demo: https://grub-zap.onrender.com/

#Overview

GrubZap is designed to provide a seamless food ordering experience by combining a responsive frontend with a robust backend. The system supports real-time interaction with restaurant data, order processing, and user authentication.

#Key Features
1.Location-based restaurant discovery
2.Cart functionality and order management
3.RESTful APIs for users, restaurants, and orders
4.Modular admin panel for managing menus and orders (in progress)
5.Responsive user interface built with modern styling tools
6.Technology Stack
7.Layer	Technology
8.Frontend	React, Tailwind CSS, React Router
9.Backend	Node.js, Express.js
10.Database	PostgreSQL / MySQL (configurable)
11.Admin Panel	React (modular dashboard)
12.Deployment	Render
13.Project Structure

#GrubZap/
├── client/       # Frontend application
├── server/       # Backend APIs and database integration
└── admin/        # Admin dashboard for management
Installation and Setup
1. Clone the Repository
git clone https://github.com/GurmanpreetKaur23/GrubZap.git
cd GrubZap
2. Setup Frontend
cd client
npm install
npm run dev

Frontend runs on:
http://localhost:5173

3. Setup Backend
cd ../server
npm install
npm run dev

Backend runs on:
http://localhost:5000

#Environment Variables

Create a .env file in the /server directory:

PORT=5000
DATABASE_URL=your_database_url_here
JWT_SECRET=your_jwt_secret_here
4. Setup Admin Panel
cd ../admin
npm install
npm run dev

Admin panel runs on:
http://localhost:5174

#Responsibilities
User authentication and session management
Restaurant and menu data handling
Order processing and tracking
Admin controls for managing system data