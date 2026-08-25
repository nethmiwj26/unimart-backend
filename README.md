# UniMart Backend

Spring Boot monolithic backend for the UniMart student marketplace project.

## Tech stack
- Java 21, Spring Boot 4.1
- Spring Data JPA + Hibernate
- MySQL 8.4 + Flyway migrations
- Spring Security + OAuth2 Resource Server (JWT)

## Local setup
1. Ensure MySQL is running with the `unimart` schema created (see project setup guides).
2. Copy `.env.example` values into your IntelliJ Run Configuration environment variables.
3. Run with `./mvnw spring-boot:run`.
4. Verify health: `curl http://localhost:8080/actuator/health`