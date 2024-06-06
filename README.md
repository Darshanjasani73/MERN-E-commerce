# E-Commerce Website

## Overview

This project is an E-Commerce website built using the MERN stack (MongoDB, Express.js, React, Node.js). It provides a fully functional online shopping platform with features like product listings, user authentication, shopping cart, and order management.

## Features

- **User Authentication**: Register, login, and manage user accounts.
- **Product Management**: Add, edit, delete, and view products.
- **Shopping Cart**: Add products to the cart, view cart, and manage cart items.
- **Order Management**: Place orders, view order history, and manage orders.
- **Admin Panel**: Manage users, products, and orders.
- **Responsive Design**: Mobile-friendly layout for an optimal user experience on all devices.

## Technologies Used

- **Frontend**: React.js, Redux, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Payment Gateway**: (Plans to integrate payment gateway using Paytm in the future) 

## Getting Started

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/ecommerce-mern.git
    cd ecommerce-mern
    ```

2. **Install server dependencies:**
    ```sh
    cd backend
    npm install
    ```

3. **Install client dependencies:**
    ```sh
    cd ../frontend
    npm install
    ```

### Configuration

1. **Backend Configuration:**
   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables:
     ```env
     NODE_ENV=development
     PORT=5000
     MONGO_URI=your_mongoDB_connection_string
     JWT_SECRET=your_jwt_secret
     ```

2. **Frontend Configuration:**
   - Create a `.env` file in the `frontend` directory.
   - Add the following environment variables:
     ```env
     REACT_APP_API_URL=http://localhost:5000/api
     REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
     ```

### Running the Application

1. **Start the backend server:**
    ```sh
    cd backend
    npm run dev
    ```

2. **Start the frontend server:**
    ```sh
    cd ../frontend
    npm start
    ```

3. **Open your browser and navigate to:**
    ```
    http://localhost:3000
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact Djasani93@gmail.com).
