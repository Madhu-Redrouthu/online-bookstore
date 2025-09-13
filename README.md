"# online-bookstore" 


Description: A full-stack e-commerce application for an online bookstore. Users can register, log in, browse and search for books, add items to a shopping cart, and complete the checkout process. The application features a responsive front-end and a robust back-end with RESTful APIs.

Built using React.js (Frontend), Node.js + Express (Backend), and MongoDB (Database).

Features

User Authentication (Login/Register) (can be extended)

Browse, Search & View Books

Shopping Cart (future enhancement)

Checkout & Order Handling (future enhancement)

RESTful API with Express.js

MongoDB database integration

Responsive UI using Bootstrap

Tech Stack

Frontend: React.js, Bootstrap, Axios
Backend: Node.js, Express.js
Database: MongoDB (local or Atlas)
Dev Tools: Git, GitHub, Postman

online-bookstore/
│
├── backend/              # Node.js + Express + MongoDB
│   ├── server.js
│   ├── routes/
│   │   └── bookRoutes.js
│   ├── models/
│   │   └── Book.js
│   └── package.json
│
├── frontend/             # React.js + Bootstrap
│   ├── src/
│   │   ├── App.js
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   └── BookList.js
│   └── package.json
│
└── README.md



CLONE REPOSITORY

git clone https://github.com/Madhu-Redrouthu/online-bookstore.git
cd online-bookstore


Backend Setup
cd backend
npm install
npm run dev


Runs at 👉 http://localhost:5000


Frontend Setup
cd frontend
npm install
npm start


Runs at 👉 http://localhost:3000


API Endpoints
Method	Endpoint	Description
GET	/api/books	Get all books
POST	/api/books	Add a new book


Future Improvements

✅ Add User Authentication (JWT)

✅ Implement Shopping Cart

✅ Checkout & Payment Integration

✅ Deploy Backend (Render/Heroku) & Frontend (Netlify/Vercel)


Madhu Redrouthu

🌐 Portfolio

💼 LinkedIn

📦 GitHub

