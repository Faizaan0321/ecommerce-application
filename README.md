
#  E-Commerce Application (Full Stack)

A full-stack **E-Commerce web application** built using **Spring Boot** for the backend and a **JavaScript-based frontend**, following RESTful architecture and clean project structure.
The project focuses on real-world e-commerce features such as product management, cart handling, and order processing.

---

##  Features

### Backend (Spring Boot)

* RESTful APIs for e-commerce operations
* Product management (CRUD)
* User and order handling
* Cart functionality
* Layered architecture (Controller → Service → Repository)
* MySQL database integration using Spring Data JPA
* Exception handling and validation

### Frontend

* JavaScript-based UI
* Product listing and interaction
* API integration with backend services
* Modular frontend structure

---

##  Project Structure

```
ecommerce-application/
│
├── backend eCommersApp/      # Spring Boot backend
│   ├── src/main/java
│   ├── src/main/resources
│   └── pom.xml
│
├── frontend/                 # Frontend application
│
├── docs/                     # API docs / ER diagram
├── screenshots/              # Application screenshots
│
├── README.md
├── package.json
└── package-lock.json
```

---

##  Tech Stack

### Backend

* Java 17
* Spring Boot
* Spring Data JPA (Hibernate)
* MySQL
* Maven
* REST APIs

### Frontend

* JavaScript
* HTML, CSS
* API-based integration

### Tools

* Git & GitHub
* VS Code / IntelliJ IDEA
* Postman (API testing)

---

##  System Architecture

```
Client (Frontend / Postman)
        |
        v
REST Controllers
        |
        v
Service Layer
        |
        v
Repository Layer (JPA)
        |
        v
MySQL Database
```

---

##  How to Run the Project

### Backend

1. Configure MySQL database in `application.properties`
2. Navigate to backend folder:

   ```bash
   cd backend eCommersApp
   ```
3. Run the application:

   ```bash
   mvn spring-boot:run
   ```

### Frontend

1. Navigate to frontend folder:

   ```bash
   cd frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start frontend:

   ```bash
   npm start
   ```

---

##  API Testing

* APIs can be tested using **Postman**
* Endpoint screenshots are available inside the `screenshots/` folder

---

##  Learning Outcomes

* Hands-on experience with Spring Boot REST APIs
* Understanding of full-stack application flow
* Clean code structure and best practices
* Database integration using JPA
* Real-world project organization

---

##  Author

**Faizaan Khan**
GitHub: [https://github.com/Faizaan0321](https://github.com/Faizaan0321)

---

##  License

This project is created for **learning and portfolio purposes**.

---


