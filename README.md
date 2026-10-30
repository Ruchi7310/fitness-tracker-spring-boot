
# Fitness Tracker – Spring Boot Backend

A backend application built with Java and Spring Boot to help users manage fitness activities, track their progress, and receive personalized recommendations.

## Features

- **User Authentication:** User registration and login.
- **JWT Authentication:** Secure API access using JSON Web Tokens.
- **Spring Security:** Role-based access control.
- **Activity Tracking:** Create and manage fitness activities.
- **Fitness Recommendations:** Generate recommendations based on activity information.
- **Database Integration:** Persist user and activity data using PostgreSQL.
- **API Documentation:** OpenAPI/Swagger integration.
- **Exception Handling:** Centralized global exception handling.

## Tech Stack

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- PostgreSQL
- JWT
- Maven
- Swagger / OpenAPI
- Docker

## Project Structure

```text
src/main/java/com/project/fitness/
├── config/
├── controller/
├── dto/
├── exceptions/
├── model/
├── repository/
├── security/
└── service/
```

## Getting Started

### Prerequisites

- Java 21 or later
- PostgreSQL
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Ruchi7310/fitness-tracker-spring-boot.git
```

### 2. Open the project

```bash
cd fitness-tracker-spring-boot
```

### 3. Configure the database

Create a PostgreSQL database and configure the database URL, username, password, and JWT secret using the application's configuration or environment variables.

### 4. Run the application

On Windows:

```bash
.\mvnw.cmd spring-boot:run
```

On macOS/Linux:

```bash
./mvnw spring-boot:run
```

## API Documentation

When the application is running, access the Swagger UI (if enabled):

```text
http://localhost:8080/swagger-ui/index.html
```

## Author

**Ruchi Chaudhary**

GitHub: [Ruchi7310](https://github.com/Ruchi7310)
