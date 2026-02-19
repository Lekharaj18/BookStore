# 📚 Bookstore Management System

A full-stack **Bookstore Management System** built using **Spring Boot (Backend)** and **React.js (Frontend)**.  
This application allows admins to manage books, users, orders, and authentication efficiently with a secure REST API.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- User registration & login
- Role-based access control (ADMIN / USER)
- Secure authentication using JWT

### 📖 Book Management
- Add new books
- Update book details
- Delete books
- View all books with pagination & sorting
- Search books by title, author, or category

### 👤 User Management
- Register users
- View user details
- Assign roles

### 🛒 Order & Cart (Optional / Extendable)
- Add books to cart
- Place orders
- View order history

### ✅ Validation & Error Handling
- Input validation using annotations
- Global exception handling
- Proper HTTP status codes

### 📄 API Documentation
- Swagger UI for testing REST APIs

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- JWT Authentication
- MySQL
- Swagger (OpenAPI)

### Frontend
- React.js
- Axios
- React Router
- HTML, CSS, JavaScript

### Tools
- Git & GitHub
- VS Code
- Postman
- MySQL Workbench

---

## 📂 Project Structure

```text
bookstore-management-system
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   ├── dto
│   ├── security
│   ├── exception
│   └── config
│
├── frontend
│   ├── components
│   ├── pages
│   ├── services
│   └── App.js
│
└── README.md

