# Employee Management API

A RESTful Employee Management API built with Java and Spring Boot.

## Technologies Used

- Java 8
- Spring Boot 2.7.18
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST API
- Swagger / OpenAPI
- Postman

## Features

- Create an employee
- Get all employees
- Get an employee by ID
- Update an employee
- Delete an employee
- Input validation
- Global exception handling
- MySQL database integration
- Swagger API documentation

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/employees` | Get all employees |
| GET | `/employees/{id}` | Get employee by ID |
| POST | `/employees` | Create employee |
| PUT | `/employees/{id}` | Update employee |
| DELETE | `/employees/{id}` | Delete employee |

## Employee Fields

- ID
- First Name
- Last Name
- Email
- Department
- Position

## Running the Application

1. Configure MySQL.
2. Set the `DB_PASSWORD` environment variable.
3. Run `EmployeeManagementApiApplication`.
4. The API runs on port 8082.

## Swagger Documentation

When the application is running, open:

`http://localhost:8082/swagger-ui.html`

## Validation

The API validates employee information before saving it.

Invalid requests return a 400 Bad Request response.

## Author

**Sabina Adaku Okpala**

Java Developer | Database Administrator | Software Development

[LinkedIn](https://www.linkedin.com/in/sabina-okpala-935067211)