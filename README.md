# CS-499 Computer Science Capstone

Welcome to my ePortfolio! Here you’ll find a collection of projects that showcase my knowledge and skills in computer science.

---

## How to Access

Simply [click this link](https://brachodev.github.io/)

---

## Inventory App:

You can access my capstone project [here](https://github.com/BrachoDev/inventoryApp)

This project is a full-stack inventory management application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to create, view, update, and delete inventory items while demonstrating backend development, database integration, and API design.

---

## 🎥 Milestone One: Code Review

A code review is the process of examining code to identify issues, improve quality, and ensure best practices are being followed. It helps developers catch bugs, improve readability, and think more critically about their design decisions.

For this milestone, I created a video where I reviewed my own code, analyzed its structure, and identified areas for improvement before beginning enhancements.

🎥 Watch my code review video by [clicking here](https://youtu.be/dT1IyXKP-HE).

---

## ⚙️ Milestone Two: Software Design & Engineering Enhancement

For this milestone, I enhanced my inventory application by improving the backend and implementing full CRUD functionality using a RESTful API.

Some of the key improvements include:

- Setting up a Node.js and Express server
- Connecting to a MongoDB Atlas database
- Creating a schema using Mongoose
- Implementing API routes for:
  - Creating products (POST)
  - Retrieving products (GET)
  - Updating products (PUT)
  - Deleting products (DELETE)
- Using environment variables for secure configuration

This milestone focuses on applying software engineering principles such as modular design, scalability, and maintainability.

📄 [Read My Full Narrative](https://github.com/BrachoDev/BrachoDev.github.io/blob/main/3-2%20Milestone%20Two%20Enhancement%20One%20Software%20Design%20and%20Engineering%20-%20Carlos%20Bracho.pdf)

---

## 🧩 Milestone Three: Algorithms and data structures Enhancement

For this milestone, I focused on improving the backend of my inventory application with more robust data handling, validations, and modular architecture. I also started setting up the frontend environment to prepare for full-stack development.

Some of the key improvements include:

- **Refactoring routes and controllers:** I created a `routes` method that includes all CRUD operations for the product collection. To make the code even more modular, I added a `controllers` folder to hold the logic for these operations, which keeps the route files clean and easy to maintain.

- **User management with validation and security:** I created a `user.model.js` schema to store user data for future login functionality. I also added password hashing using `bcryptjs` to secure sensitive data. The `registerUser` method now includes multiple validations:
  - Ensures all required fields are present
  - Validates email format
  - Checks password strength (at least 8 characters, includes uppercase, lowercase, and a number)
  - Checks username length (6 characters minimum) and allowed characters
  - Verifies user uniqueness
  - Validates optional phone numbers

Additional CRUD operations were added for users, including retrieving all users, updating, and deleting accounts.

- **Environment configuration and database management:** I moved sensitive server settings like `PORT` to a `.env` file for security. I also renamed the MongoDB database from `products` to `inventory_app_db` to reflect the inclusion of the users collection, updating the connection string accordingly.

- **Improved code readability and maintainability:** I went back to add detailed comments throughout the backend, including the `server.js`, routes, models, controllers, and database connection files.

- **Frontend setup and testing:** I started the frontend with Vite and installed Chakra UI for UI components. I confirmed the setup works by creating a simple test button that says “Hello.”

This milestone demonstrates the application of data structures and algorithmic logic in a real-world project, particularly in handling user input, validating data, and managing collections. It also highlights modular design, maintainability, and security considerations.

📄 [Read My Full Narrative]()
