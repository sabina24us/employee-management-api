# Employee Management API

Author: Sabina Adaku Okpala

Java Developer | Database Administrator | Software Development

A RESTful Employee Management API built with Java and Spring Boot.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST API
- Swagger / OpenAPI
- Postman
- Git & GitHub

## Features

- Create an employee
- Get all employees
- Get an employee by ID
- Update an employee
- Delete an employee
- Employee validation
- Global exception handling
- MySQL database integration
- Swagger API documentation

## API Endpoints

GET /employees - Get all employees

GET /employees/{id} - Get employee by ID

POST /employees - Create an employee

PUT /employees/{id} - Update an employee

DELETE /employees/{id} - Delete an employee

## Employee Fields

ID  
First Name  
Last Name  
Email  
Department  
Position

## Running the Application

1. Configure MySQL.
2. Set the `DB_PASSWORD` environment variable.
3. Run `EmployeeManagementApiApplication`.
4. The application runs on:

[http://localhost:8082](http://localhost:8082)

## Swagger Documentation

The API documentation is available through Swagger UI.

[Open Swagger UI](http://localhost:8082/swagger-ui.html)

## Database Security

The database password is stored using an environment variable.

spring.datasource.password=${DB_PASSWORD}

The actual database password is not stored in the GitHub repository.

## GitHub Repository

[Employee Management API](https://github.com/sabina24us/employee-management-api)
## Author

Sabina Adaku Okpala

Java Developer | Database Administrator | Software Development

[LinkedIn Profile](https://www.linkedin.com/in/sabina-okpala-935067211)