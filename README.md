# Skyline Pizza

This project is a Realtime Pizza Delivery application developed using Node.js, MongoDB, Express.js, Socket.IO for real-time communication, Tailwind CSS for styling, EJS templates for server-side rendering, Laravel Mix for asset compilation, Passport for authentication and Stripe for payment processing. 

The application allows users to order pizzas in real-time, track their orders and make payments securely.

## Features

1. **Real-Time Order Tracking:**
- Users can track the status of their pizza orders in real-time.
- Real-time updates on order confirmation, order preparation, delivery, etc., using Socket.IO.
2. **Pizza Ordering:**
- Users can browse through a menu of available pizzas, select toppings, sizes and customize their orders.
- Integration with Stripe for secure payment processing.
3. **User Authentication:**
- Secure authentication using Passport, allowing users to sign up, log in, and log out securely.
4. **Admin Panel:**
- Admin dashboard for managing pizza orders.
- Admin can update menu items, track orders and manage user accounts.
5. **Responsive Design:**
- Ensure the application is optimized for various devices and screen sizes, providing a seamless user experience across desktop and mobile platforms.

## Technologies Used

- **Node.js:** JavaScript runtime environment for server-side development.
- **MongoDB:** NoSQL database for storing pizza menu, user data and order information.
- **Express.js:** Backend framework for handling server-side logic and routing.
- **Socket.IO:** Real-time communication library for enabling bidirectional communication between clients and the server.
- **Tailwind CSS:** Utility-first CSS framework for styling the UI components.
- **EJS Template:** Server-side templating engine for generating dynamic HTML content.
- **Laravel Mix:** Asset compilation tool for compiling JavaScript, CSS and other assets.
- **Passport:** Authentication middleware for Node.js applications, supporting various authentication mechanisms.
- **Stripe:** Payment processing platform for handling online payments securely.

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/Nirav-919/Skyline-Pizza.git
```

2. Navigate to the project directory:

```bash
cd Skyline-Pizza
```

3. Install dependencies for both frontend and backend:

```bash
npm install
```

4. Set up environment variables:

- Create a .env file in the root directory and add necessary environment variables.

```bash
COOKIE_SECRET=
MONGO_CONNECTION_URL=
STRIPE_PRIVATE_KEY=
```

5. Open a terminal and compile assets using Laravel Mix:

```bash
npm run watch
```

6. Open another terminal and start the development server:

```bash
npm run dev
```

7. Open your browser and navigate to http://localhost:3300 to view the application.