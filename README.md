# Web Food Ordering

## Overview
Web Food Ordering is an advanced online food ordering system built using Spring Boot. It allows users to register, sign in, browse menus, and place orders with ease. This system is designed to be robust, secure, and highly scalable, catering to both small and large-scale deployments.

## Key Features
- **User Registration and Authentication:** Users can register and authenticate securely using Spring Security.
- **Menu Browsing and Ordering:** Comprehensive RESTful APIs allow for interactive menu browsing and order placement.
- **Data Management:** Utilizes Spring Data JDBC for efficient data management with a PostgreSQL database on AWS RDS.
- **Caching Mechanisms:** Implements caching to enhance performance by reducing database load and improving response times.

## Technical Stack
- **Backend:**
  - **Framework:** Spring Boot
  - **Authentication:** Spring Security
  - **ORM:** Spring Data JDBC
  - **Caching:** Spring Framework

- **Database:**
  - **DBMS:** PostgreSQL
  - **Host:** AWS RDS

- **Frontend:**
  - **Library:** ReactJS
  - **UI Framework:** Ant Design

- **Containerization and Deployment:**
  - **Containerization:** Docker
  - **Registry:** AWS ECR
  - **Deployment:** AWS App Runner
