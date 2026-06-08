# HotelRatingSystem
project by using microservices 
A scalable and fault-tolerant microservices-based application built using Spring Boot and Spring Cloud. The system manages users, hotels, and ratings through independently deployable services while leveraging modern cloud-native patterns.

🚀 Features
Microservices Architecture
User Service
Hotel Service
Rating Service
Service Discovery
Eureka Server for dynamic service registration and discovery.
Inter-Service Communication
OpenFeign Client for declarative REST communication between microservices.
Client-Side Load Balancing
Spring Cloud LoadBalancer for distributing requests across service instances.
API Gateway
Centralized routing and request handling using Spring Cloud Gateway.
Rate Limiting
Request throttling to prevent abuse and improve system stability.
Fault Tolerance
Resilience4j Circuit Breaker
Retry Mechanism
Fallback Methods
Database Integration
MySQL for User and Hotel services.
MongoDB for Rating service.
Distributed Configuration
Centralized configuration management.
RESTful APIs
CRUD operations for Users, Hotels, and Ratings.
Logging & Monitoring
Centralized logging support.
Actuator endpoints for health monitoring.
🛠️ Tech Stack
Java 21
Spring Boot 3.x
Spring Cloud
Spring Cloud Gateway
Netflix Eureka
OpenFeign
Spring Cloud LoadBalancer
Resilience4j
MySQL
MongoDB
Maven
REST API
Hibernate / JPA
Lombok
📌 Architecture Flow
Client sends request to API Gateway.
Gateway routes request to appropriate microservice.
Services register themselves with Eureka Server.
OpenFeign communicates between services.
LoadBalancer distributes requests among service instances.
Resilience4j handles failures using Circuit Breaker and Retry.
Rate Limiter controls excessive traffic.
Data is persisted in MySQL and MongoDB databases.
🎯 Learning Outcomes

This project demonstrates:

Microservices Design Principles
Service Discovery & Registration
API Gateway Pattern
Distributed System Communication
Fault Tolerance Strategies
Load Balancing Techniques
Rate Limiting Implementation
Database Per Service Pattern
Cloud-Native Application Development
