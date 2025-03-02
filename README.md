# Todo App

A Todo App built with React, Material-UI, and Express.js. This application allows users to register, log in, add, edit, and delete items. It uses JWT tokens for authentication and toast notifications to display success and error messages.

## Features

- User registration and login
- Add, edit, and delete items
- JWT authentication
- Toast notifications for success and error messages
- Responsive design with Material-UI

## Prerequisites

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app.git
Navigate to the project directory:

bash
cd todo-app
Install the dependencies for both the server and client:

bash
cd server
npm install
cd ../client
npm install
Configuration
Create a .env file in the server directory and add the following environment variables:

env
PORT=8000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_uri
Ensure that you have a MongoDB instance running and update the MONGO_URI in the .env file with the correct connection string.

Running the Application
Start the server:

bash
cd server
npm start
Start the client:

bash
cd client
npm start
Open your browser and navigate to http://localhost:3000.

Usage
Register
Click on the Register button in the navbar.

Fill in your name, email, and password.

Click the Register button to create an account.

Login
Click on the Login button in the navbar.

Enter your email and password.

Click the Login button to log in.

Add Item
Once logged in, navigate to the Items page.

Fill in the title and description in the Add Item form.

Click the Add Item button to add the item.

Edit Item
On the Items page, click the Edit button next to the item you want to edit.

Update the title and description.

Click the Save button to save the changes.

Delete Item
On the Items page, click the Delete button next to the item you want to delete.

Confirm the deletion.

API Endpoints
User Routes
POST /users/register: Register a new user.

POST /users/login: Log in a user.

GET /users/logout: Log out a user.

GET /auth/check-token: Check if the JWT token is valid.

Item Routes
GET /items: Get all items.

POST /items: Add a new item.

PUT /items/:id: Update an item.

DELETE /items/:id: Delete an item.

Technologies Used
React

Material-UI

Express.js

MongoDB

JWT (JSON Web Token)

Axios

React Toastify

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
React

Material-UI

Express.js

MongoDB

React Toastify
