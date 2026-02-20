# SpringDeptManager

A full-stack CRUD web application built using **Spring Boot**, **MySQL**, and **HTML/JavaScript**.

This project demonstrates backend development, database integration, REST APIs, and frontend connectivity.


## Features

-  Add new students
-  View all students
-  Delete students
-  Update student details
-  MySQL database integration
-  REST API endpoints
-  Simple frontend using HTML + JavaScript


##  Tech Stack

- Java 17+
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- HTML, CSS, JavaScript


##  Project Structure
src
└── main
├── java/com/example/demo
│ ├── Controller
│ ├── Entity
│ ├── Repository
│ └── DemoApplication
└── resources
├── static (Frontend files)
└── application.properties


## Setup Instructions

###  Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

Configure MySQL

CREATE DATABASE Database name;

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/demo
spring.datasource.username=your_username
spring.datasource.password=your_password

Run the Application using maven wrapper

./mvnw spring-boot:run

Access Application:
http://localhost:8080

API Endpoints
Method	  Endpoint	      Description
GET	    /students	      Get all students
GET	    /students/{id}	Get student by ID
POST	  /students	      Add new student
DELETE	/students/{id}	Delete student

Learning Outcomes

1.Understanding REST APIs

2. Connecting Spring Boot to MySQL

3. Performing CRUD operations

4. Building basic frontend

5. Version control using Git & GitHub
