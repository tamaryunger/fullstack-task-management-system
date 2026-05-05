# Task & Project Management System

A full-stack web application for managing projects and tasks with user tracking.  
Built with React, Node.js, Express, and MongoDB.

## Tech Stack
- Frontend: React, Redux, Vite, Axios
- Backend: Node.js, Express
- Database: MongoDB (Atlas / Local)
- Architecture: REST API

## Features
- Create, update, delete projects
- Create, update, delete tasks
- Assign tasks to projects
- Task status tracking (To Do / In Progress / Done)
- Priority levels for tasks
- User management system
- MongoDB integration with Mongoose
- Clean REST API structure

## Project Structure
backend/ - Express server, routes, models  
ReactProject/ - React frontend (Vite)

## Installation & Run

### Backend
cd backend  
npm install  
npm run dev  

Create `.env` file:
MONGODB_URI=your_mongodb_connection_string  
PORT=5000  

### Frontend
cd ReactProject  
npm install  
npm run dev  

## API Endpoints

### Projects
GET /projects  
POST /projects  
PUT /projects/:id  
DELETE /projects/:id  

### Tasks
GET /tasks  
POST /tasks  
PUT /tasks/:id  
DELETE /tasks/:id  

### Users
GET /users  
POST /users  
PUT /users/:id  
DELETE /users/:id  
GET /users/search  

## Notes
Backend runs on http://localhost:5000  
Frontend runs on http://localhost:5173  
Make sure MongoDB is running or connected to Atlas
