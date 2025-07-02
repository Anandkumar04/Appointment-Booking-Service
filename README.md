# BookEasy - Appointment Booking Platform 🗓️✨

BookEasy is a full-stack MERN web application for booking services like salon appointments, medical checkups, yoga sessions, and more. Users can register, sign in, and schedule appointments with professionals.

## 🚀 Live Demo

- 🔗 Frontend (Vercel): [https://book-easy-nine.vercel.app/](https://book-easy-nine.vercel.app/).
- 🔗 Backend (Render): [https://book-easy-1270.onrender.com](https://book-easy-1270.onrender.com)

---

## 🛠️ Features

- 👤 User login and registration
- 📆 Book and cancel appointments
- 🧾 View all your bookings in the profile page
- 🔒 Secure JWT-based authentication
- 🌐 Deployed on **Render** (backend) and **Vercel** (frontend)
- 💅 Clean responsive UI using Tailwind CSS

---

## 🧱 Tech Stack

**Frontend**  
- React  
- React Router  
- Tailwind CSS  

**Backend**  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT for authentication  

---

## 📂 Folder Structure

📁 Appointment-Booking-Platform
│
├── client (React frontend)
│ ├── components/
│ ├── pages/
│ ├── api.js
│ └── App.jsx
│
├── server (Express backend)
│ ├── routes/
│ ├── models/
│ ├── controllers/
│ └── server.js
│
└── README.md


---

## ⚙️ How to Run Locally

1. Clone the repository:

git clone https://github.com/Anandkumar04/Appointment-Booking-Platform.git
cd Appointment-Booking-Platform
Install frontend dependencies:


cd client
npm install
Install backend dependencies:


cd ../server
npm install
Set environment variables in a .env file:


PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run backend:


npm run dev
Run frontend (in client/):


npm run dev
🙋‍♂️ Author
Anand Kumar

GitHub: @Anandkumar04

📃 License
This project is licensed under the MIT License.

