# Employee Management REST API

A Spring Boot CRUD REST API for Employee Management using Spring Web, Spring Data JPA, Validation, and H2 Database.

## Features

- Create Employee
- Get All Employees
- Get Employee By ID
- Update Employee
- Delete Employee
- Input Validation
- RESTful API Design

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

## API Endpoints

| Method | Endpoint | Description |
|----------|----------|-------------|
| POST | /api/employees | Create Employee |
| GET | /api/employees | Get All Employees |
| GET | /api/employees/{id} | Get Employee By ID |
| PUT | /api/employees/{id} | Update Employee |
| DELETE | /api/employees/{id} | Delete Employee |

## Sample Request

```json
{
  "name": "Dheepika",
  "email": "dheepika@gmail.com",
  "department": "IT"
}
```

## Author

Dheepika Lankalapalli
