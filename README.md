# FirstDemo - Spring Boot Hello World Application

## Overview

FirstDemo is a simple Spring Boot application developed to understand the fundamentals of Spring Boot, REST APIs, and embedded Tomcat server configuration.

The application exposes a REST endpoint that returns a simple "Hello World!" response.

---

## Technologies Used

* Java 21
* Spring Boot 3.5.14
* Maven
* Embedded Tomcat
* Spring Web

---

## Project Structure

```text
src
├── main
│   ├── java
│   │   └── com.HelloWorld.FirstDemo
│   │       └── FirstDemoApplication.java
│   └── resources
│       └── application.properties
└── test
```

---

## Application Code

The application contains:

* `@SpringBootApplication`
* `@RestController`
* `@GetMapping`

### REST Endpoint

```java
@GetMapping("/hello")
public String helloWorld() {
    return "Hello World!";
}
```

---

## API Details

### Get Hello World Message

**Request**

```http
GET /hello
```

**URL**

```text
http://localhost:9090/hello
```

**Response**

```text
Hello World!
```

---

## Running the Application

### Clone Repository

```bash
git clone <repository-url>
```

### Navigate to Project

```bash
cd FirstDemo
```

### Run Application

```bash
mvn spring-boot:run
```

or

Run the `FirstDemoApplication` class directly from IntelliJ IDEA.

---

## Verify Application

Open your browser:

```text
http://localhost:9090/hello
```

Expected Output:

```text
Hello World!
```

---

## Learning Objectives

This project demonstrates:

* Spring Boot Project Setup
* REST Controller Creation
* Request Mapping using @GetMapping
* Embedded Tomcat Server
* Maven Dependency Management
* Running Spring Boot Applications
* Git & GitHub Integration

---

## Future Enhancements

* Add Employee CRUD APIs
* Integrate MySQL Database
* Use Spring Data JPA
* Add Validation
* Add Exception Handling
* Implement Spring Security
* Dockerize Application

---

## Author

Kalyani

Java Full Stack Developer
