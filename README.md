# Task Manager (TaskQue) Using MERN

## 📋 Project Description

This is a React-based **Task Management Application** that allows users to:

- User Authentication with **JWT**
- View all tasks with filters by status (All, Pending, In Progress, Completed)
- Edit task title, description, priority, status, and due date
- Delete existing tasks 
- Paginate through the task list with a user-friendly UI
- Get real-time toast notifications for successful or failed operations
- Responsive and accessible UI using **Material UI**


The app uses:
- **React** for frontend components
- **Redux Toolkit** for global state management
- **MUI (Material-UI)** for UI components and styling
- **Toastify** for feedback messages
- **Thunks** for asynchronous task operations (CRUD)

## Task Summery 
**Sample Video**


https://github.com/user-attachments/assets/c3c60872-23e9-44a0-8205-ba81492709d2


## ⚙️ Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/task-management-app.git
   cd task-management-app
2. **setup frontend**
   ```bash
   cd frontend
   npm install
   npm run dev
3. **setup backend**
   ```bash
   cd backend
   npm install

   **create .env file**
   
   PORT=5000
   MONGO_DB_URL=mongodb://example.in
   JWT_SECRET=example_secret_key
4. **run backend**
   ```bash
   npm start
