# ⚡ ElectroPulse - Full Stack MERN E-Commerce Platform

ElectroPulse is a modern, production-grade e-commerce application built using the MERN stack (MongoDB, Express, React, Node.js) with Redux Toolkit for state management and JWT for secure authentication.

## ✨ Key Features
- **User Authentication**: Secure JWT-based authentication stored in HTTP-Only cookies.
- **State Management**: Redux Toolkit & RTK Query for state management, API caching, and automated re-fetching.
- **Product Search & Pagination**: Server-side searching, filtering, and page navigation.
- **Shopping Cart & Checkout**: Interactive cart with price calculations, shipping, and tax logic.
- **Payment Gateway**: Integrated PayPal Sandbox and Credit Card workflow.
- **Admin Dashboard**:
  - Manage products (Create, Edit, Delete)
  - Manage users & admin permissions
  - Mark orders as delivered / paid
- **Product Review System**: Customer rating system with verified purchase validation.

## 🛠️ Tech Stack
- **Frontend**: React.js, React-Bootstrap, Redux Toolkit, RTK Query, React Icons
- **Backend**: Node.js, Express.js, Mongoose ODM, JWT, Bcrypt.js
- **Database**: MongoDB Atlas (Cloud)

## ⚙️ Environment Variables
Create a `.env` file in the root directory:
\`\`\`env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret_key
PAYPAL_CLIENT_ID=sb
\`\`\`

## 🚀 Running Locally
\`\`\`bash
# Install dependencies
npm install
cd frontend && npm install --legacy-peer-deps && cd ..

# Import sample data
npm run data:import

# Run frontend and backend concurrently
npm run dev
\`\`\`