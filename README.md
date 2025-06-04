# Spring Boot Demo Application

A simple Spring Boot application with Docker support.

## Prerequisites

- Java 21
- Maven
- Docker

## Building the Application

To build the application, run:

```bash
mvn clean package
```

## Docker

### Building the Docker Image

To build the Docker image, run:

```bash
docker build -t spring-boot-demo .
```

### Running the Docker Container

To run the Docker container, execute:

```bash
docker run -p 8080:8080 spring-boot-demo
```

The application will be accessible at http://localhost:8080/hello

## API Endpoints

- GET `/hello`: Returns "Hello World"
