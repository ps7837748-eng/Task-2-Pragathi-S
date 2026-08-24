# Backend Development Project 2 - Database Integration (CRUD)

## Project Overview

This project is a REST API built using Node.js, Express.js, MongoDB, and Mongoose.

The API performs CRUD operations on user data and stores the data permanently in MongoDB.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- REST API
- JavaScript

## User Schema

The User model contains:

- Name
- Email
- Age

Email is unique to prevent duplicate entries.

## CRUD Operations

### 1. Create User

Method: POST

Endpoint:

http://localhost:3000/users

Example request:

```json
{
  "name": "Pragathi",
  "email": "pragathi@example.com",
  "age": 19
}


### 2. Get All Users

Method: GET

Endpoint:

http://localhost:3000/users

### 3. Get User by ID

Method: GET

Endpoint:

http://localhost:3000/users/:id

Example:

http://localhost:3000/users/6a8babf5ce6ce9f9f1c8c930

---

### 4. Update User

Method: PUT

Endpoint:

http://localhost:3000/users/:id

Example request:

```json
{
  "name": "Pragathi S",
  "email": "pragathi@example.com",
  "age": 20
}

### 5. Delete User

Method: DELETE

Endpoint:

http://localhost:3000/users/:id

Example:

http://localhost:3000/users/6a8babf5ce6ce9f9f1c8c930

---

## API Testing

The API can be tested using Postman.

### POST
Create a new user.

### GET
Retrieve all users or a user by ID.

### PUT
Update an existing user's details.

### DELETE
Delete a user from the database.

---

## Conclusion

This project demonstrates how to build a REST API using Node.js, Express.js, MongoDB, and Mongoose with complete CRUD functionality.