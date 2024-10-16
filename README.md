FitTrack MERN Stack Application

FitTrack is a full-stack fitness tracker application built using the MERN stack (MongoDB, Express, React, and Node.js). It provides users with workout tracking, blog articles, and a dashboard for monitoring fitness activities.
Table of Contents

    Features
    Tech Stack
    Prerequisites
    Project Structure
    Installation
    Environment Variables
    Running the App
    Contributing
    License

Features

    User authentication (sign up, login)
    Track workouts, calories burned, active minutes
    Interactive dashboard with charts for data visualization
    Fetch and display blog articles
    Responsive and intuitive UI using React and Tailwind CSS
    Backend API built with Express and MongoDB for data management

Tech Stack

    Frontend: React.js, Tailwind CSS, Shadcn UI, Framer Motion
    Backend: Node.js, Express.js, MongoDB, Mongoose
    Authentication: JWT-based authentication
    Routing: React Router for frontend routing, Express for backend routing
    Tools & Libraries: Axios, Moment.js, bcrypt, Helmet, Validator

Prerequisites

Before you begin, ensure you have met the following requirements:

    Node.js (v16.x or later)
    npm or yarn
    MongoDB (installed and running locally or hosted on MongoDB Atlas)

Project Structure

bash

.
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── server.js
│   ├── .env
│   └── ...
├── frontend
│   ├── src
│   ├── public
│   ├── .env
│   └── ...
├── .gitignore
├── package.json
└── README.md

Installation
Clone the repository

bash

git clone https://github.com/your-username/fittrack-mern.git
cd fittrack-mern

Install dependencies
Frontend:

bash

cd frontend
npm install

Backend:

bash

cd backend
npm install

Environment Variables

You need to configure environment variables for both the frontend and backend.
Frontend .env file

In the frontend folder, create a .env file:

bash

REACT_APP_API_URL=http://localhost:5000

Backend .env file

In the backend folder, create a .env file with the following variables:

bash

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

Ensure that these .env files are excluded from version control by including them in the .gitignore.
Running the App
Backend

Navigate to the backend folder and run the server:

bash

cd backend
npm start

This will start the backend server at http://localhost:5000.
Frontend

In another terminal window, navigate to the frontend folder and run the React app:

bash

cd frontend
npm start

This will start the frontend on http://localhost:3000.
Connecting Frontend and Backend

The React app will communicate with the backend using the REACT_APP_API_URL defined in the .env file.
Contributing

Contributions are welcome! Please follow these steps:

    Fork the project
    Create a new branch (git checkout -b feature-branch)
    Commit your changes (git commit -m "Add some feature")
    Push to the branch (git push origin feature-branch)
    Open a pull request

License

This project is open-source and available under the MIT License.
