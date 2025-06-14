# Study Notion

Study Notion is an EdTech (Education Technology) web application developed using the **MERN Stack**.

## 🚀 Features

- ✅ User Authentication with JWT  
- ✅ Role-based access: Student, Instructor, Admin  
- ✅ Course Creation and Enrollment  
- ✅ Lesson Progress Tracking  
- ✅ Razorpay Integration for Payments  
- ✅ Instructor Dashboard with Analytics  
- ✅ Responsive UI with Tailwind CSS  
- ✅ Backend APIs with Express.js  
- ✅ MongoDB for Data Persistence

## 📁 Folder Structure

StudyNotionclean/
├── client/ # Frontend (React + Tailwind)
├── server/ # Backend (Node + Express + MongoDB)
├── README.md # Project Documentation

markdown
Copy
Edit

## 🔧 Tech Stack

- **Frontend**: React.js, Tailwind CSS, Redux Toolkit  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB, Mongoose  
- **Payment**: Razorpay  
- **Authentication**: JWT

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/DaksshDixit/StudyNotionclean.git
cd StudyNotionclean
2. Install Dependencies
bash
Copy
Edit
cd client
npm install
cd ../server
npm install
3. Configure Environment Variables
Create a .env file in both the client and server directories. Use .env.example as a guide to set required variables like MongoDB URI, JWT secrets, etc.

4. Start the Application (Dev Mode)
bash
Copy
Edit
# Start backend
cd server
npm run dev

# Start frontend in separate terminal
cd client
npm start
Visit your app at http://localhost:3000

🔐 Admin Access
Register as a student or instructor.

In MongoDB, open the users collection and change your user’s accountType to "Admin".

Log in again and you'll have access to the Admin Panel.

🧠 Notes
This project is created for learning purposes.

You can customize and extend it for your own academic or personal use.

Backend code is located in the server folder.

Create categories (e.g. Web Dev, Python) before uploading any course. You must be an Admin to create categories.

👤 Author
Dakssh Dixit
GitHub: @DaksshDixit








