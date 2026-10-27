# Student Management System – React JS

## 📌 Project Overview

The **Student Management System** is a simple React.js web application developed as part of Experiment 12 of the Skill Development Course (Node.js / React.js / Django). The project demonstrates the implementation of multiple pages and navigation using **React Router DOM**.

The application consists of Home, Registration, Login, Contact, and About pages, providing a basic structure for a student management web application.

## 🎯 Objectives

- To develop a multi-page web application using React.js.
- To implement client-side routing using `react-router-dom`.
- To create reusable React components for different pages.
- To handle user input using React's `useState` hook.
- To understand navigation between pages without reloading the entire application.

## ✨ Features

- **Home Page:** Displays a welcome message for the Student Management System.
- **Registration Page:** Accepts the user's full name, email address, and password.
- **Login Page:** Provides input fields for email and password.
- **Contact Page:** Displays contact information.
- **About Page:** Provides a brief description of the application.
- **Navigation:** Enables movement between pages using React Router DOM.
- **Form Handling:** Uses React state to manage form inputs and basic submission interactions.

## 🛠️ Technologies Used

- **React.js** – Frontend library for building the user interface.
- **JavaScript (ES6+)** – Application logic and component functionality.
- **HTML5** – Page structure.
- **CSS3** – Styling, if configured in the project.
- **React Router DOM** – Client-side navigation.
- **Node.js and npm** – JavaScript runtime and package management tools.

## 📂 Project Structure

```text
student-management-system/
├── public/
├── src/
│   ├── components/
│   │   ├── About.js
│   │   ├── Contact.js
│   │   ├── Home.js
│   │   ├── Login.js
│   │   └── Register.js
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have the following installed:
- Node.js
- npm
- Visual Studio Code (recommended)

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Directory

```bash
cd student-management-system
```

### Step 3: Install Dependencies

```bash
npm install
npm install react-router-dom
```

### Step 4: Start the Application

```bash
npm start
```

### Step 5: Open in Browser

Visit:

```text
http://localhost:3000
```

You can navigate between the Home, Register, Login, Contact, and About pages using the navigation links.

## 🔍 How It Works

The application uses React functional components to build individual pages. The `useState` hook manages registration and login form inputs, while `react-router-dom` handles navigation between routes.

The `App.js` file defines the routes and navigation links for each page. Form submissions currently demonstrate basic client-side interactions through browser alerts.

## 🚀 Future Enhancements

- Connect the application to a backend API.
- Implement actual student registration and authentication.
- Add a database to store student information.
- Create student profile and dashboard pages.
- Improve the user interface with responsive CSS styling.
- Add form validation and error handling.

## 📚 Learning Outcomes

- Understanding React functional components.
- Using the `useState` hook for form management.
- Implementing routing with React Router DOM.
- Organizing a React application into reusable components.
- Building and running a multi-page frontend application.

## 📝 Conclusion

This project demonstrates the development of a basic multi-page Student Management System using React.js and React Router DOM. It provides a foundation for learning frontend development, component-based architecture, and client-side routing, with opportunities for future integration of backend services and database functionality.

---

**Project Type:** Academic Mini Project / Lab Experiment  
**Experiment:** 12  
**Domain:** Web Development  
**Primary Technology:** React.js

