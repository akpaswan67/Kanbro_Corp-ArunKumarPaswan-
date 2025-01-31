# User Management API

A simple **Node.js**, **Express.js**, and **MongoDB** based backend API for managing user records. This API allows for performing **CRUD operations** (Create, Read, Update, Delete) on user data stored in a MongoDB database.

---

## Features

- **Create User**: Add a new user to the database.
- **Retrieve All Users**: Get a list of all users.
- **Retrieve User by ID**: Get details of a single user by their ID.
- **Update User**: Update the details of an existing user.
- **Delete User**: Remove a user from the database by ID.

---

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (using Mongoose for Object Data Modeling)
- **Environment Variables**: dotenv for managing sensitive data like MongoDB URI
- **Security**: CORS for cross-origin resource sharing management

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/user-management-api.git
cd user-management-api
2. Install dependencies
bash
Copy
Edit
npm install
3. Set up environment variables
Create a .env file in the root directory and add the following:

bash
Copy
Edit
MONGO_URI=mongodb://localhost:27017/userdb
PORT=3000
Replace mongodb://localhost:27017/userdb with your actual MongoDB connection string if you're using a remote database.

4. Start the server
bash
Copy
Edit
npm start
