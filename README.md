# springboot-microservices-architecture
Spring Cloud microservices
# 🧩 Arquitectura de Microservicios con Spring Boot y Spring Cloud

Este proyecto agrupa varios microservicios desarrollados como parte del curso avanzado de microservicios. Cada servicio se encuentra en un repositorio independiente y se enfoca en diferentes aspectos de la arquitectura distribuida con Spring Cloud.

⚠️ Por limitaciones de la capa gratuita de AWS EC2, el archivo `docker-compose.yml` incluye solo tres microservicios (items, eureka, products). El resto está implementado y documentado, pero no incluido en la orquestación completa.

## 🔧 Microservicios implementados

| Servicio              | Funcionalidad                                        | Repositorio |
|-----------------------|------------------------------------------------------|-------------|
| **Items**             | Orquesta productos e invoca otros servicios         | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-items) |
| **Products**          | Gestión CRUD de productos                           | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-products) |
| **Users**             | Gestión de usuarios                                 | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-users) |
| **OAuth**             | Autenticación y autorización con JWT + OAuth2.1     | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-oauth) |
| **Config Server**     | Configuración centralizada para todos los servicios | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-config-server) |
| **Eureka Server**     | Registro y descubrimiento de servicios               | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-eureka) |
| **API Gateway**       | Entrada unificada con filtros y balanceo            | [Repo](https://github.com/GuidoComp/msvc-guzman-udemy-gateway-mvc) |
| **Docker Compose**    | Orquestación parcial (3 servicios)                  | [Repo actual](https://github.com/GuidoComp/msvc-guzman-udemy-docker-compose) |

---

## 🚀 Características técnicas destacadas

- Arquitectura basada en Spring Cloud
- Spring Boot 3.3 con Java 21
- Comunicación entre microservicios via REST
- Configuración centralizada con perfiles por entorno
- Registro y descubrimiento con Eureka
- Balanceo de carga con Spring Cloud LoadBalancer
- Seguridad con OAuth 2.1, JWT y roles
- Tolerancia a fallos con Resilience4j Circuit Breaker
- Docker y Docker Compose
- Monitoreo con Micrometer y Zipkin

---

📌 **Nota**: Este proyecto fue parte de un curso intensivo, y si bien no tiene lógica de negocio completa, su objetivo es demostrar la implementación de patrones modernos de microservicios y buenas prácticas con Spring Cloud.

