# Employee Management System (Angular + Spring Boot)

A full-stack CRUD app for managing employee data with a modern, mobile-responsive design.

---

## Technologies

**Frontend:**

* Angular 12, Bootstrap 4, TypeScript, HTML5, CSS3, RxJS, Angular HTTP Client

**Backend:**

* Spring Boot 2.x, Spring Data JPA, Spring Web, Hibernate, MySQL/H2, Maven 3.2+, Java JDK 1.8+

---

## Features

* Full CRUD operations
* Responsive, mobile-first design
* Auto-generated Project IDs
* RESTful API with clean architecture
* Employee fields: First Name, Last Name, Email, Age, Gender, Project ID

---

## Setup

**Frontend:**

1. `cd angular-frontend`
2. `npm install`
3. `npm start` (or `ng serve`)
4. Runs on `http://localhost:4200`

**Backend:**

1. `cd springboot-backend`
2. `mvn clean install`
3. `mvn spring-boot:run`
4. API at `http://localhost:8080/api/v1/employees`

---

## Database

**H2 (default):** In-memory, resets on restart.
**MySQL:**

* Create database: `employee_management`
* Update `application.properties` with your DB credentials.

---

## API Endpoints

| Method | Endpoint               | Description         |
| ------ | ---------------------- | ------------------- |
| GET    | /api/v1/employees      | Get all employees   |
| GET    | /api/v1/employees/{id} | Get employee by ID  |
| POST   | /api/v1/employees      | Create new employee |
| PUT    | /api/v1/employees/{id} | Update employee     |
| DELETE | /api/v1/employees/{id} | Delete employee     |
