# 🏥 PatientIQ

A **Java Spring Boot Microservices**-based patient management system designed with production-grade best practices, leveraging **Docker**, **PostgreSQL**, **Kafka**, **gRPC**, **Spring Cloud Gateway**, and **AWS LocalStack** for a modern, scalable, and cloud-native architecture.

---

## 🚀 Tech Stack

- **Java 17**, **Spring Boot**
- **Microservices Architecture** with **REST** and **gRPC**
- **PostgreSQL** for persistent storage
- **Apache Kafka** for asynchronous event-driven communication
- **Spring Cloud Gateway** for secure API routing and load balancing
- **Spring Security** for authentication & authorization (JWT-based)
- **Docker** for containerized deployment
- **AWS LocalStack** simulating ECS, RDS, MSK, and API Gateway
- **JUnit & Integration Tests** for reliability

---

## 📦 Features

### 🧩 Microservices Architecture & Scalability
- Modular services: Patient Service, Billing Service, Auth Service, Analytics Service
- REST and gRPC used strategically for inter-service communication
- Designed for scalability, maintainability, and high availability

### ⚡ Event-Driven Communication
- Apache Kafka for real-time, async messaging between microservices
- Kafka Producer in Patient Service, Kafka Consumer in Analytics Service

### 🔐 Secure API Gateway & Auth
- Auth Service using Spring Security with JWT-based Bearer Token Auth
- Gateway filters and request validation for secure routing
- Token validation, login endpoint, and user service integration

### ☁️ Cloud-Native Deployment with IaC
- Deployed to **AWS LocalStack** using **CloudFormation**
- Infrastructure includes: VPC, RDS, MSK (Kafka), ECS, and API Gateway
- Fully Dockerized microservices with testable local cloud setup

---

## 📁 Project Structure (Simplified)

