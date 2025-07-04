# 💳 Banking Microservices System (Enterprise-Grade Architecture)

A production-ready banking system built with a microservices architecture using Spring Boot and deployed on a Kubernetes cluster. This project showcases real-world infrastructure patterns including service discovery, API gateway, secure communication, distributed tracing, logging, monitoring, and asynchronous messaging.

---

## 📐 Architecture Diagram

![Architecture Diagram](./eb094189-594e-48e3-946d-55e52f40613e.png)

---

## 🛠️ Tech Stack

- **Spring Boot**, **Spring Cloud**, **Spring Security**, **Spring Cloud Gateway**
- **Keycloak** for OAuth2/OpenID Connect (SSO)
- **Kafka** & **RabbitMQ** for asynchronous communication
- **Docker**, **Kubernetes**, **Helm**
- **Eureka** for service discovery
- **Prometheus**, **Grafana**, **Loki**, **OpenTelemetry** for observability
- **Redis** for caching
- **REST APIs** with OpenAPI docs (Swagger)

---

## 🔧 Microservices Included

| Service   | Description |
|-----------|-------------|
| **Gateway**  | API Gateway with OAuth2 security via Keycloak |
| **Eureka**   | Service registry and discovery |
| **Accounts** | Core banking operations and account services |
| **Cards**    | Credit/debit card operations |
| **Loans**    | Loan management and processing |
| **Messages** | Asynchronous event processing |
| **Event Broker** | Kafka + RabbitMQ integration for async flow |

---

## 🚀 Features

- ✅ Microservices communication via **REST** (sync) and **Kafka/RabbitMQ** (async)
- ✅ Full **OAuth2 Security** using Keycloak
- ✅ Deployed using **Kubernetes + Helm**
- ✅ Observability: **Prometheus**, **Grafana**, **Loki**
- ✅ Centralized Logging + Metrics scraping
- ✅ Follows **15-Factor App Methodology**

---

## 🔍 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/banking-microservices.git
