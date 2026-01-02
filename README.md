# Fetch & Display Todos Using Axios and React Routing

## 📌 Description
This React application fetches Todos data from a public API using Axios and displays it using React Router.
Axios logic is separated from UI components to maintain clean architecture.

## 🚀 Features
- Fetch all todos
- View individual todo details using routing
- Axios service layer abstraction
- Clean folder structure

## 📂 Folder Structure
src/
 ├── api/
 │    ├── axiosInstance.js
 │    └── todoService.js
 ├── pages/
 │    ├── TodoList.jsx
 │    └── TodoDetails.jsx
 ├── App.jsx
 ├── index.js
 └── styles.css

## 🔗 Routes
- `/` → Displays all todos
- `/todo/:id` → Displays selected todo details

## ⚙️ Technologies Used
- React
- Axios
- React Router DOM

## ▶ How to Run
1. Clone the repository
2. Run `npm install`
3. Run `npm start`
