# MERN eCommerce Website

## 🚀 Project Overview
This is a fully functional **eCommerce website** built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack**. The platform enables users to browse products, add items to the cart, and complete purchases with secure payment integration.

## 🛠️ Features
- **User Authentication & Authorization** (JWT-based login & registration)
- **Admin Dashboard** for managing products, users, and orders
- **Product Listings** with filtering, sorting, and search functionality
- **Shopping Cart** with dynamic quantity updates
- **Secure Payment Processing** (Stripe/PayPal integration)
- **Order Management** with order tracking & history
- **Reviews & Ratings** for products
- **Responsive Design** for mobile & desktop
- **RESTful API** with proper validation & error handling

## 🏗️ Tech Stack
- **Frontend:** React.js, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Tokens)
- **Payment Gateway:** Stripe/PayPal
- **State Management:** Redux
- **Database:** MongoDB with Mongoose ORM
- **Deployment:** Vercel (Frontend) & Render/Heroku (Backend)

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository:
```sh
 git clone https://github.com/yourusername/mern-ecommerce.git
 cd mern-ecommerce
```

### 2️⃣ Install Dependencies:
```sh
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables:
Create a `.env` file in the **backend** directory and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
STRIPE_SECRET_KEY=your_stripe_secret
```

### 4️⃣ Run the Application:
```sh
# Run Backend
cd backend
npm run dev

# Run Frontend
cd ../frontend
npm start
```

## 📌 API Endpoints
- `GET /api/products` - Fetch all products
- `GET /api/products/:id` - Fetch single product
- `POST /api/users/login` - Authenticate user & get token
- `POST /api/orders` - Create new order

## 🚀 Deployment
### **Frontend Deployment:**
- Deploy on **Vercel** using `vercel deploy`

### **Backend Deployment:**
- Deploy on **Render/Heroku** with `git push heroku main`

## 🎯 Future Enhancements
- **Wishlist & Favorites** feature
- **Coupon & Discount System**
- **Chat Support for Users**

## 🤝 Contributing
Feel free to **fork** this repository and submit pull requests.




Developed by Nanthana S ✨

