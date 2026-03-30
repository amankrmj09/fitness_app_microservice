# Fitness Microservice

A simple **Spring Boot** microservice built as part of the **Spring Boot Full Stack AI Microservices Project**, showcasing modern microservices architecture with **Kafka**, **Keycloak**, and **OAuth2**.

## Project Overview

This project demonstrates how to build a clean and secure fitness-related microservice using the latest Spring Boot technologies. It serves as a practical example of implementing scalable, event-driven, and well-secured microservices.

### Key Features

- RESTful APIs for fitness-related operations
- Secure authentication and authorization using **OAuth2** + **Keycloak**
- Event-driven architecture with **Apache Kafka**
- Built with modern Java and Spring Boot stack

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies & Tools](#technologies--tools)
- [Services](#services)
  - [User Service](#user-service-userserviceapplication)
- [Project Focus](#project-focus)

## Technologies & Tools

- **Java**: 25
- **Spring Boot**: 3.5.13
- **Build Tool**: Gradle 9.4.1 with **Kotlin DSL** (`build.gradle.kts`)
- **Security**: Spring Security + OAuth2 + Keycloak
- **Messaging**: Apache Kafka
- **API Documentation**: Springdoc OpenAPI / Swagger
- **Testing**: JUnit 5 + Mockito

---

## Services

### User Service (`UserServiceApplication`)

The **User Service** is a Spring Boot-based microservice responsible for managing all user-related operations within the fitness application ecosystem.

#### Responsibilities

- **User Registration** — Handles new user onboarding and account creation
- **Authentication** — Manages login flows integrated with Keycloak and OAuth2
- **Profile Management** — Supports reading and updating user profile data

## Project Focus

This microservice is built as part of the **Spring Boot Full Stack AI Microservices Project**, covering:

- Microservices architecture best practices
- Event-driven systems with Kafka
- Secure API development with Keycloak and OAuth2

---

**Built with ❤️ for modern Spring Boot microservices development.**
