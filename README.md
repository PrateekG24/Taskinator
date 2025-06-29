
# 🚀 Taskinator - Task Management Application

  

A modern, full-stack task management application built with React, Node.js, and MongoDB. Taskinator helps you organize, prioritize, and track your tasks with an intuitive interface and powerful features.

  


  

## ✨ Features

  

### 🎯 Core Functionality

  

-  **Task Management**: Create, edit, delete, and organize tasks

-  **Priority Levels**: Set Low, Medium, or High priority for tasks

-  **Due Date Tracking**: Set and manage task deadlines

-  **Status Management**: Mark tasks as completed or in progress

-  **Real-time Updates**: Instant task synchronization across the application

  

### 📊 Dashboard & Analytics

  

-  **Task Overview**: Comprehensive dashboard with task statistics

-  **Progress Tracking**: Visual progress bars and completion rates

-  **Filtering Options**: Filter tasks by date, priority, and status

-  **Recent Activity**: View latest task updates and changes

  

### 🔐 User Management

  

-  **User Authentication**: Secure login and registration system

-  **Profile Management**: Update user profile and password

-  **JWT Authentication**: Secure token-based authentication

-  **User-specific Tasks**: Each user sees only their own tasks

  

### 🎨 Modern UI/UX

  

-  **Responsive Design**: Works seamlessly on desktop, tablet, and mobile

-  **Material-UI Components**: Beautiful, consistent interface design

-  **Dark/Light Theme Support**: Customizable appearance

-  **Intuitive Navigation**: Easy-to-use sidebar and navigation

-  **Toast Notifications**: User-friendly feedback and alerts

  

  


  

### Dashboard Features

  

-  **Task Overview**: See all your tasks in one place

-  **Statistics Panel**: Track total, completed, and pending tasks

-  **Progress Bar**: Visual representation of your completion rate

-  **Recent Activity**: View your latest task updates

  
   

## 🏗️ Project Structure

  

```

taskinator/

├── backend/

│ ├── config/

│ │ └── db.js # Database configuration

│ │ ├── controllers/

│ │ │ ├── taskController.js # Task CRUD operations

│ │ │ └── userController.js # User authentication

│ │ ├── middleware/

│ │ │ └── auth.js # JWT authentication middleware

│ │ ├── models/

│ │ │ ├── taskModel.js # Task schema

│ │ │ └── userModel.js # User schema

│ │ ├── routes/

│ │ │ ├── taskRoute.js # Task API routes

│ │ │ └── userRoute.js # User API routes

│ │ ├── server.js # Express server setup

│ │ └── package.json

├── frontend/

│ ├── src/

│ │ ├── components/

│ │ │ ├── AddTask.jsx # Task creation/editing modal

│ │ │ ├── Layout.jsx # Main layout component

│ │ │ ├── Login.jsx # Login form

│ │ │ ├── Navbar.jsx # Navigation bar

│ │ │ ├── Sidebar.jsx # Sidebar navigation

│ │ │ ├── SignUp.jsx # Registration form

│ │ │ └── TaskItem.jsx # Individual task component

│ │ ├── pages/

│ │ │ ├── Dashboard.jsx # Main dashboard

│ │ │ ├── Pending.jsx # Pending tasks view

│ │ │ └── Complete.jsx # Completed tasks view

│ │ ├── App.jsx # Main app component

│ │ └── main.jsx # App entry point

│ └── package.json

└── README.md

```

