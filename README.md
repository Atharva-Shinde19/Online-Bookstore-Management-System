# 📚 Online Bookstore Management System

An **Online Bookstore Management System** built using **Java Spring Boot**, **MySQL**, and **Thymeleaf**.  
This project allows users to browse books, manage carts, place orders, and make payments, while providing admin functionalities for managing the bookstore.

---

## 🚀 Features

### 👤 User Features
- User Registration & Login (Spring Security)
- Browse and search books
- Add books to cart
- Place orders
- Payment processing
- View order history

### 🛠 Admin Features
- Add, update, and delete books
- Manage orders
- View users and payments

---

## 🏗 Project Architecture

- **Architecture Pattern:** MVC (Model–View–Controller)
- **Backend:** Spring Boot
- **Frontend:** Thymeleaf
- **Database:** MySQL
- **ORM:** Spring Data JPA (Hibernate)
- **Security:** Spring Security
- **Build Tool:** Maven

---

## 📁 Project Structure
```
online-bookstore-system
│
├── src/main/java/com/bookstore
│ ├── OnlineBookstoreApplication.java
│ │
│ ├── config
│ │ └── SecurityConfig.java
│ │
│ ├── controller
│ │ ├── AuthController.java
│ │ ├── BookController.java
│ │ ├── CartController.java
│ │ ├── OrderController.java
│ │ └── PaymentController.java
│ │
│ ├── model
│ │ ├── User.java
│ │ ├── Book.java
│ │ ├── Cart.java
│ │ ├── Order.java
│ │ └── Payment.java
│ │
│ ├── repository
│ │ ├── UserRepository.java
│ │ ├── BookRepository.java
│ │ ├── CartRepository.java
│ │ ├── OrderRepository.java
│ │ └── PaymentRepository.java
│ │
│ └── service
│ ├── UserService.java
│ ├── BookService.java
│ ├── CartService.java
│ ├── OrderService.java
│ └── PaymentService.java
│
├── src/main/resources
│ ├── static
│ ├── templates
│ └── application.properties
│
├── pom.xml
└── README.md
```


---

## 🗄 Database Design

### Tables
- `users`
- `books`
- `cart`
- `orders`
- `payments`

Hibernate automatically creates tables using JPA annotations.

---

## ⚙️ Configuration

### 1️⃣ Create MySQL Database
```sql
CREATE DATABASE bookstore_db;
```


## 📌 Future Enhancements

- REST API + React frontend

- JWT authentication

- Payment gateway integration (Razorpay / Stripe)

- Book recommendation system

- PDF invoice generation

- Order tracking system



