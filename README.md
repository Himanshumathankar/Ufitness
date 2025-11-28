# UFitness – Diet & Exercise Tracking System (Java + Spring Boot)

FitnessJiffy is a full-stack health-tracking application built using Java 21, Spring Boot, and Spring MVC. It enables users to track diet, exercises, daily weight, calorie intake, calorie burn, and generate interactive charts and insights for long-term fitness monitoring.

## Overview
FitnessJiffy is a self-hostable diet and workout management system.  
It lets users:

- Log foods eaten each day  
- Record exercises performed  
- Track daily weight and BMI  
- View calories consumed and burned  
- Generate interactive charts and reports  
- Maintain a complete health history  

This version uses Java 21, Spring Boot 2.x, MySQL, Docker, Flyway, Thymeleaf, Bootstrap, and jQuery.

## Features

### Authentication and Security
- Login/Logout using Spring Security  
- Secure password handling  
- Demo test user created through Flyway  

### Daily Weight Tracking
- Record daily weight  
- Automatic BMI calculation  
- Calorie maintenance suggestions  

### Food Logging System
- Search foods by name  
- Daily meal tracking  
- Recently eaten foods list  
- Global and private foods  
- Auto calorie calculation  

### Exercise Tracking
- Database of 800+ exercises  
- Log duration and intensity  
- Auto calorie burn calculation  

### Reporting and Charts
- Daily health summaries  
- amCharts interactive charts  
- JSON endpoints for chart rendering  
- Background worker for summary updates  

### Database and Infrastructure
- MySQL with Flyway migrations  
- H2 for testing  
- Docker Compose support  
- Gradle CI pipeline  

## Technologies / Tools Used

### Backend
- Java 21  
- Spring Boot 2.x  
- Spring MVC  
- Spring Data JPA  
- Spring Security  
- Flyway  
- MySQL  
- H2  

### Frontend
- Thymeleaf  
- Bootstrap  
- jQuery  
- amCharts  

### DevOps
- Gradle  
- Docker & Docker Compose  
- Git & GitHub  

## Steps to Install and Run the Project

### Prerequisites
- Java 21  
- Docker (optional)  
- Gradle wrapper  
- MySQL or Docker Compose  

### 1. Start MySQL using Docker
```
docker compose up -d
```
Stop:
```
docker compose down
```

### 2. Run the Application
Run directly:
```
./gradlew bootRun
```
Build:
```
./gradlew build
```
Create JAR:
```
./gradlew bootJar
```

### 3. Use a Custom Database
```
export SPRING_DATASOURCE_URL=jdbc:mysql://<host>:<port>/<schema>
export SPRING_DATASOURCE_USERNAME=<username>
export SPRING_DATASOURCE_PASSWORD=<password>
```

## Testing Instructions

Run tests:
```
./gradlew check
```

Test setup:
- H2 database  
- JUnit 5  
- Mocked services and repositories  
- Integration tests  

## Screenshots
Place screenshots in the `/screenshots` folder.

Recommended:
- Login Page  
- Weight Tracking  
- Food Logging  
- Exercise Search  
- Charts and Reports  
