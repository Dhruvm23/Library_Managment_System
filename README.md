# Library Management System

A full-stack MERN (MongoDB, Express, React, Node.js) application for managing books in a library. This system allows users to borrow and return books, view available books, and allows admins to manage the books and users.

## Demo

Walkthrough of the web application:

[![Watch the Demo on YouTube](https://img.youtube.com/vi/H6eCItmeONo/0.jpg)](https://youtu.be/H6eCItmeONo)

## Features

- **User Authentication**: Login and registration for users and admins.
- **Admin Panel**: Admin can add, update, delete, and view books.
- **User Roles**: Differentiates between admins and borrowers.
- **Book Management**: Admins can add new books to the system.
- **Book Borrowing**: Borrowers can view available books and borrow them.
- **File Upload**: Book images are uploaded to Cloudinary.
  
## Tech Stack

- **Frontend**:
  - React
  - Vite
  - Tailwind CSS
  - React Router
  - React Hook Form
  - Axios

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Cloudinary (for image storage)
  - JWT (for authentication)

## Prerequisites

Before running the project, ensure that you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary](https://cloudinary.com/) account

  
## Project Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dhruvm23/library-management-system.git

### Frontend Setup

1. **Navigate to the frontend directory**
   ```bash
   cd library-management-system/frontend
2. **Install dependencies for the frontend**
   ```bash
   npm i
3. **Create a .env file in the frontend directory and add the following:**
   ```bash
   VITE_BASE_URL=http://localhost:3000
4. **Start the frontend development server**
    ```bash
    npm run dev
### Backend Setup

1. **Navigate to the backend directory**
   ```bash
   cd library-management-system/backend

2. **Install dependencies for the backend**
   ```bash
   npm i

3. **Create a .env file in the backend directory and add the following variables:**
   ```bash
    MONGODB_URI=your-mongodb-connection-string
    JWT_SECRET=your-jwt-secret-key
    CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
    CLOUDINARY_API_KEY=your-cloudinary-api-key
    CLOUDINARY_API_SECRET=your-cloudinary-api-secret-key
    CLOUDINARY_FOLDER_NAME=your-cloudinary-folder-name
4. **Start the backend server**
   ```bash
   node server.js

## License

This project is licensed under the MIT License.

## Acknowledgments

- **MongoDB**: A NoSQL database used for storing user and book data.
- **Cloudinary**: A cloud-based image and video management platform used for uploading and storing book images.
- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for building custom designs without having to leave your HTML.


