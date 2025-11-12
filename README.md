MERN E-commerce Store
Description
A full-stack e-commerce platform built using the MERN stack (MongoDB, Express.js, React, Node.js). This application allows users to browse products, manage a shopping cart, create orders, and features admin controls for product and order management.

Features
User registration & authentication (JWT-based)

Product listing, details, and review system

Shopping cart functionality

Order placement and management

Paypal payment integration

Image management using Cloudinary

State management with Redux Toolkit

Responsive, modern UI with Tailwind CSS and Radix UI

Admin panel for product/order control

Technologies Used
Frontend: React, Redux Toolkit, React Router DOM, Axios, Tailwind CSS, Lucide React, Radix UI

Backend: Node.js, Express.js, MongoDB, Cloudinary, Paypal SDK

Build Tools: Vite, PostCSS, ESLint

Other: JWT, dotenv, ESLint, Prettier

Folder Structure
text
/client      # React frontend code
/server      # Express backend (API) code
/shared      # Common files/models if needed
(from your files: App.jsx, main.jsx, store.js, Product.js, Order.js, User.js, Cart.js, Review.js, Address.js, Feature.js, etc.)

Setup Instructions
Clone the repository:

bash
git clone https://github.com/your-username/mern-ecommerce.git
cd mern-ecommerce
Frontend Setup:

bash
cd client
npm install
npm run dev
Backend Setup:

bash
cd server
npm install
npm start
(You may need to create server folder and move backend files like server.js, models, routes, etc.)

Environment Variables:
Add a .env file in both frontend and backend directories for variables like:

text
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
PAYPAL_CLIENT_ID=your_paypal_client_id
See your .gitignore to ensure secrets aren't pushed.

Usage
Visit localhost:5173 for frontend after running npm run dev in /client.

Register/login, browse products, add them to cart, and checkout.

Admin dashboard is accessible for admin users (setup via backend).
