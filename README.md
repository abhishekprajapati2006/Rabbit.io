# 📚 Learning Management System (LMS) Project Documentation
<img width="659" alt="Screenshot 2025-02-08 112741" src="https://github.com/user-attachments/assets/e71547af-c9e0-44fb-8d82-4c0f2aa1903b" />

##  🌐 Project Overview
This **Learning Management System (LMS)** is a web application designed to streamline the management of online learning activities. It provides users with features like course enrollment, progress tracking, and course content management, making education more accessible and efficient.

## ✨ Key Features
- 🔒 **User Authentication**: Secure login and sign-up.
- 🔑 **Role-Based Access Control**: Separate functionalities for Admin, Instructor, and Student roles.
- 📋 **Course Management**: Create, update, delete, and view courses.
- 📊 **User Dashboard**: Track progress and performance.
- 📝 **Assignment System**: Upload and grading functionalities.
- 🔔 **Notifications**: Stay updated with important alerts.

## 🛠️ Technology Stack
### 🌐 Frontend:
- **Framework**: React.js
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **Routing**: React Router

### ⚙️ Backend:
- **Framework**: Node.js with Express.js
- **Database**: MongoDB with Mongoose ORM
- **Authentication**: JSON Web Tokens (JWT)

### 📂 Additional Tools:
- **Version Control**: Git and GitHub
- **Project Management**: Trello/Asana

## 📋 Prerequisites
- **Node.js** and **npm** installed
- **MongoDB** set up and running
- Basic knowledge of JavaScript and React

## ⚡ Setup Instructions
1. 📥 **Clone** the repository from GitHub.
2. Navigate to the project directory and install dependencies:
   ```bash
   npm install
   ```
3. 🛠️ Configure environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_secret_key
   ```
4. 🚀 Start the development server:
   ```bash
   npm run dev
   ```
5. 🌐 Access the application at `http://localhost:3000`.

## 🧪 Testing
- 🛡️ **Run unit tests** for backend APIs using Jest:
  ```bash
  npm test
  ```
- 🖥️ Perform manual testing through Postman or the frontend interface.

## 🌍 Deployment
- 🌟 **Frontend** hosted on Vercel
- ☁️ **Backend** hosted on Vercel
- 💾 **Database** hosted on MongoDB Atlas.

## 👥 Roles and Responsibilities
- **🛡️ Admin**: Manage users and courses, view analytics.
- **👩‍🏫 Instructor**: Create and manage courses, grade assignments.
- **👨‍🎓 Student**: Enroll in courses, complete assignments, and track progress.

## 🤔 Challenges Faced
- 🔐 Implementing secure role-based access control.
- 📱 Ensuring responsive design across devices.
- ⚡ Optimizing backend for scalability and performance.

## 🚀 Future Enhancements
- 🎥 Integration with third-party services like Zoom for live classes.
- 🌎 Support for multiple languages.
- 🤖 AI-based recommendations for personalized learning paths.


## Some Screenshots This Rabbit.io Project

- # 📈 Admin DashBoard 
- ![image](https://github.com/user-attachments/assets/0bbc85ee-14a3-402c-92eb-da59fbb83f81)
- # 🗃️ Create Courses
- ![image](https://github.com/user-attachments/assets/e742b40a-4100-4dcb-a315-f7dcc92bfdbb)
- # ⚙️ Edit Courses
- ![Screenshot 2025-02-08 113829](https://github.com/user-attachments/assets/632d1bd1-c878-403c-8af1-c1e06790046d)
- # 📹 Create Lectures 
- ![Screenshot 2025-02-08 113909](https://github.com/user-attachments/assets/b78de1a2-5851-4ec6-be7e-bb539b3043fd)
- # 🎞️ Edit Lectures
- ![Screenshot 2025-02-08 113919](https://github.com/user-attachments/assets/9260f8d2-9976-4b2d-aacc-f9948bde97ce)




