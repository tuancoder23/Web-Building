# Web Building Management System

A web-based real estate and building management system developed with Java Spring Boot.

The application is designed to support building management, customer management,
staff assignment, transaction management, user administration and role-based access control.

---

## Features

### Building Management

- View building list
- Search and filter buildings
- Add and update building information
- Manage rental areas
- Assign buildings to staff
- Filter building data based on assigned staff

### Customer Management

- View customer list
- Search customers
- Manage customer information
- Assign customers to staff
- Manage customer-related transactions

### User Management

- Manage system users
- Manage user roles
- Change user password
- Staff management

### Authentication & Authorization

The application uses Spring Security for authentication and authorization.

Supported roles include:

- `MANAGER`
- `STAFF`

Access to administrative resources is controlled according to the authenticated
user's role.

Passwords are encrypted using BCrypt.

### Transaction Management

- Manage customer transactions
- Store transaction history
- Support different transaction types

### Email Service

The project includes email sending functionality using Spring Mail.

---

## Technology Stack

### Backend

- Java 8
- Spring Boot 2.0.9
- Spring MVC
- Spring Data JPA
- Spring Security
- Hibernate
- Spring Validation
- Spring Mail

### Database

- MySQL

### Frontend

- JSP
- JSTL
- SiteMesh
- DisplayTag
- HTML
- CSS
- JavaScript

### Other Libraries

- ModelMapper
- Apache Commons Lang
- Log4j

### Build Tool

- Maven

---

## Architecture

The project follows a layered architecture:

```text
Controller / API
       ↓
    Service
       ↓
  Repository
       ↓
     Entity
       ↓
     MySQL
