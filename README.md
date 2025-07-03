#  Tasks REST API – Spring Boot Application

A simple yet scalable Task Management REST API built using Spring Boot, designed to perform CRUD operations on tasks. This project demonstrates best practices in backend development, including RESTful API design, Spring Boot framework usage, JPA for persistence, and structured project setup.

##  Features

- Create, Read, Update, and Delete (CRUD) tasks
- RESTful API endpoints with proper HTTP methods
- JPA/Hibernate for object-relational mapping
- MySQL as the relational database
- Input validation and error handling
- Basic exception management
- Swagger UI for API documentation

##  Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Swagger (OpenAPI)
- Postman (for API testing)

##  Project Structure

tasks-rest-api/
├── src/
│ ├── main/
│ │ ├── java/com/example/tasks/
│ │ │ ├── controller/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ └── service/
│ │ └── resources/
│ │ └── application.properties
├── pom.xml
└── README.md


##  API Endpoints

| Method | Endpoint          | Description           |
|--------|-------------------|-----------------------|
| GET    | `/api/tasks`      | Get all tasks         |
| GET    | `/api/tasks/{id}` | Get task by ID        |
| POST   | `/api/tasks`      | Create new task       |
| PUT    | `/api/tasks/{id}` | Update task by ID     |
| DELETE | `/api/tasks/{id}` | Delete task by ID     |

##  How to Run Locally

### Prerequisites

- Java 17+
- Maven
- MySQL (or configure another DB)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ganesh9828/tasks-rest-api.git
   cd tasks-rest-api












