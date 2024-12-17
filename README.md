# Expense-Tracker-System

## Full-Stack Web Application

This project is built using modern web technologies, including Node.js, Express, React.js, MongoDB, and several libraries for styling and security. Below, you'll find instructions for cloning, installing dependencies, and running the application.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Available Scripts](#available-scripts)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Full-Stack Application**: Combines a backend with Node.js/Express and a frontend with React.js.
- **Database Integration**: MongoDB for storing application data.
- **Styling**: CSS, Bootstrap, and Ant Design (antd) for clean UI design.
- **Security**: Bcrypt for password encryption.
- **Responsive UI**: Built with modern CSS frameworks and responsive design principles.

## Technologies Used

- **Node.js**: JavaScript runtime for backend.
- **Express**: Web framework for Node.js.
- **React.js**: Frontend JavaScript library for building user interfaces.
- **MongoDB**: NoSQL database.
- **CSS**: Custom styles for layout and design.
- **Bootstrap**: CSS framework for responsive design.
- **Ant Design (antd)**: React UI components library.
- **HTML5**: Markup language for structure.
- **Bcrypt**: Library for hashing and securing passwords.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 14 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) package manager
- MongoDB installed and running locally or a MongoDB Atlas cluster

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. **Install dependencies:**

   Navigate to the backend folder and install dependencies:

   ```bash
   cd backend
   npm install
   ```

   Navigate to the frontend folder and install dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

### Running the Application

1. **Start the MongoDB server:**
   Ensure MongoDB is running locally or configure the connection string for your database.

2. **Run the backend server:**

   Navigate to the `backend` directory and start the server:

   ```bash
   cd backend
   npm run dev
   ```

   The backend server will run at `http://localhost:5000` by default.

3. **Run the frontend application:**

   Navigate to the `frontend` directory and start the React application:

   ```bash
   cd ../frontend
   npm start
   ```

   The frontend will be available at `http://localhost:3000`.

### Environment Variables

Create a `.env` file in the backend folder and add the following environment variables:

```
PORT=5000
MONGO_URI=<Your_MongoDB_URI>
JWT_SECRET=<Your_Secret_Key>
```

Replace `<Your_MongoDB_URI>` and `<Your_Secret_Key>` with appropriate values.

## Available Scripts

### Backend Scripts
- `npm run dev`: Starts the backend server in development mode.
- `npm start`: Starts the backend server.

### Frontend Scripts
- `npm start`: Starts the React development server.
- `npm run build`: Builds the frontend for production.

## Folder Structure

```
├── backend
│   ├── config          # Configuration files (e.g., database connection)
│   ├── models          # Mongoose models
│   ├── routes          # API routes
│   ├── controllers     # Request handlers
│   ├── middleware      # Custom middleware
│   ├── server.js       # Entry point for backend server
├── frontend
│   ├── public          # Static assets
│   ├── src
│   │   ├── assets      # Images, fonts, etc.
│   │   ├── components  # Reusable React components
│   │   ├── pages       # Page components
│   │   ├── utils       # Utility functions
│   │   ├── App.js      # Main React component
│   │   ├── index.js    # Entry point for React app
│   ├── package.json    # Frontend dependencies
├── package.json        # Backend dependencies
└── README.md           # Project documentation
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

