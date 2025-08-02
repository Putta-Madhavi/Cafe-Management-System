# ☕ Cafe Management System

A full-stack Cafe Management System built using **Angular**, **Spring Boot**, and **MySQL**. This project manages cafe operations including product listings, order creation, user management, and PDF bill generation with secure authentication and role-based access control.

## 🚀 Tech Stack

- **Frontend**: Angular
- **Backend**: Spring Boot
- **Database**: MySQL
- **Security**: JWT (JSON Web Tokens), Role-Based Access Control
- **Others**: Email Integration, PDF Generation, REST APIs

---

## 🎬 Video Overview Summary

This project walkthrough showcases key technical implementations:

- **Angular frontend** on `localhost:4200`
- **Spring Boot backend** on `localhost:8081`
- MySQL as the database for users, orders, products, and categories

The video walks through user flows, including signup/login, admin approval, dashboard overview, bill generation, and email notifications. It highlights API integration, session management, validation, and real-time UI feedback.

---

## 🔑 Key Features

### 👥 User Management
- Signup with validations (email, phone, password)
- Admin approval system before login is enabled
- Forgot password with email integration
- Change password with validation

### 🔐 Authentication & Authorization
- Secure login with **JWT-based authentication**
- Role-based access: Admin vs Regular user
- Route guards and protected backend APIs

### 📊 Dashboard
- Real-time data display for:
  - Total categories
  - Total products
  - Total bills

### 🗂️ Category & Product Management
- Add, update, delete categories
- Add, filter, and manage products with dynamic validations
- Enable/disable product status

### 🧾 Order & Bill Generation
- Create orders with validated quantities and dynamic billing
- Generate and download **PDF bills**
- View previous bills; prevent duplicate generation
- Delete bills with full cleanup (database + server)

### 📧 Email Integration
- Send HTML emails for:
  - Password recovery
  - User activation/deactivation
- Email notifications include admin details and user actions

### 🛡️ Security Features
- JWT token validation and expiration handling
- Token inspection using jwt.io
- Prevent tampering with exception handling and redirection
- Role checks via token decoding


