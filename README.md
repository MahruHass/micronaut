# Micronaut

A simple dummy project built with the **Micronaut Framework** for testing, learning, and experimentation.

## Overview

**Dummy Micronaut Test Project** is a lightweight JVM application demonstrating the basic structure and features of a Micronaut application.

The project includes examples of:

- Dependency Injection
- Inversion of Control (IoC)
- HTTP Controllers
- Service Classes
- Application Configuration
- Unit Testing
- Integration Testing
- Gradle-based builds

> **Note:** This is a fictional/demo project created for testing and educational purposes. It is not intended for production use.

## Technologies

- Java
- Micronaut Framework
- Gradle
- JUnit
- HTTP/REST

## Project Structure

```text
dummy-micronaut-test/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── example/
│   │   │       ├── Application.java
│   │   │       ├── controller/
│   │   │       │   └── HelloController.java
│   │   │       └── service/
│   │   │           └── HelloService.java
│   │   │
│   │   └── resources/
│   │       └── application.yml
│   │
│   └── test/
│       └── java/
│           └── example/
│               └── HelloControllerTest.java
│
├── build.gradle
├── gradlew
├── gradlew.bat
├── settings.gradle
└── README.md
