# 💼 JobWarriors

<div align="center">

### A Full-Stack Job Portal Application built with Spring Boot & PostgreSQL

*Connecting talented job seekers with recruiters through a secure and modern recruitment platform.*

![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge\&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge\&logo=springboot)
![Spring Security](https://img.shields.io/badge/Spring_Security-6.x-6DB33F?style=for-the-badge\&logo=springsecurity)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge\&logo=postgresql)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-3.1-005F0F?style=for-the-badge\&logo=thymeleaf)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge\&logo=apachemaven)

</div>

---

# 📖 About the Project

**JobWarriors** is a full-stack Job Portal application developed using **Spring Boot**, **Spring Security**, **Thymeleaf**, and **PostgreSQL**.

The platform enables **Job Seekers** to explore job opportunities, upload resumes, and apply for positions, while allowing **Recruiters** to securely manage job postings through a dedicated dashboard.

The project follows modern backend development practices including layered architecture, authentication & authorization, RESTful APIs, database integration, and secure user management.

---

# ✨ Features

## 🔐 Authentication

* Secure Login & Registration
* Spring Security Authentication
* Password Encryption
* Role-Based Authorization

## 👨‍💼 Recruiter Module

* Recruiter Dashboard
* Create Job Posts
* Update Existing Jobs
* Delete Job Posts
* Manage Posted Jobs

## 👨‍🎓 Job Seeker Module

* Browse Available Jobs
* Search Jobs
* View Job Details
* Apply for Jobs
* Upload Resume

## 🌐 REST APIs

* RESTful Backend APIs
* CRUD Operations
* JSON Data Exchange
* API-ready Backend Architecture

## 🗄 Database

* My Sql
* Spring Data JPA
* Hibernate ORM
* Entity Relationships

---

# 🛠 Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring MVC
* Spring Security
* Spring Data JPA
* Hibernate

### Frontend

* Thymeleaf
* HTML5
* CSS3
* Bootstrap
* JavaScript

### Database

* My Sql

### Tools

* IntelliJ IDEA
* Git
* GitHub
* Maven
* Postman

---

# 🏗 Architecture

```text
Client (Browser)
        │
        ▼
Spring MVC Controllers
        │
        ▼
Service Layer
        │
        ▼
Repository Layer (JPA)
        │
        ▼
PostgreSQL Database
```

---

# 📂 Project Structure

```text
src/
├── main/
│   ├── java/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── config/
│   │   └── security/
│   └── resources/
│       ├── templates/
│       ├── static/
│       └── application.properties
```

---

# ⚙️ Getting Started

## Clone the Repository

```bash
git clone https://github.com/alamintkhab1716-hash/JobWarriors.git
```

## Navigate to the Project

```bash
cd JobWarriors
```

## Configure PostgreSQL

Update the following properties:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/jobwarriors
spring.datasource.username=******
spring.datasource.password=*****
```

## Run the Application

```bash
mvn spring-boot:run
```

Application will start at:

```text
http://localhost:8080
```

---

# 📸 Screenshots

> Add screenshots after deployment.

* Home Page
* Login Page
* Registration Page
* Recruiter Dashboard
* Job Listings
* Job Details
* Resume Upload

---

# 🔗 REST API

Example endpoint:

```http
GET /api/jobs
```

```http
POST /api/jobs
```

```http
PUT /api/jobs/{id}
```

```http
DELETE /api/jobs/{id}
```

---

# 🔒 Security

* Spring Security
* BCrypt Password Encryption
* Authentication & Authorization
* Role-Based Access Control

---

# 🚀 Future Enhancements

* Email Notifications
* Interview Scheduling
* Company Verification
* Admin Dashboard
* Docker Support
* CI/CD Pipeline
* Cloud Deployment (AWS / Render)

---

# 👨‍💻 Author

**Intkhab Alam**

Backend Developer | Java | Spring Boot | PostgreSQL

GitHub: https://github.com/alamintkhab1716-hash

---

## ⭐ Support

If you found this project helpful, please consider giving it a **Star** on GitHub.

