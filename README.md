# JavaDevProjects

This repository contains Java development projects created by **Lubna**. The projects demonstrate various Java technologies and frameworks including Spring Boot REST APIs and database transaction handling.

## Projects

### 1. SnapConnect - Social Media Image Sharing Platform

A full-featured REST API application built with Spring Boot for connecting people through image sharing and social media functionality.

#### Features:
- **User Management**: Complete user registration, authentication, and profile management
- **Post Management**: Create, read, update, and delete posts with image uploads
- **Category System**: Organize posts by categories
- **File Upload**: Support for image file uploads up to 10MB
- **Database Integration**: MySQL database with JPA/Hibernate ORM
- **Exception Handling**: Global exception handling with custom error responses

#### Technologies Used:
- Spring Boot 3.x
- Spring Data JPA
- Spring Web
- MySQL Database
- Maven for dependency management
- File upload handling for images

#### Database Configuration:
- Database: `snapconnect_app_apis`
- Username: `root`
- Password: `Lubnafatima`

#### API Endpoints:
- User Controller: User management operations
- Post Controller: Post CRUD operations with image handling
- Category Controller: Category management

### 2. Simple Transaction System

A console-based Java application for handling banking transactions with ACID properties.

#### Features:
- **Transaction Management**: Handles debit and credit transactions
- **Balance Validation**: Checks sufficient balance before transactions
- **Database Transactions**: Uses database transactions with rollback capabilities
- **Connection Management**: Proper database connection handling
- **Error Handling**: Comprehensive error handling for failed transactions

#### Technologies Used:
- Core Java
- JDBC for database connectivity
- MySQL Database
- Maven for project management

#### Database Configuration:
- Database: `AccountInfo`
- Username: `root`
- Password: `Lubnafatima`

## Setup Instructions

### Prerequisites:
- Java 17 or higher
- Maven 3.6+
- MySQL 8.0+
- IDE (IntelliJ IDEA, Eclipse, or VS Code)

### For SnapConnect Application:
1. Navigate to the `SnapConnect` directory
2. Configure MySQL database connection in `src/main/resources/application.properties`
3. Create database: `CREATE DATABASE snapconnect_app_apis;`
4. Run: `./mvnw spring-boot:run`

### For Transaction System:
1. Navigate to the `TransactionSystem` directory
2. Configure database connection in `HandleTransactions.java`
3. Create database: `CREATE DATABASE AccountInfo;`
4. Create accounts table with appropriate schema
5. Compile and run `Main.java`

## Author

**Lubna** - Java Developer

## License

This project is for educational and development purposes.
