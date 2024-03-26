# Foodi 🍔

Foodi is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to browse, search, and discover recipes from various cuisines, as well as contribute their own recipes. The application features user authentication, CRUD operations, and integration with third-party APIs for recipe data. 🍽️

## Features

### Client Side:
- **Order Food:** Users can browse the available menu, select items, and place orders for delivery or pickup. 🛒
- **User Authentication:** Secure user authentication system allows users to sign up, log in, and log out. 🔒
- **Add Food to Cart:** Users can add items to their shopping cart, review their selections, and proceed to checkout. 🛍️
- **Payment Gateway Integration (Stripe):** Seamless integration with the Stripe payment gateway for secure and convenient online payments. 💳

### Admin:
- **Register User:** Admins can register new users, granting them access to the system. 📝
- **Manage All Users:** Full control over user management, including viewing user details, editing user profiles, and deactivating accounts if necessary. 👤
- **Add Food:** Admins can add new food items to the menu, including details such as name, description, price, and availability. 🥗
- **Change Order Status:** Admins have the authority to update the status of orders, such as confirming, preparing, delivering, or completing them. 🚚

## Technologies Used

- MongoDB: NoSQL database used for storing recipe data. 🍃
- Express.js: Web application framework for building RESTful APIs. 🚀
- React.js: Frontend library for building user interfaces. ⚛️
- Node.js: JavaScript runtime environment for server-side development. 🖥️
- Mongoose: MongoDB object modeling tool for Node.js. 🧩

## Getting Started

To run the Foodi-Complete application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies by running `npm install` in both the `client` and `server` directories.
4. Start the server by running `npm start` in the `server` directory.
5. Start the client by running `npm start` in the `client` directory.
6. Open your web browser and navigate to `http://localhost:3000` to view the application. 🚀

## Contributing

Contributions to Foodi-Complete are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name (`git checkout -b feature/my-new-feature`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push your changes to your forked repository (`git push origin feature/my-new-feature`).
5. Create a new pull request on the original repository. 🎉
