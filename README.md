
# Tasty Street Eats - Food Ordering Platform

**Tasty Street Eats** is a feature-rich food ordering platform designed to provide a seamless and intuitive food ordering experience. Developed using the **MERN stack** (MongoDB, Express.js, React, Node.js) for the web and **Kotlin** for the Android application, this platform ensures reliability, speed, and high customer satisfaction across both web and mobile interfaces.

The platform allows users to easily browse food items, place orders, and track deliveries, all from a simple and user-friendly interface.

---

## Features

* **User Registration and Authentication**: Secure login and registration with email verification.
* **Menu Display**: Browse a wide variety of food items with clear descriptions, prices, and images.
* **Search and Filter**: Quickly find food items based on categories, price, or name.
* **Order Placement**: Simple and efficient process for selecting items and placing an order.
* **Order Tracking**: Real-time updates on order status, including preparation and delivery progress.
* **Payment Integration**: Integrated with payment systems for easy, secure payments.
* **Android App**: A dedicated mobile application for ordering food on the go.
* **Responsive Web Interface**: Fully optimized for both mobile and desktop web browsers.
* **Admin Dashboard**: Admin can manage food items, track orders, and view statistics.

---

## Tech Stack

* **Backend**:

  * **MongoDB**: NoSQL database for storing user data, orders, and food items.
  * **Express.js**: Web application framework for Node.js, used for handling API requests.
  * **Node.js**: JavaScript runtime for the server-side application logic.
* **Frontend**:

  * **React.js**: JavaScript library for building interactive user interfaces.
* **Mobile App**:

  * **Kotlin**: Used for developing the Android app, ensuring optimal speed and performance for mobile users.
* **Authentication**:

  * **JWT (JSON Web Tokens)**: For secure user authentication.
* **Payment Integration**:

  * **Stripe API**: For securely processing payments online.

---

## Prerequisites

Before you begin, ensure you have the following installed:

* **Node.js** (latest stable version)
* **npm** (Node package manager)
* **MongoDB** (for local development or use a cloud service like MongoDB Atlas)
* **Android Studio** (for the Kotlin-based Android app development)
* **React Native** (for the mobile app development, if using it for cross-platform)

---

## Installation

### Clone the Repository

Clone the project repository to your local machine:

```bash
git clone https://github.com/yourusername/Tasty-Street-Eats.git
```

### Backend (Node.js)

1. Navigate to the **backend** directory:

```bash
cd Tasty-Street-Eats/backend
```

2. Install dependencies:

```bash
npm install
```

3. Set up your **MongoDB** database and configure the connection in `config.js`.

4. Start the server:

```bash
npm start
```

The backend server should now be running on `http://localhost:5000`.

### Frontend (React.js)

1. Navigate to the **frontend** directory:

```bash
cd Tasty-Street-Eats/frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the React development server:

```bash
npm start
```

The frontend should now be accessible at `http://localhost:3000`.

### Android App (Kotlin)

1. Open **Android Studio**.
2. Import the **Tasty Street Eats** Android project.
3. Build and run the app on your Android device or emulator.

---

## Usage

1. **Web Interface**: Navigate to the web app at `http://localhost:3000` and sign up or log in.
2. **Browse Menu**: Browse available food items and add them to your cart.
3. **Place Order**: Choose the food items you want and proceed to checkout to complete your order.
4. **Track Order**: View the current status of your order from preparation to delivery.
5. **Android App**: Use the mobile app to place orders and track them on the go.

---

## Project Structure

Here is the basic project structure:

```bash
Tasty-Street-Eats/
├── backend/                    # Backend (Node.js, Express)
│   ├── controllers/             # API Controllers
│   ├── models/                  # MongoDB models (Food, Orders, etc.)
│   ├── routes/                  # API routes (user, orders, etc.)
│   ├── config/                  # Database connection and configurations
│   └── server.js                # Main entry point for the Node.js server
├── frontend/                    # Frontend (React.js)
│   ├── components/              # Reusable UI components
│   ├── pages/                   # React pages (Home, Cart, Profile)
│   ├── App.js                   # Main React app component
│   └── index.js                 # Entry point for the React application
├── android/                     # Android mobile app (Kotlin)
│   ├── src/                     # Kotlin source files
│   └── AndroidManifest.xml      # Android app configuration
└── README.md                    # Project documentation
```

---



## Contributing

We welcome contributions to improve the **Tasty Street Eats** platform. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a pull request.

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

* **MongoDB** for providing an efficient NoSQL database.
* **Express.js** for simplifying the backend development.
* **React.js** for an interactive user interface.
* **Kotlin** for a fast, native mobile app experience.
* **Stripe** for secure and seamless payment integration.

---


## Future Improvements

* **Push Notifications**: Add notifications for order updates.
* **Multiple Payment Methods**: Integrate more payment gateways (e.g., PayPal, Google Pay).
* **Rating System**: Implement a system for users to rate food items and services.
* **Order History**: Enable users to view past orders and reorder items easily.
