# Store Ratings System

A full-stack Store Rating System with role-based access for System Admins, Normal Users, and Store Owners.

---

## How to Run the Project

### Prerequisites

Make sure you have the following installed:

- Node.js (v14 or later)
- npm or yarn
- MySQL server

---

### Setup Instructions

1. **Clone the repository** 

git clone https://github.com/MD2403/store-ratings-system.git
cd store-ratings-system

Install dependencies for both frontend and backend

Copy code
# For backend
cd backend
npm install

# For frontend
cd ../frontend
npm install
Configure MySQL database

Create a database named store_ratings.

Create a .env file inside the backend folder and add:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=store_ratings
Run database migrations (if applicable)

Start the backend server

cd backend
npm start
# Server runs on http://localhost:5000
Start the frontend

cd ../frontend
npm start
# React app runs on http://localhost:3000
Features
Role-based login: Admin, User, Store Owner

Store rating and review system

Admin dashboard for managing users and stores

Tech Stack
Frontend: ReactJS, TailwindCSS or MUI

Backend: Node.js, Express

Database: MySQL