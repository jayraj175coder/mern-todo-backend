# MERN To-Do Backend

## Overview

This project is the backend component of the MERN To-Do application. It is built using Node.js and Express.js, and it manages the API endpoints for CRUD operations on to-do items. The backend connects to a MongoDB database and handles requests from the frontend.

## Features

- **API Endpoints**:
  - `GET /todos` – Retrieve all to-do items.
  - `POST /todos` – Create a new to-do item.
  - `PUT /todos/:id` – Update an existing to-do item.
  - `DELETE /todos/:id` – Delete a to-do item.

- **MongoDB Integration**: Uses Mongoose for schema definitions and database operations.
- **CORS Support**: Allows requests from the frontend domain.

## Technologies Used

- **Node.js**: For the server runtime environment.
- **Express.js**: For building the REST API.
- **MongoDB**: For the database.
- **Mongoose**: For MongoDB schema and data modeling.
- **Cors**: For handling Cross-Origin Resource Sharing.

## Setup Instructions

### 1. Clone the Repository


git clone https://github.com/your-username/mern-todo-backend.git

cd mern-todo-backend



