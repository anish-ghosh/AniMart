# AniMart

AniMart is an e-commerce platform designed and developed by Anish Ghosh. It provides a user-friendly interface for both buyers and sellers to interact and conduct transactions smoothly. This repository contains the source code for the AniMart platform.

## Features

- **User Authentication**: Secure user authentication system for both buyers and sellers.
- **Product Management**: Sellers can easily add, edit, and delete products from their inventory.
- **Shopping Cart**: Buyers can add products to their cart and proceed to checkout for purchasing.
- **Order Management**: Buyers can view their order history and track the status of their orders.
- **Search and Filter**: Users can search for products and filter them based on various criteria.
- **Responsive Design**: The platform is designed to work seamlessly across different devices and screen sizes.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Database**: MongoDB Atlas (Cloud-hosted MongoDB)
- **Deployment**: Heroku

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/anish-ghosh/AniMart.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AniMart
   ```

3. Install dependencies for both frontend and backend:

   ```bash
   cd client && npm install
   ```

   ```bash
   cd ../server && npm install
   ```

4. Set up environment variables:

   Create a `.env` file in the `server` directory and define the following variables:

   ```
   PORT=3001
   MONGODB_URI=<your_mongodb_uri>
   SECRET_KEY=<your_secret_key>
   ```

5. Run the backend server:

   ```bash
   npm start
   ```

6. Run the frontend:

   Open a new terminal and navigate to the `client` directory:

   ```bash
   cd ../client && npm start
   ```

7. Access the application in your browser:

   Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgements

AniMart was developed as a personal project by Anish Ghosh. Special thanks to the developers of the libraries and frameworks used in this project, as well as the open-source community for their valuable contributions.
