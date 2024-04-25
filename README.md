# Online Food Ordering System

This repository contains the source code for an online food ordering system, consisting of both frontend and backend components. The system allows users to register, login, browse restaurants, view menus, manage carts, and place orders.

## Project Overview

The online food ordering system is built using Next.js for the frontend and Node.js with Express.js for the backend. It utilizes MongoDB as the database for storing user information, restaurant data, menu items, and orders.

### Features

- **User Management**: Users can register, login, and logout. Authentication is token-based.
- **Restaurant Management**: Admins can perform CRUD operations on restaurants, including adding, editing, and deleting.
- **Menu Management**: Restaurants can manage their menus by adding, editing, and deleting items.
- **Cart System**: Users can add items to their carts and proceed to checkout.
- **Order Placement**: Users can place orders for their selected items.

## Technologies Used

### Frontend

- **Next.js**: A React framework for building server-rendered applications.
- **React**: A JavaScript library for building user interfaces.
- **Axios**: A promise-based HTTP client for making requests to the server.
- **Cookies**: A library for handling cookies in the browser.
- **Tailwind CSS**: A utility-first CSS framework for styling.

### Backend

- **Node.js**: A JavaScript runtime environment for server-side code.
- **Express.js**: A web application framework for Node.js.
- **MongoDB**: A NoSQL database for storing application data.
- **Mongoose**: An ODM library for MongoDB, used for data modeling and database operations.

## Project Structure

- **frontend/**: Contains the frontend code written in Next.js.
- **backend/**: Contains the backend code written in Node.js with Express.js.
- **public/**: Contains static assets such as images and CSS files.
- **config/**: Configuration files including database configuration and environment variables.
- **routes/**: Contains route definitions for various functionalities.
- **models/**: Defines Mongoose schemas for database entities.
- **middlewares/**: Contains middleware functions for authentication and authorization.
- **database.js**: Handles database operations using Mongoose ORM.

## Setup Instructions

1. Clone the repository.
2. Set up the backend server and database.
3. Navigate to the `frontend/` directory and install frontend dependencies using `npm install`.
4. Navigate to the `backend/` directory and install backend dependencies using `npm install`.
5. Set up your environment variables by creating a `.env` file in both the frontend and backend directories, providing necessary values.
6. Run the frontend server using `npm run dev` in the `frontend/` directory.
7. Run the backend server using `node index.js` in the `backend/` directory.

## Contributors

- Jainish Patel
