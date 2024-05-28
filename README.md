# Task Manager Web Application Documentation

## Overview
The Task Manager web application allows users to create, view, update, and delete tasks. The application consists of frontend, backend, database, and API components. Users can register, log in, and manage their tasks.

## Features
- User Registration
- User Login
- Task Management (Create, Read, Update, Delete)
- User Authentication and Authorization
- Responsive Design

## Technologies Used
- **Backend:** Node.js, Express.js
- **Frontend:** React.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Other Libraries:** Axios, Mongoose, bcryptjs

## Prerequisites
- Node.js
- MongoDB
- npm

## Installation

### Clone the Repository
```bash
git clone https://github.com/Mihir02/task-manager.git
cd task-manager
```

### Project Structure

```bash
task-manager/
├── client/                  # Frontend application (React.js)
├── server/                  # Backend application (Node.js, Express.js)
│   ├── backend.js           # Express server
│   ├── mongo.js             # Mongoose connection
│   ├── routes/              # API routes
│   └── index.js             # Entry point
└── README.md                # Project documentation

```
### .env

```bash

DATABASE_URI = ""
SECRET_KEY = ""

```

