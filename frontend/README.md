🛒 GadgetVerse – MERN E-Commerce Platform

A fully functional E-commerce web application built using the MERN Stack (MongoDB, Express, React, Node.js) with modern UI, custom theme, Indian Rupee pricing, secure authentication, and complete shopping workflow.

This project is a customized and upgraded version of the base ProShop project — redesigned with a dark neon UI theme, INR currency, updated product catalog, and multiple structural improvements.

🚀 Live Demo

🔗 Frontend: 
🔗 Backend API: 
🔗 GitHub Repository: (Your repo link)

✨ Features
🛍 Storefront

Modern dark theme UI (neon purple + black)

Product listing with images, reviews, price, and rating

Individual product details page

Indian Rupee formatting (₹10,999.00 style)

Fully responsive layout

🛒 Shopping Functionality

Add to cart

Update quantities

Remove items

Cart persistence

Checkout flow integrated with backend

🔐 Authentication & Authorization

Secure JWT-based login/signup

Password hashing using bcrypt

Protected routes for logged-in users

Admin-only access for product & order management

📦 Order Management

Place orders

View order details

Order status updates

Backend integration with MongoDB

🛠 Admin Capabilities

Manage products

Manage users

Manage orders

Create/Edit/Delete products

🇮🇳 India Customization

Currency changed from $ → ₹ (INR)

Product catalog updated

UI redesigned for Indian e-commerce feel

🧰 Tech Stack
Frontend

React.js

React Router

Redux Toolkit

Axios

Bootstrap + Custom Theme

Backend

Node.js

Express.js

JWT Authentication

bcrypt.js

Multer (for uploads if enabled)

Database

MongoDB Atlas (Cloud)

Development Tools

Nodemon

Concurrently

Postman (API testing)

📁 Project Structure
proshop_mern/
│
├── backend/
│   ├── config/          # DB config, JWT config
│   ├── controllers/     # API logic
│   ├── data/            # Product/user seed data
│   ├── middleware/      # Auth, error handling
│   ├── models/          # Mongoose schemas
│   ├── routes/          # Express API routes
│   ├── utils/
│   ├── images/          # Product images (moved from frontend)
│   ├── uploads/         # Upload folder
│   ├── server.js        # Main entry
│   └── .env
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── redux/
│   │   ├── styles/
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│
└── README.md

⚙️ Environment Variables

Create a .env inside backend/:

NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=placeholder_value


(If using Cash on Delivery, PayPal can be ignored.)

▶️ Running the Project Locally
Install dependencies
Backend:
cd backend
npm install

Frontend:
cd frontend
npm install

Run both servers concurrently

From root folder:

npm run dev


Backend → http://localhost:5000

Frontend → http://localhost:3000

📦 Import Sample Data (Products & Users)

To seed sample data:

npm run data:import


To destroy all data:

npm run data:destroy

🚀 Future Enhancements

Planned upgrades:

Wishlist / Favorites ❤️

Categories & filters

AI-based product suggestions

Price comparison (Amazon, Flipkart, etc.)

Search auto-suggestions

Admin analytics dashboard

📄 License

This project is for educational and portfolio use.

🙋‍♀️ Author

Nandini Mittal
SDE Intern Aspirant | MERN Developer | Problem Solver