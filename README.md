# Social Media Backend API

A simple backend REST API built with **Node.js**, **Express.js**, and **MongoDB**. It provides user authentication and basic social media features.

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

## Features
- User Registration
- User Login & Logout
- Create Post
- Like/Unlike Posts
- Delete Posts
- RESTful API Architecture

## Installation

```bash
git clone <repository-url>
cd project-folder
npm install
npm start
```

## Environment Variables

Create a `.env` file and add:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## API Endpoints

- `POST /register` – Register a new user
- `POST /login` – Login user
- `POST /logout` – Logout user
- `POST /posts` – Create a post
- `PUT /posts/:id/like` – Like/Unlike a post
- `DELETE /posts/:id` – Delete a post

## License

This project is for learning purposes.