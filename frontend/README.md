# Project README

# Name: Jainish Patel

## Description
This project is a Next.js application for an online food ordering system. It includes functionality for user authentication, restaurant view, menu display, cart management, and checkout.

# Project Link

You can access the project [here](https://jp-restaurant-client.vercel.app/).
You can register and login with that credentials to use app as normal user.
Login credentials for Admin : 
- username: tester
- password: password


### Login & Signup (Frontend and Backend with Proper Authentication)
- Responsible for designing and implementing the user interface for login/signup.
- Develop backend API endpoints for user registration and authentication.

### Restaurant & Menu functionality (Both Frontend and Backend)
- Design the user interface for displaying restaurant listings.
- Develop backend logic to fetch and serve restaurant data to the frontend.
- Implement the user interface for displaying restaurant menus and menu items.
- Develop backend APIs to retrieve and manage menu data.

### Cart System and Checkout Page (Both Frontend and Backend)
- Design and implement the cart interface, ensuring a smooth user experience.
- Develop backend functionality to handle cart operations, such as adding and removing items.
- Design and implement frontend/backend for the checkout page with a focus on user interaction.

## Client-side Code Overview

### Login (page.tsx)
- Handles user login functionality.
- Sends login requests to the backend.
- Redirects to the home page after successful login.
- Includes a link to the registration page for new users.

### Logout (page.tsx)
- Handles user logout functionality.
- Clears user session data and redirects to the main page.

### Register (page.tsx)
- Handles user registration functionality.
- Sends registration requests to the backend.
- Redirects to the login page after successful registration.

### Add to Cart (page.tsx)
- Placeholder page for adding items to the cart.

### View Cart (page.tsx)
- Displays the items added to the cart.
- Allows users to remove items from the cart.
- Provides functionality for user checkout.

## Technologies Used
- Next.js
- React
- Axios
- Cookies

## Setup Instructions
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up the backend server and database.
4. Set up your environment variables by creating a `.env` file and providing values for `NEXT_PUBLIC_BASE_URL`.
5. Run the development server using `npm run dev`.

---

# Restaurant Management System

This project is a web application for managing restaurants and their menu items. It allows users to add, edit, and delete restaurants, as well as add, edit, and delete menu items for each restaurant.

## Features

- Add new restaurants with details such as name, address, phone, cuisine, and rating.
- Edit existing restaurant details.
- View detailed information about a specific restaurant, including its name, address, phone, cuisine, rating, and menu items.
- Add new menu items to a specific restaurant.
- Edit existing menu items for a restaurant.
- Delete menu items from a restaurant.
- Delete restaurants.

## Technologies Used

- Next.js: A React framework for building server-rendered applications.
- React: A JavaScript library for building user interfaces.
- Axios: A promise-based HTTP client for making requests to the server.
- Cookies: A library for handling cookies in the browser.
- Node.js: A JavaScript runtime environment.
- TypeScript: A typed superset of JavaScript.
- Tailwind CSS: A utility-first CSS framework for styling.

## File Structure

- `pages/`
  - `restaurants.tsx`: Main landing page for displaying all restaurants.
  - `add-restaurant.tsx`: Page for adding a new restaurant.
  - `edit-restaurant.tsx`: Page for editing an existing restaurant.
  - `restaurant-details.tsx`: Page for displaying detailed information about a specific restaurant.
  - `add-menu-item.tsx`: Page for adding a new menu item to a restaurant.
  - `edit-menu.tsx`: Page for editing an existing menu item.
- `context/`
  - `UserContext.tsx`: Context for managing user authentication and authorization.
- `api/`
  - `restaurants.ts`: API routes for handling CRUD operations related to restaurants.
  - `menus.ts`: API routes for handling CRUD operations related to menu items.

---

# Restaurant Management System

This project is a web application for managing restaurants and their menu items. It allows users to add, edit, and delete restaurants, as well as add, edit, and delete menu items for each restaurant.

## Features

- Add new restaurants with details such as name, address, phone, cuisine, and rating.
- Edit existing restaurant details.
- View detailed information about a specific restaurant, including its name, address, phone, cuisine, rating, and menu items.
- Add new menu items to a specific restaurant.
- Edit existing menu items for a restaurant.
- Delete menu items from a restaurant.
- Delete restaurants.
- User registration and authentication.
- User authorization with admin privileges.
- User cart feature for future ordering.
- Order placement functionality.
- User logout functionality.

## Technologies Used

- Next.js: A React framework for building server-rendered applications.
- React: A JavaScript library for building user interfaces.
- Axios: A promise-based HTTP client for making requests to the server.
- Cookies: A library for handling cookies in the browser.
- Node.js: A JavaScript runtime environment.
- TypeScript: A typed superset of JavaScript.
- Tailwind CSS: A utility-first CSS framework for styling.

## File Structure

- `pages/`
  - `restaurants.tsx`: Main landing page for displaying all restaurants.
  - `add-restaurant.tsx`: Page for adding a new restaurant.
  - `edit-restaurant.tsx`: Page for editing an existing restaurant.
  - `restaurant-details.tsx`: Page for displaying detailed information about a specific restaurant.
  - `add-menu-item.tsx`: Page for adding a new menu item to a restaurant.
  - `edit-menu.tsx`: Page for editing an existing menu item.
  - `users.tsx`: Page for displaying all users.
  - `index.tsx`: Root page of the Next.js app.
- `context/`
  - `UserContext.tsx`: Context for managing user authentication and authorization.
- `api/`
  - `restaurants.ts`: API routes for handling CRUD operations related to restaurants.
  - `menus.ts`: API routes for handling CRUD operations related to menu items.
- `components/`
  - `Footer.tsx`: Component for the footer section of the layout.
  - `Header.tsx`: Component for the header section of the layout.
  - `Navbar.tsx`: Component for the navigation bar.
- `public/`
  - `images/`: Directory for storing images used in the application.
- `styles/`
  - `global.css`: Global styles for the application.
