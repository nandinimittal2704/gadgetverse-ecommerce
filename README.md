# 🛒 GadgetVerse – MERN E-Commerce Platform  

A modern full-stack **E-commerce web application** built with the **MERN stack (MongoDB, Express, React, Node.js)** featuring a dark neon UI theme, secure authentication, Indian Rupee support, and a complete shopping workflow.

This project is fully customized with a unique UI, updated product catalog, and several improvements to provide a real-world online shopping experience.

---

## 🚀 Live Demo  
🔗 **Frontend:** _Coming soon_  
🔗 **Backend API:** _Coming soon_  
🔗 **GitHub Repository:** https://github.com/nandinimittal2704/gadgetverse-ecommerce  

---

## ✨ Features  

### 🛍 Storefront  
- Modern **dark neon UI theme**  
- Product listing with rating, reviews & images  
- Product details page with description  
- Price displayed in **₹ (INR)** format  
- Responsive and clean layout  

### 🛒 Shopping Cart  
- Add/remove items  
- Update quantity  
- Cart saved in localStorage  
- Checkout flow connected to backend  

### 🔐 Authentication  
- Secure **JWT-based login & registration**  
- User profile with order history  
- Password hashing using bcrypt  
- Protected routes  

### 📦 Orders & Payments  
- Create orders  
- View past orders  
- Mark orders as delivered (admin)  
- Supports manual / COD payment method (extendable)  

### 🛠 Admin Panel  
- Manage products  
- Manage orders  
- Manage users  
- Edit/update product details  

### 🇮🇳 India Customizations  
- All prices converted to INR  
- UI theme updated  
- Improved product images  
- Supports Indian e-commerce experience  

---

## 🧰 Tech Stack  

### **Frontend**  
- React.js  
- Redux Toolkit  
- React Router  
- Axios  
- Bootstrap + Custom CSS  

### **Backend**  
- Node.js  
- Express.js  
- JWT Authentication  
- MongoDB Atlas  
- Mongoose  
- Multer (optional image uploads)  

### **Tools**  
- Postman  
- Nodemon  
- Concurrently  
- VS Code  

---

## 📁 Project Structure  

gadgetverse-ecommerce/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── data/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── images/
│ ├── uploads/
│ └── server.js
│
├── frontend/
│ ├── public/
│ └── src/
│ ├── components/
│ ├── screens/
│ ├── redux/
│ ├── styles/
│ └── App.js
│
└── README.md

yaml
Copy code

---

## ⚙️ Environment Variables  

Create a `.env` file inside **backend/**:

NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=placeholder_value

yaml
Copy code

---

## ▶️ Running the Project Locally  

### **1. Install dependencies**

Backend:

```sh
cd backend
npm install
Frontend:

sh
Copy code
cd frontend
npm install
2. Run both servers
From the project root:

sh
Copy code
npm run dev
Frontend: http://localhost:3000

Backend: http://localhost:5000

📦 Seeding the Database
Import sample products/users:

sh
Copy code
npm run data:import
Destroy all data:

sh
Copy code
npm run data:destroy
🚀 Deployment
The project can be deployed on:

⭐ Backend
Render

Railway

Cyclic

⭐ Frontend
Vercel

Netlify

A production build can be created with:

sh
Copy code
cd frontend
npm run build
🌟 Future Enhancements
Planned improvements:

Wishlist / Favorites ❤️

AI-based product recommendation

Price comparison using external APIs

Search auto-suggestions

Admin analytics dashboard

Category-based filtering

👩‍💻 Author
Nandini Mittal
SDE Intern | MERN Developer
📌 India

📄 License
This project is for educational and portfolio use.




