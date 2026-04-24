# RomboTask – Fullstack Project Management App (MERN)

RomboTask is a fullstack web application for project and task management, inspired by tools like Trello.  
It allows teams to create projects, manage tasks, track progress, and collaborate with role-based permissions.

This project follows the **MERN stack architecture** and is split into two repositories:

- Frontend (React + TypeScript)
- Backend (Node.js + Express + MongoDB)

## Live Demo

Frontend: https://rombo-task-frontend.vercel.app/  
Backend API: https://rombotaskbackend-production.up.railway.app  

## Demo Users

Use the following credentials to explore the application without registration:

- **Manager**  
  rubenm@rombo.com / 11111111  

- **Collaborator**  
  martinf@rombo.com / 22222222  

## Features

- Project creation and management
- Task management (create, update, delete)
- Task status tracking (progress workflow)
- Notes/comments on tasks
- User authentication with **JWT**
- Password recovery functionality
- Role-based permissions (**manager / collaborator**)
- Controlled access to editing and viewing

## Tech Stack

### Frontend
- React
- TypeScript
- React Router
- React Query
- React Hook Form

### Backend
- Node.js
- Express
- TypeScript
- MongoDB
- Mongoose
- JWT Authentication

## Repositories

- Frontend: https://github.com/RomboTask-Fullstack/RomboTask_Frontend  
- Backend: https://github.com/RomboTask-Fullstack/RomboTask_Backend  

## Architecture

The application follows a **client-server architecture**:

- The frontend handles UI, routing, and state management
- The backend exposes a REST API with nested resource routing
- Authentication is handled via JWT tokens
- Role-based authorization controls access to resources

## Author

Developed by **Jordi Romero**
