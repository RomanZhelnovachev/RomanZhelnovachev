# 👋 Привет, я Роман Желновачев

🎯 **Java Backend Developer**  
💡 Backend-разработчик с фокусом на Highload и микросервисную архитектуру. Специализируюсь на оптимизации производительности и построении устойчивых интеграций.  
📍 Ищу задачи, связанные с масштабированием распределённых систем и сложным бэкендом.

---

## 🧩 Технологии и инструменты
**Backend:** Java 17/21, Spring Boot, Spring Security, Spring Cloud, Spring AI, Spring Security, Spring MVC, Spring Data JPA, Hibernate, Spring JDBC  
**Database:** PostgreSQL, Redis, MongoDB, Liquibase/Flyway
**Massege Broker:** Kafka, RabbitMQ
**DevOps:** Docker, Kubernetes, GitLab CI/Jenkins
**Observability:** ELK, Actuator, Prometheus, Grafana
**Testing:** Junit, Mockito, AssertJ, Testcontainers 
**Build & Tools:** Maven/Gradle, Git, Postman  
**Other:** JWT, ModelMapper, Lombok, Swagger  

---

## 📦 Мои проекты

### 🔹 [Search and Listing Platform]([https://github.com/RomanZhelnovachev/spring-boot-event-booking](https://github.com/RomanZhelnovachev/search-listings-platform))
Микросервисная платформа недвижимости для поиска, публикации и управления объявлениями с разделением **write-side** и **read-side** на основе **CQRS**.
**Функциональность:**
- Поиск недвижимости 4 типов с динамической фильтрацией и пагинацией
- CQRS-архитектура: Listing Service и Search Service
- Асинхронная синхронизация read-моделей через Apache Kafka и Transactional Outbox
- Партиционирование PostgreSQL по регионам для оптимизации поисковых запросов
- JWT-аутентификация и ролевая модель доступа RBAC
- Генерация тестовых данных и документирование REST API

🛠 **Стек:** Java 17, Spring Boot, Spring Security, Spring Data JPA, PostgreSQL, Liquibase, Apache Kafka, Redis, Docker, Maven, OpenAPI/Swagger
📘 **Формат:** Микросервисный pet-проект, демонстрирующий CQRS, асинхронное взаимодействие сервисов и проектирование масштабируемых read-моделей.

---

### 🔹 [Event Booking Backend](https://github.com/RomanZhelnovachev/spring-boot-event-booking)
Бэкенд для системы бронирования мероприятий с разделением ролей (**User**, **Admin**).  
**Функциональность:**  
- Регистрация и авторизация через JWT  
- Управление событиями и бронированиями  
- Ролевая модель доступа  
- REST API с валидацией  
- Контейнеризация через Docker  

🛠 **Стек:** Java 17, Spring Boot, Spring Security, PostgreSQL, Docker, Maven  
📘 **Формат:** Pet-проект, отражающий реальную структуру продакшн-приложения  

---

## 🚀 Что я изучаю сейчас
- Spring Cloud и микросервисные паттерны  
- Асинхронное взаимодействие (Kafka / RabbitMQ)  
- CI/CD (GitHub Actions, Docker Hub)  

---

## 📫 Как связаться
📧 **Email:** romanzhelnovachev@gmail.com


---

## 💬 Немного обо мне
Люблю backend-разработку за её логику и структурность.  
Пишу код, стремясь к чистоте и читаемости.  
Открыт к коммерческим проектам, где можно развиваться и приносить пользу команде.

---

⭐ Если тебе интересны мои проекты — можешь поставить звезду репозиторию, чтобы поддержать :)
