🚨 Women Safety Alert System (MERN Stack)

This is a simple Women Safety Alert System built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The application allows women to
**register their name and phone number**, and provides a **single-click alert button** to send a safety alert. Upon clicking the alert button,
a message like `Alert sent` is shown as a confirmation.

## 🔧 Features

- Input form for Name and Phone Number
- Save details to MongoDB database
- One-click **Alert** button
- Shows a browser alert message: `Alert sent`

## 🧑‍💻 Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Other**: Axios (for API calls), Mongoose (ODM)

## 🚀 How to Run the Project Locally

### Prerequisites

- Node.js and npm
- MongoDB running locally (or MongoDB Atlas)
- Git

---

### Step 1: Clone the Repository

```bash
git clone https://github.com/Manjushree296/women-safety-alert.git
cd women-safety-alert
Step 2: Backend Setup
cd backend
npm install
Create a .env file inside backend folder and add:

MONGO_URI=mongodb://localhost:27017/womenSafetyDB
PORT=5000
Start backend server: node Server.js

mongoDB will start

Step 3: Frontend Setup
cd ../frontend
npm install
npm start
