# statement.md

## Project Title
UFitness – Diet & Exercise Tracking System

## Problem Statement
Most individuals struggle to track their diet, exercise habits, and daily calorie balance due to busy schedules or lack of convenient tools. Existing fitness applications often store personal data externally, require subscriptions, or offer limited customization. UFitness solves this by providing a secure, self-hosted fitness tracking system that enables users to log meals, record exercises, monitor weight, and analyze health trends with full control over their data.

## Scope of the Project
- Full diet and exercise tracking system  
- Daily food and exercise logs  
- Weight tracking and BMI calculation  
- Calorie consumption and burn estimation  
- Interactive charts and health analytics  
- Secure authentication and role-based access  
- Dockerized deployment  
- Database versioning with Flyway  
- MySQL for production and H2 for testing  

## Target Users
- Students  
- Working professionals  
- Fitness enthusiasts  
- Individuals managing weight goals  
- Anyone wanting a private health tracking system  
- Developers learning Java + Spring Boot architecture  

## High-Level Features
### 1. User Authentication
- Secure login/logout  
- Password hashing  
- Demo user auto-created via Flyway  

### 2. Weight Tracking
- Daily weight entry  
- Automatic BMI calculation  
- Calorie maintenance estimation  

### 3. Food Logging
- Search foods  
- Log meals daily  
- Recently eaten foods list  
- Global + user-created foods  
- Automatic calorie calculation  

### 4. Exercise Tracking
- 800+ exercises  
- Log intensity and duration  
- Weight-based calorie burn estimation  

### 5. Reporting & Analytics
- Daily summaries  
- JSON APIs for charts  
- Interactive visualizations using amCharts  

### 6. Infrastructure & Deployment
- Docker Compose support  
- Flyway migration scripts  
- Modular Spring MVC + JPA architecture  
- H2 database for testing  
