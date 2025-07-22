🔐 Hybrid Identity Management System

A secure, scalable identity management platform designed to support hybrid infrastructures using microservices architecture. This system enables robust user authentication, role-based access control, and centralized identity governance.

---

📌 Overview

This project implements a full-stack enterprise-grade identity management system. It integrates user registration, authentication, and permission management with RESTful microservices, ensuring modularity, security, and maintainability.

---

🛠️ Tech Stack

- **Frontend**: (Optional UI layer or Postman for testing APIs)
- **Backend**: Java, Spring Boot, Node.js
- **Database**: SQL Server
- **Build Tools**: Maven, Gradle
- **DevOps**: Docker, Azure Pipelines, GitHub Actions
- **Authentication**: JWT (JSON Web Tokens)
- **Architecture**: Microservices

---

🚀 Key Features

- ✅ Modular Microservices (Auth, User, Access Control)
- 🔐 Secure login/logout flow with JWT tokens
- 👥 Role-Based Access Control (RBAC)
- 🗃️ SQL-based identity storage with schema validation
- 🧪 Unit testing with JUnit and Postman collections
- 🔄 CI/CD pipeline using GitHub Actions and Azure Pipelines
- 🐳 Docker containerization for deployment

---

🔄 API Endpoints (Sample)

`POST /api/auth/register`  
Register a new user

`POST /api/auth/login`  
Login and receive a JWT

`GET /api/user/me`  
Fetch current authenticated user

`GET /api/access/roles`  
Fetch available roles and permissions

---

🧪 Testing

- Backend unit tests with **JUnit**
- Postman test suites for all API endpoints
- Secure input validations and edge-case tests

---

📦 Deployment

1. Clone the repository  
2. Set environment variables (see `.env.example`)  
3. Build using Maven:  
   ```bash
   mvn clean install

