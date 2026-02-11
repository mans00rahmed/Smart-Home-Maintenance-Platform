# 🏠 Smart Home Maintenance Platform (SHM)

## 📌 Overview

The **Smart Home Maintenance Platform (SHM)** is a cloud-native,
microservices-based system designed to manage and coordinate maintenance
operations in smart residential properties.

This platform enables efficient handling of:

-   🔧 Maintenance requests\
-   🏢 Property management\
-   👤 User management\
-   🔍 Service discovery\
-   ☁️ Cloud-native deployment

The system follows a **Microservices Architecture**, allowing each
service to be developed, deployed, and scaled independently.

------------------------------------------------------------------------

## 🏗 Architecture

The SHM platform is built using modern backend and cloud-native
technologies:

-   **Spring Boot** -- Microservice development\
-   **Spring Cloud Netflix Eureka** -- Service discovery\
-   **REST APIs** -- Inter-service communication\
-   **Maven** -- Dependency management\
-   **Cloud Deployment Ready (AWS compatible)**

Each service runs independently and registers itself with the Discovery
Server for dynamic service resolution.

------------------------------------------------------------------------

## 📦 Microservices Repositories

This repository serves as a parent overview repository.\
Each core service is maintained in its own dedicated GitHub repository:

### 1️⃣ User Service

Responsible for managing users, authentication, and user-related
operations.

🔗 https://github.com/mans00rahmed/User-Service-For-SHM

### 2️⃣ Property Service

Handles property listings, maintenance assignments, and related property
data.

🔗 https://github.com/mans00rahmed/Property-Service-For-SHM

### 3️⃣ Discovery Service

Implements Netflix Eureka Server for service registration and discovery
between microservices.

🔗 https://github.com/mans00rahmed/Discovery-Service-For-SHM

------------------------------------------------------------------------

## 🚀 System Design Principles

-   ✅ Loose Coupling\
-   ✅ High Cohesion\
-   ✅ Independent Deployment\
-   ✅ Scalability\
-   ✅ Fault Tolerance\
-   ✅ Cloud-Native Architecture

------------------------------------------------------------------------

## 🔄 How It Works

1.  All services register themselves with the **Discovery Service
    (Eureka Server)**.
2.  Services communicate using REST APIs.
3.  Each service can scale independently.
4.  The architecture supports future integration of additional services
    such as:
    -   Maintenance Service
    -   Notification Service
    -   API Gateway
    -   Monitoring & Logging

------------------------------------------------------------------------

## 📈 Future Enhancements

-   API Gateway Integration\
-   Centralized Configuration Server\
-   Docker & Kubernetes Deployment\
-   CI/CD Pipeline (Jenkins/GitHub Actions)\
-   Monitoring using Prometheus & Grafana

------------------------------------------------------------------------

## 👨‍💻 Author

Team Sigma - TUS
Microservices & Cloud Computing Enthusiast
