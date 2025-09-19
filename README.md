# 📚 Library Management System

A simple **web-based Library Management System** built with **Node.js, Express, MongoDB, and Mongoose**.  
It allows admins to manage books (add, update, delete) and users to register, borrow, and return books.  

---

## 🚀 Features

- User authentication (Register & Login)
- Role-based access (Admin / User)
- Admin can add, edit, and delete books
- Users can borrow and return books
- Track book availability and stock
- Upload and serve book cover images
- MongoDB for data persistence

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Authentication:** JWT (JSON Web Tokens)  
- **Image Handling:** Multer / Local Storage  

---

## 📂 Project Structure

library-management-system/
│ app.js
│ package.json
│ .env
│
├── models/
│ └── book.js
│
├── routes/
│ ├── indexRoutes.js
│ ├── bookRoutes.js
│ └── userRoutes.js
│
├── public/
│ └── images/ # Book cover images
│
└── README.md

yaml
Copy code

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
Install dependencies

bash
Copy code
npm install
Setup environment variables
Create a .env file in the root folder:

env
Copy code
PORT=5000
DB_URL=mongodb://127.0.0.1:27017/libraryDB
JWT_PRIVATE_KEY=your_secret_key
Run the project

bash
Copy code
nodemon app.js
App will run at: http://localhost:5000

📖 Sample Data
You can seed sample books into the database using:

bash
Copy code
node insertSampleBooks.js
