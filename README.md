# Books Management System

## Overview

The **Books Management System** is a web application that allows users to manage books, register, and log in. It is built using the **MERN** (MongoDB, Express.js, React.js, Node.js) stack, and the project is divided into **Backend** and **Frontend** directories.

---

## Tech Stack

- **Frontend**: React.js, Tailwind CSS, Vite
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **State Management**: Context API

---

## Folder Structure

### Backend

- `controller/`: Contains logic for handling book and user-related operations.
  - `book.controller.js`
  - `user.controller.js`
  
- `model/`: Defines Mongoose schemas for books and users.
  - `book.model.js`
  - `user.model.js`
  
- `route/`: API routes for books and users.
  - `book.route.js`
  - `user.route.js`
  
- `node_modules/`: Dependencies for backend.
- `.env`: Environment variables.
- `index.js`: Entry point for the backend.
- `package.json`: Backend dependencies and scripts.

### Frontend

- `public/`: Stores static assets like images.
- `src/`: Main source code folder.
  - `components/`: Reusable UI components.
    - `Banner.jsx`, `Cards.jsx`, `Course.jsx`, `Footer.jsx`, etc.
  - `context/`: Context API for authentication.
    - `AuthProvider.jsx`
  - `courses/`: Course-related components.
    - `Courses.jsx`
  - `home/`: Homepage components.
    - `Home.jsx`, `App.jsx`
- `index.css`: Global styles.
- `main.jsx`: React entry file.
- `.gitignore`: Git ignored files.
- `index.html`: Main HTML file.
- `package.json`: Frontend dependencies and scripts.
- `tailwind.config.js`: Tailwind CSS configuration.
- `vite.config.js`: Vite configuration.
