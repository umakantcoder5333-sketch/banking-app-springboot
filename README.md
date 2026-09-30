# 🏦 Banking App - Spring Boot

A Banking REST API built using Java, Spring Boot, Spring Data JPA,
Hibernate, and MySQL.

## 🚀 Features

- Create a bank account
- Get account by ID
- Get all accounts
- Deposit money
- Withdraw money
- Delete account
- Exception handling
- Global exception handling
- RESTful APIs
- MySQL database integration

## 🛠️ Tech Stack

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Postman
- IntelliJ IDEA

## 🏗️ Project Architecture

The application follows a layered architecture:

Controller → Service → Repository → Database

DTO and Mapper are used for transferring and converting data,
while the Exception package handles application errors.

## 📂 Project Structure

```text
banking-app
│
├── .mvn
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── net.javaguides.banking_app
│   │   │       │
│   │   │       ├── controller
│   │   │       │   └── AccountController
│   │   │       │
│   │   │       ├── dto
│   │   │       │   └── AccountDto
│   │   │       │
│   │   │       ├── entity
│   │   │       │   └── Account
│   │   │       │
│   │   │       ├── exception
│   │   │       │   ├── AccountException
│   │   │       │   ├── ErrorDetails
│   │   │       │   └── GlobalExceptionHandler
│   │   │       │
│   │   │       ├── mapper
│   │   │       │   └── AccountMapper
│   │   │       │
│   │   │       ├── repository
│   │   │       │   └── AccountRepository
│   │   │       │
│   │   │       ├── service
│   │   │       │   ├── impl
│   │   │       │   │   └── AccountServiceImpl
│   │   │       │   └── AccountService
│   │   │       │
│   │   │       └── BankingAppApplication
│   │   │
│   │   └── resources
│   │
│   └── test
│
├── pom.xml
├── mvnw
└── mvnw.cmd
