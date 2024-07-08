# E-commerce Dashboard

This project is an E-commerce Dashboard built using the MERN (MongoDB, Express, React, Node.js) stack. The dashboard allows administrators to manage products, orders, users, and view various analytics.

## Table of Contents

1. [Features](#features)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Environment Variables](#environment-variables)
6. [Technologies Used](#technologies-used)
7. [Folder Structure](#folder-structure)
8. [Contributing](#contributing)
9. [License](#license)

## Features

- User authentication and authorization
- Product management (CRUD operations)
- Order management (CRUD operations)
- User management (CRUD operations)
- Dashboard analytics and charts
- Responsive design

## Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed or access to a MongoDB Atlas account

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/ecommerce-dashboard.git
   ```

2. Navigate to the project directory:

   ```sh
   cd ecommerce-dashboard
   ```

3. Install server dependencies:

   ```sh
   cd backend
   npm install
   ```

4. Install client dependencies:

   ```sh
   cd ../frontend
   npm install
   ```

## Usage

1. Start the backend server:

   ```sh
   cd backend
   npm start
   ```

2. Start the frontend development server:

   ```sh
   cd ../frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`

## Environment Variables

Create a `.env` file in the `backend` directory and add the following environment variables:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Technologies Used

- MongoDB: Database
- Express: Backend framework
- React: Frontend library
- Node.js: JavaScript runtime
- Redux: State management
- Chart.js: For creating charts and graphs

## Folder Structure

```
ecommerce-dashboard/
│
├── backend/                 # Node.js backend
│   ├── config/              # Configuration files
│   ├── controllers/         # Controllers for handling requests
│   ├── models/              # Mongoose models
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware
│   └── server.js            # Entry point for the backend
│
├── frontend/                # React frontend
│   ├── public/              # Public assets
│   ├── src/                 # React source files
│   │   ├── components/      # React components
│   │   ├── pages/           # React pages
│   │   ├── redux/           # Redux store and slices
│   │   ├── App.js           # Main app component
│   │   └── index.js         # Entry point for the frontend
│   └── package.json         # Frontend dependencies
│
└── README.md                # This readme file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

---

Feel free to reach out if you have any questions or need further assistance. Enjoy using the E-commerce Dashboard!
