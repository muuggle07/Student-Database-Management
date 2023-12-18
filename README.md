# Spring Boot Student Management System

A comprehensive Spring Boot application for managing student details using Servlets, JSP, MVC, and MySQL.

## Features

- **CRUD Operations:** Add, view, update, and delete student records with ease.
- **MVC Architecture:** Ensures a clean separation of concerns for better maintainability.
- **Spring Boot:** Simplifies development with auto-configuration and embedded servers.
- **MySQL Database:** Stores student information securely.

## Screenshots

### Home Page
![Home Page](screenshots/home.png)

### Add Student
![Add Student](screenshots/register.png)

### View Students
![View Students](screenshots/display.png)

### Update Student
![Update Student](screenshots/update.png)

### Delete Student
![Delete Student](screenshots/delete.png)

## How to Run

1. Clone the repository to your local machine.
2. Set up a MySQL database and configure connection details in `application.properties`.
3. Build the project using Maven.
4. Run the Spring Boot application.
5. Access the application through the provided URL.

## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/spring-boot-student-management.git

# Navigate to the project directory
cd spring-boot-student-management

# Build the project
mvn clean install

# Run the application
java -jar target/spring-boot-student-management.jar
