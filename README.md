# KetoFood Delivery full-stack Project

A premium keto food delivery application built with React, Tailwind CSS, Node.js, Express, and MongoDB.

## Features
- **User Authentication**: JWT-based Register and Login.
- **Product Menu**: Filterable and searchable keto meal list.
- **Nutritional Info**: Each meal shows Protein, Carbs, and Fat content.
- **Shopping Cart**: Real-time cart management.
- **Modern UI**: Built with glassmorphism, smooth animations, and premium typography.

## Setup Instructions

### 1. Prerequisites
- Node.js installed.
- MongoDB installed and running locally on `mongodb://localhost:27017`.

### 2. Backend Setup
1.  Open a terminal in the `server` directory.
2.  Install dependencies: `npm install` (if not already done).
3.  Seed the database with initial food items:
    ```bash
    npm run seed
    ```
4.  Start the backend server:
    ```bash
    npm run dev
    ```
    The server will run on `http://localhost:5000`.

### 3. Frontend Setup
1.  Open another terminal in the `client` directory.
2.  Install dependencies: `npm install` (if not already done).
3.  Start the frontend application:
    ```bash
    npm run dev
    ```
    The application will usually run on `http://localhost:5173`.

## Technologies Used
- **Frontend**: React, Vite, Tailwind CSS, Lucide Icons, Framer Motion.
- **Backend**: Node.js, Express, Mongoose, JWT, BcryptJS.
- **Database**: MongoDB.
