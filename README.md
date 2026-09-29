Employee Management System

A backend-based Employee Management System developed using Java and Spring Boot. This application provides RESTful APIs to manage employee records efficiently, following a layered architecture and clean coding practices.

Project Overview

The Employee Management System is designed to perform essential employee management operations such as creating, retrieving, updating, and deleting employee records.

The project demonstrates practical implementation of Spring Boot, REST APIs, DTOs, exception handling, and database integration.

Technologies Used

- Language: Java
- Framework: Spring Boot
- Database: MySQL
- Build Tool: Maven
- API Testing: Postman
- IDE: IntelliJ IDEA
- Version Control: Git & GitHub

Features

- Create new employee records
- Retrieve employee details
- Update existing employee information
- Delete employee records
- RESTful API architecture
- DTO-based data transfer
- Custom exception handling
- Layered architecture
- Database integration using MySQL

Project Structure
## Project Structure

```text
EmployeeManagementSystem/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/EmployeeManagementSystem/
│   │   │       ├── controller/
│   │   │       │   └── ControllerEmployee.java
│   │   │       ├── dto/
│   │   │       │   └── DtoEmployee.java
│   │   │       ├── exception/
│   │   │       │   └── ExceptionEmployee.java
│   │   │       ├── mapper/
│   │   │       │   └── MapperEmployee.java
│   │   │       ├── model/
│   │   │       │   └── Employee.java
│   │   │       ├── repository/
│   │   │       │   └── RepositoryEmployee.java
│   │   │       ├── service/
│   │   │       │   ├── ServiceEmployee.java
│   │   │       │   └── ServiceEmployeeIn.java
│   │   │       └── EmployeeManagementSystemApplication.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│
├── .gitignore
├── pom.xml
└── README.md
```
Prerequisites

Make sure you have the following installed:

- Java JDK
- Maven
- MySQL Server
- IntelliJ IDEA or any Java IDE
- Postman

How to Run the Project

1. Clone the repository

git clone https://github.com/anish529/Employee-Management-System

2. Open the project

Open the cloned project in IntelliJ IDEA.

3. Configure the database

Create a MySQL database and update the database credentials in "src/main/resources/application.properties".

4. Build the project

mvn clean install

5. Run the application

Run "EmployeeManagementSystemApplication.java" from your IDE.

The application will start on:

http://localhost:8080

API Testing

You can test the REST APIs using Postman.

Test the available employee endpoints for:

- Creating employees
- Fetching employee records
- Updating employee details
- Deleting employees

Refer to the controller class for the exact endpoint URLs and HTTP methods.

Learning Outcomes

Through this project, I gained practical experience in:

- Building RESTful APIs using Spring Boot
- Implementing layered architecture
- Understanding dependency injection
- Working with DTOs and mapper classes
- Handling exceptions in Spring Boot
- Integrating a MySQL database
- Testing APIs using Postman
- Managing source code using Git and GitHub

Author

Anish Prajapati

B.Tech Computer Science and Engineering

"GitHub" (https://github.com/anish529)

"LinkedIn" (https://www.linkedin.com/in/anish-kumar-prajapati-9983a3336/L)

---

This project was developed as part of my journey toward becoming a Java Backend Developer.