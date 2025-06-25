#BookStore

##Overview
**BookStore** is a full-stack web application built using the **MERN stack** (**MongoDB, Express.js, React.js, and Node.js**) that provides an intuitive platform for users to browse, search, and purchase books. Admins can manage the inventory, ensuring a seamless experience for both buyers and sellers.

---

## Features
**User Features:**
- Browse and search for books  
- Add books to the cart  
- Secure authentication & profile management   
- Track order history   

**Admin Features:**
- Add, update, and remove books 
- Manage inventory & stock 

**General Features:**
- Secure login & authentication (JWT)  
- Responsive and user-friendly UI  
- Fast and scalable API  

---

## Tech Stack
- **Frontend:** React.js, Redux, Axios, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT (JSON Web Token)  

---


## Installation & Setup

1️**Clone the repository**  
git clone https://github.com/ShubhamYadav27/BookStore.git
cd BookStore

2️**Install dependencies for frontend & backend**
cd frontend && npm install
cd ../backend && npm install

3️**Set up environment variables**
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

4️**Run the development server**
# Start backend
cd backend && npm start
# Start frontend
cd frontend && npm start
