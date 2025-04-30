FoodDelivery - Online Food Ordering Web App
# Project Description
FoodDelivery is a full-stack web application that allows users to browse restaurant menus, add food items to a cart, and place online orders. It also provides a simple dashboard for restaurant owners to manage menus and orders. The app is built using the MERN stack (MongoDB, Express.js, React, Node.js), combining a responsive user interface with a robust backend and cloud-hosted database.
This project demonstrates how modern technologies can be used to create real-world applications with seamless user experiences and backend functionality. It also reflects practical skills in web development, REST API creation, frontend design, and secure data management.

# Features
User registration and login
View and search restaurant menu items
Add to cart and checkout functionality
Order tracking
Admin panel for managing food items and orders
Responsive design for desktop and mobile
# Technologies Used
Frontend: React, JavaScript, HTML, CSS
Backend: Node.js, Express.js
Database: MongoDB Atlas
Tools: Mongoose, dotenv, Postman (for API testing)

# Folder Structure
FoodDelivery/
│
├── client/           # Frontend React app
│   ├── src/
│       ├── components/
│       ├── pages/
│       └── App.js
│
├── server/           # Backend with Express.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── index.js
│
└── README.md
# How to Run
Clone the repository (git clone):- https://github.com/kanishhkkaa/FoodDelivery.git
cd FoodDelivery
Install dependencies
Frontend:
cd client
npm install

Backend:
cd ../server
npm install
Set up environment variables
In server/.env:
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
PORT=5000
Start the app

Backend:
node index.js
Frontend:
cd ../client
npm start
