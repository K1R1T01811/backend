#  Personal Finance Management (PFM) Dashboard — Backend

## Overview
The **backend** of the Personal Finance Management Dashboard is built using **Node.js**, **Express.js**, and **MongoDB**.  
It provides secure authentication, database connectivity, and API endpoints for managing users, transactions, and accounts.

This backend acts as the bridge between the frontend and the database, ensuring data security and smooth communication.

---

## Tech Stack
- **Node.js**
- **Express.js**
- **MongoDB** with Mongoose
- **JWT** (JSON Web Token) for authentication
- **dotenv** for environment variables
- **CORS** enabled

---

## Project Structure
backend/
│
├── models/ # Mongoose models (User, Account, Transaction)
├── controllers/ # Business logic for each route
├── routes/ # API routes
├── middleware/ # Auth middleware (JWT verification)
├── server.js # Entry point of the application
└── .env # Environment variables.
