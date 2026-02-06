# Spring Boot Movie API

A simple Java Spring Boot backend application that implements RESTful APIs
for managing a collection of movies. This project was built as part of a
technical sample task.

---

## 🚀 Features

- Add a new movie (POST API)
- Fetch a movie by ID (GET API)
- In-memory data storage using ArrayList
- RESTful API design with proper HTTP responses
- Built using Spring Boot and Java 21

---

## 🛠️ Tech Stack

- Java 21
- Spring Boot 3
- Maven
- Embedded Tomcat Server

---

## 📂 Project Structure

src/main/java/com/example/demo
├─ DemoApplication.java
├─ controller
│ └─ MovieController.java
├─ service
│ └─ MovieService.java
└─ model
└─ Movie.java


---

## ▶️ How to Run the Application

### Prerequisites
- Java 21 installed
- Maven or Maven Wrapper

### Steps
```bash
git clone https://github.com/bolisettypoojitha/spring-boot-movie-api.git
cd spring-boot-movie-api
./mvnw spring-boot:run
## Live API
Base URL: https://spring-boot-movie-api.onrender.com

### POST /api/movies
Creates a new movie

### GET /api/movies/{id}
Fetch movie by ID


