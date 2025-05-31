# 🌐 Customer Web Application

A modern Java web application built with Spring Boot, designed to demonstrate cloud deployment capabilities and database integration. This project serves as a practical example of building and deploying a web application on Heroku.

## ✨ Features

- **Spring Boot Architecture**
  - Robust backend with Spring Boot framework
  - MVC pattern implementation
  - RESTful endpoints
  
- **Database Integration**
  - PostgreSQL database support
  - Dynamic database operations
  - Real-time data persistence
  
- **Modern Frontend**
  - Responsive design with Bootstrap
  - Thymeleaf templating
  - Interactive UI components

## 🛠️ Technologies Used

- **Backend**
  - Java 17
  - Spring Boot
  - Spring MVC
  - JPA/Hibernate
  
- **Frontend**
  - Thymeleaf
  - Bootstrap 3.3.7
  - jQuery
  
- **Database**
  - PostgreSQL
  
- **Build Tools**
  - Maven
  
- **Deployment**
  - Heroku Platform

## 🚀 Quick Start

### Prerequisites
- Java 17 or higher
- Maven
- PostgreSQL
- Git

### Local Development Setup

1. Clone the repository:
```bash
git clone https://github.com/ItsSouls/CustomerWebApp.git
```
2. Navigate to the project directory:
cd CustomerWebApp
3. Build the project:
mvn clean install
4. Run the application:
mvn spring-boot:run
The application will be available at http://localhost:8080

📋 Project Structure

src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── heroku/
│   │           └── java/
│   │               └── GettingStartedApplication.java
│   └── resources/
│       ├── templates/
│       │   ├── fragments/
│       │   ├── error.html
│       │   ├── index.html
│       │   └── database.html
│       ├── public/
│       │   └── stylesheets/
│       └── application.properties

🌍 Deployment
Heroku Deployment
  1. Create a Heroku account if you haven't already
  2. Install the Heroku CLI
  3. Deploy using the following commands:
     heroku create
     git push heroku main
  Alternatively, deploy with one click:
<img alt="Deploy to Heroku" src="https://www.herokucdn.com/deploy/button.svg">


