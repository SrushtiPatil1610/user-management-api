# User Management API (Spring Boot)

## 📌 Description
A RESTful backend API built using Spring Boot to manage users with basic CRUD operations.

## 🚀 Features
- Create User (POST)
- Get All Users (GET)
- In-memory database (H2)
- REST API architecture

## 🛠 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- H2 Database

## 🔗 API Endpoints

### GET Users
GET /users

### POST User
POST /users

Example:
{
  "name": "Srushti",
  "email": "srushti@gmail.com"
}

## ▶️ How to Run
.\mvnw.cmd spring-boot:run

## 📈 Result
Backend service capable of storing and retrieving user data.
