# Full Stack Food Delivery App

Welcome to the Full Stack Food Delivery App! This project is a comprehensive food delivery platform built using the MERN stack (MongoDB, Express.js, React, Node.js) with integrated Stripe payment processing.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication:** Sign up, log in, and log out.
- **Browse Restaurants:** View a list of restaurants and their menus.
- **Cart Management:** Add or remove items from the cart.
- **Order Placement:** Place orders and view order history.
- **Stripe Integration:** Secure payment processing with Stripe.
- **Admin Panel:** Manage restaurants, menus, and orders.


![image](https://github.com/AbhayTomar24/Food-del/assets/62169450/b7f9c8e2-6363-4e9e-a217-5dff27ecf12e)
![image](https://github.com/AbhayTomar24/Food-del/assets/62169450/5babbe80-ad06-4874-856d-0d4dfeb07b28)
![image](https://github.com/AbhayTomar24/Food-del/assets/62169450/b46c2b43-e445-43e4-86e8-0ca27501a1e6)
![image](https://github.com/AbhayTomar24/Food-del/assets/62169450/fae8cc30-30b0-46c6-8405-261cc9d52213)
![image](https://github.com/AbhayTomar24/Food-del/assets/62169450/863ee16b-e684-4155-b1e6-c879c64bcd39)








## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
- Node.js
- npm (Node Package Manager) or yarn
- MongoDB (Local or Atlas)
- Stripe Account (for payment processing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fullstack-food-delivery-app.git
   cd fullstack-food-delivery-app
2. Backend
   ```bash
    cd backend
    npm install
3. Frontend
    ```bash
     cd ../frontend
     npm install
4. Admin
   ```bash
   cd ../admin
   npm install
5. Start MongoDB Server
   ```bash
   mongod
6. Start the Backend Server
   ```bash
   cd backend
   npm start
7. Start the Frontend Server
   ```bash
   cd ../frontend
   npm start
-Open your browser and go to http://localhost:3000.

### Configuration
**Backend**
 - Create a .env file in the backend directory and add the following:
```bash
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
