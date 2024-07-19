# Node.js Authentication System

A Node.js backend application for user authentication and authorization using JWT and bcrypt.

## Features

- **User Authentication and Authorization**: Secure user login and registration using JSON Web Tokens (JWT).
- **JWT for Secure Token-Based Authentication**: Ensure secure communication by using JWT for authentication.
- **Bcrypt for Password Encryption**: Use bcrypt to hash and store passwords securely.
- **Role-Based Access Control**: Restrict access to certain routes based on user roles (e.g., Student, Admin).
- **MongoDB Database Connection**: Connect and interact with a MongoDB database using Mongoose.

## Technologies

- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing user data.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **JWT (jsonwebtoken)**: Library to create and verify JSON Web Tokens.
- **Bcrypt**: Library to hash passwords.

## Setup

### Prerequisites

- Node.js installed
- MongoDB installed or access to a MongoDB Atlas account

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/SoumitraKode/auth-system-nodejs
   cd your-repo-name
2. **Install dependencies**:
   ```sh
   npm install
3.  **Create a .env file and add your MongoDB URI and JWT secret**:
      ```sh
         PORT = your_Port
         MONGODB_URI=your_mongodb_uri
         JWT_SECRET=your_jwt_secret
4.**Start the server**:
   ```sh
   npm start
