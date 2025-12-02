# 🎯 EduQuest - Spring Boot + MySQL

A backend REST API for a Quiz Application built using Spring Boot and MySQL. It allows users to create quizzes, fetch questions based on category, submit answers, and receive scores.

---

## 📦 Tech Stack

- Java 17
- Spring Boot 3.x
- Spring Data JPA
- MySQL
- Maven
- Postman (for API testing)

---

## 🔧 Features

- Add, update, delete questions
- Get questions by category
- Create quizzes with random questions
- Fetch quiz questions for users (without answers)
- Submit quiz and receive total score
- Proper error handling with HTTP status codes

---

## ⚙️ Configuration

### Database Setup

1. Create a MySQL database:
   ```sql
   CREATE DATABASE questiondb;
   ```

2. Set the required environment variables before running the application:
   ```bash
   export DB_USERNAME=your_username
   export DB_PASSWORD=your_password
   # Optional: override the default database URL
   export DB_URL=jdbc:mysql://localhost:3306/questiondb
   ```

3. Alternatively, you can set these in your IDE's run configuration or create a local properties file.

### Running the Application

```bash
./mvnw spring-boot:run
```

---
