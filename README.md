# 🏗️ Microservices Architecture Project

A scalable **Microservices-based system** built using Spring Boot, designed to demonstrate service separation, service discovery, and independent deployment of services.

---

## 📌 Overview

This project implements a basic microservices architecture consisting of multiple independent services communicating with each other.

It follows the **Service-Oriented Architecture (SOA)** principles with centralized service discovery.

---

## 🧩 Services Included

### 🏢 company_server

Handles company-related operations such as company data management and business logic.

### 👤 user_server

Manages user-related operations including user creation, retrieval, and management.

### 📡 service_registry

A **Service Discovery Server** (Eureka Server) used to register and locate microservices dynamically.

---

## ⚙️ Architecture

```
Service Registry (Eureka)
        ↑
   -----------------
   |               |
Company Service   User Service
```

* Each service runs independently
* Services register themselves with the Service Registry
* Communication happens through REST APIs

---

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring Cloud Netflix Eureka
* REST APIs
* Maven
* Microservices Architecture

---

## 🚀 Features

* 🔄 Independent deployment of services
* 📡 Service discovery using Eureka
* 🌐 RESTful communication between services
* 🧱 Modular and scalable architecture
* ⚡ Lightweight Spring Boot services

---

## 📂 Project Structure

```bash id="ms1"
microservices-project/
│
├── service_registry/
│   └── Eureka Server
│
├── company_server/
│   └── Company Microservice
│
├── user_server/
│   └── User Microservice
```

---

## ▶️ How to Run

1. Start **service_registry** first
2. Run **company_server**
3. Run **user_server**
4. Open Eureka dashboard to verify services

Default Eureka URL:

```
http://localhost:8761
```

---

## 📊 Learning Outcomes

* Microservices architecture design
* Service registration & discovery
* Spring Boot REST API development
* Distributed system communication

---

## 📫 Author

**Ravishankar Pandey**
Full Stack Developer | Java Specialist

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.
