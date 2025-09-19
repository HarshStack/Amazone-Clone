🛒 Amazon Clone

An Amazon-inspired e-commerce platform built with a modern tech stack. This project replicates core functionalities of Amazon including authentication, product listings, cart management, checkout, and order history.

🚀 Features

🔐 User Authentication (Sign Up / Login / Logout with JWT)

🛍️ Product Listings with categories and search

🛒 Shopping Cart (Add, remove, update quantities)

💳 Checkout & Payment Flow (dummy/test payment integration)

📦 Order History & Tracking

⭐ Product Ratings & Reviews

📱 Responsive UI for desktop & mobile

🛠️ Tech Stack
Frontend:

React.js

Redux (State Management)

TailwindCSS / CSS Modules

Axios (API calls)

Backend:

Node.js + Express.js

MongoDB + Mongoose (Database)

JWT Authentication

Bcrypt (Password hashing)

Tools & Deployment

Postman (API Testing)

Git & GitHub

Vercel / Netlify (Frontend hosting)

Render / Railway / Heroku (Backend hosting)

⚙️ Installation & Setup
Clone the repository
git clone https://github.com/your-username/amazon-clone.git
cd amazon-clone

Backend Setup
cd Backend
npm install
npm start


Make sure to configure your .env file with:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Frontend Setup
cd Frontend
npm install
npm start


The app will run on http://localhost:3000
 (Frontend) and http://localhost:5000
 (Backend).
