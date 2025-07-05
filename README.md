# 📝 Feedback Collection System

A modern web application for collecting, managing, and analyzing feedback from users. Built with the MERN stack (MongoDB, Express, React, Node.js), it provides a user-friendly interface, real-time data submission, and admin analytics.

---

## 📦 Tech Stack

- **Frontend:** React.js, Tailwind CSS (optional)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Tools:** VS Code, Postman, Git, dotenv

---

## 🚀 Features

- ✅ Customizable feedback form
- ✅ Rating with stars (1 to 5)
- ✅ Real-time form submission
- ✅ Stores feedback in MongoDB
- ✅ Feedback dashboard display
- ✅ Responsive and clean UI
- ✅ Secure with environment variables (`.env`)
- ✅ Modular file structure for scalability

---

## 📁 Project Structure
feedback-system/
│
├── client/                   # React Frontend
│   ├── src/
│   │   ├── components/
│   │   │   └── FeedbackForm.jsx
│   │   ├── pages/
│   │   │   └── Dashboard.jsx
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/                   # Node Backend
│   ├── controllers/
│   │   └── feedbackController.js
│   ├── models/
│   │   └── Feedback.js
│   ├── routes/
│   │   └── feedbackRoutes.js
│   ├── server.js
│   └── package.json
│
└── README.md


---

## ⚙️ Setup Instructions

### 1. 📁 Clone the Repository

```bash
git clone https://github.com/your-username/feedback-system.git
cd feedback-system

###2. 🔧 Backend Setup (server/)

cd server
npm install

##Create a .env file:

MONGO_URI=mongodb://localhost:27017/feedback-db
PORT=5000

#Start MongoDB (Linux):

sudo systemctl start mongod

#Run the backend:
npm start

###3. 🎨 Frontend Setup (client/)
