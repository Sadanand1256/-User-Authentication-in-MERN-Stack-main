
# User Authentication in MERN Stack

This project demonstrates a robust user authentication system using the MERN stack (MongoDB, Express.js, React.js, Node.js). It includes features such as user registration, login, and secure access to protected routes.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Registration**: New users can create an account.
- **User Login**: Existing users can log in to access protected resources.
- **JWT Authentication**: Secure user sessions using JSON Web Tokens.
- **Protected Routes**: Restrict access to certain routes based on authentication status.
- **Password Hashing**: Secure user passwords with bcrypt.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB
- npm (Node Package Manager) or yarn

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/User-Authentication-in-MERN-Stack.git
    ```

2. Navigate to the project directory:

    ```bash
    cd User-Authentication-in-MERN-Stack
    ```

3. Install server-side dependencies:

    ```bash
    cd server
    npm install
    ```

4. Install client-side dependencies:

    ```bash
    cd ../client
    npm install
    ```

## Usage

1. Start MongoDB server:

    ```bash
    mongod
    ```

2. Start the backend server:

    ```bash
    cd server
    npm start
    ```

3. Start the frontend server:

    ```bash
    cd ../client
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```markdown
User-Authentication-in-MERN-Stack/
├── client/                 # React frontend
│   ├── public/             # Public assets
│   └── src/                # Source files
│       ├── components/     # React components
│       ├── pages/          # React pages
│       ├── services/       # API services
│       └── App.js          # Main React component
├── server/                 # Express backend
│   ├── config/             # Configuration files
│   ├── controllers/        # Route controllers
│   ├── models/             # Mongoose models
│   ├── routes/             # Express routes
│   └── server.js           # Entry point
└── README.md               # This file

