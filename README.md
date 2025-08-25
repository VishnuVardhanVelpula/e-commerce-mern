🛒 MERN E-Commerce Website

This is a full-stack E-Commerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
It supports user authentication, product browsing, shopping cart, order management, reviews, wishlist, and more.

🚀 Features

👤 User Authentication (Register, Login, Logout, JWT + Cookies)

📦 Product Management (CRUD for products, categories, brands)

🛒 Cart & Wishlist (Add, update, remove items)

💳 Order Management (Place orders, track status)

⭐ Product Reviews (Add/edit reviews with ratings)

📍 Address Management for orders

🔐 Secure password hashing & protected routes

⚡ RESTful API with Express.js

🎨 Frontend built in React with Axios for API calls

🏗️ Tech Stack

Frontend: React.js, Axios, TailwindCSS / CSS

Backend: Node.js, Express.js

Database: MongoDB + Mongoose

Authentication: JWT & Cookies

Other Tools: dotenv, morgan, cookie-parser, cors

📂 Project Structure
E-commerce-website/
│── backend/          # Express backend
│   ├── routes/       # API routes (Auth, Users, Products, Orders, etc.)
│   ├── database/     # DB connection
│   ├── models/       # Mongoose models
│   └── server.js     # Entry point
│
│── frontend/         # React frontend
│   ├── src/          # React components, pages, services
│   └── public/
│
└── README.md         # Project documentation

⚙️ Setup & Installation
1️⃣ Clone the repo
git clone https://github.com/<your-username>/E-commerce-website.git
cd E-commerce-website

2️⃣ Backend Setup
cd backend
npm install


Create a .env file in backend/ with:

MONGO_URI=mongodb://127.0.0.1:27017/ecommerce
JWT_SECRET=your_secret_key
ORIGIN=http://localhost:3000


Run backend:

npm start


Backend will run on http://localhost:8000

3️⃣ Frontend Setup
cd frontend
npm install


Create a .env file in frontend/ with:

REACT_APP_BASE_URL=http://localhost:8000/api


Run frontend:

npm start


Frontend will run on http://localhost:3000



🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📜 License

This project is licensed under the MIT License.
