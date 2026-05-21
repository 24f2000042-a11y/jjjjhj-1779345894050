# Modern Blue Todo App

A simple full‑stack Todo application built with the MERN stack.

## Features

- Add, toggle, and delete tasks
- Responsive modern blue UI
- RESTful API with Express & MongoDB
- Axios for client‑side requests
- Environment variables for configuration

## Project Structure


/frontend   – React + Vite
/backend    – Node.js, Express, MongoDB


## Prerequisites

- Node.js (v18 or later)
- npm or yarn
- MongoDB Atlas account (or local MongoDB)

## Setup

### Backend

bash
cd backend
cp .env.example .env
# Edit .env with your MongoDB connection string
npm install
npm run dev   # starts server on http://localhost:5000


### Frontend

bash
cd frontend
npm install
# Optionally create a .env file to set VITE_API_URL
# VITE_API_URL=http://localhost:5000
npm run dev   # starts Vite dev server on http://localhost:5173


## API Endpoints

| Method | Endpoint          | Description                |
|--------|-------------------|----------------------------|
| GET    | `/api/todos`      | Get all todos              |
| POST   | `/api/todos`      | Create a new todo         |
| PUT    | `/api/todos/:id`  | Toggle completed status    |
| DELETE | `/api/todos/:id`  | Delete a todo              |

## License

MIT