# LearnHub

A comprehensive learning platform offering a variety of courses to enhance your skills in programming, design, and more. Built with React, Tailwind CSS on the frontend and Node.js, Express on the backend.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)

## Features
- A wide range of courses on different topics (e.g., programming, design, etc.).
- Responsive design using Tailwind CSS.
- Secure user authentication and authorization.
- RESTful API for managing courses and users.
- Admin panel to manage courses and users.

## Tech Stack

### Frontend:
- **React**: For building dynamic and responsive user interfaces.
- **Tailwind CSS**: For fast and customizable styling.

### Backend:
- **Node.js**: For server-side operations.
- **Express**: For handling API requests.
- **MongoDB**: (optional, if used) For database management.

## Installation

### Prerequisites
- **Node.js** installed on your machine (version 14.x or higher recommended).
- **MongoDB** for database (if applicable).

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**:
   - Install backend dependencies:
     ```bash
     cd server
     npm install
     ```

   - Install frontend dependencies:
     ```bash
     cd ../client
     npm install
     ```

3. **Set up environment variables**:
   - Create a `.env` file in the `server` folder and provide your environment variables (e.g., database URI, secret keys).
   - Example:
     ```bash
     MONGO_URI=your_mongo_uri
     CLIENT_URL=your_client_URL
     PORT=your_port
     ```

4. **Run the development server**:
   - Backend (Node.js/Express):
     ```bash
     cd server
     npm run dev
     ```
   - Frontend (React):
     ```bash
     cd ../client
     npm start
     ```

## Usage

1. **Frontend**: 
   - Navigate to `http://localhost:5173` in your browser to access the learning platform.
   - Register or log in to view and enroll in courses.

2. **Backend API**: 
    - for example
   - Access the RESTful API at `http://localhost:5000/api`.
