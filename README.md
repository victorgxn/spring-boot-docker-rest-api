# Spring Boot CRUD Application with JPA, Docker, and PostgreSQL

This is a simple Spring Boot application that demonstrates CRUD (Create, Read, Update, Delete) operations using JPA (Java Persistence API) for database interaction, Docker for containerization PostgreSQL as the database.

<img src='./readme/spring-boot-docker.jpg' width="100%" alt="imagen readme" />

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd api-rest
   ```
3. Build the project:
   ```bash
   mvn clean install
   ```
4. Run the application using Docker:
   ```bash
   docker-compose up -d
   ```

## Configuration

The application uses `.env` for configuration. You can customize the database connection details.

## Features

- CRUD operations for entities
- Dockerized PostgreSQL for easy deployment

## API Endpoints

- `GET http://localhost:8080/productos`: Retrieve all products
- `POST http://localhost:8080/productos`: Create a new products
- `GET http://localhost:8080/productos/{id}`: Retrieve a products by ID
- `PUT http://localhost:8080/productos/{id}`: Update a products by ID
- `DELETE http://localhost:8080/productos/{id}`: Delete a products by ID
