# Spring Microservices Architecture

Una arquitectura de microservicios robusta con Spring Cloud.

## 🧩 Componentes
- **Eureka Server**: Service Discovery
- **Config Server**: Centralized configuration
- **API Gateway**: Routing y filtrado
- **Microservicios**: Course, Student

## 🚀 Inicio rápido
```bash
# 1. Iniciar Eureka
cd microservice-eureka && ./mvnw spring-boot:run

# 2. Iniciar Config Server
cd microservice-config && ./mvnw spring-boot:run

# 3. Iniciar Gateway y microservicios
# ...
