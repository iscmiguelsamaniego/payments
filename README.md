# Nombre de tu Proyecto

Proyecto backend desarrollado con **Spring Boot 4.1.0** y **Java 21**, siguiendo una **Arquitectura Hexagonal**.

## Tecnologías
* **Lenguaje:** Java 21
* **Framework:** Spring Boot 4.1.0
* **Build Tool:** Gradle (Kotlin DSL)
* **Base de Datos:** PostgreSQL
* **Mensajería:** Apache Kafka (KRaft)
* **Resiliencia:** Resilience4j
* **Documentación:** SpringDoc OpenAPI (Swagger)
* **Testing:** JUnit 5, Mockito, Testcontainers, ArchUnit

## Ejecución
Para levantar la infraestructura necesaria (PostgreSQL y Kafka), utiliza el archivo `docker-compose.yml` (si ya lo tienes configurado) o ejecuta:
`docker-compose up -d`

Para compilar y ejecutar el proyecto:
`./gradlew bootRun`

## Estructura
El proyecto sigue principios de arquitectura hexagonal para asegurar la separación de responsabilidades entre el Dominio, la Aplicación y la Infraestructura.
