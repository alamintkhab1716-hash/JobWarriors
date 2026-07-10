# 💼 JobWarriors

<div align="center">

# 🚀 Modern Job Portal Platform

### Connecting Recruiters with Job Seekers through a Secure & Scalable Recruitment System

<p align="center">
<img src="https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=openjdk"/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white"/>
<img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
</p>

*A Full Stack Job Portal built with Spring Boot, Spring Security, Thymeleaf & MySQL.*

</div>

---

# 📖 About JobWarriors

**JobWarriors** is a full-stack recruitment platform developed using **Java**, **Spring Boot**, **Spring Security**, **Hibernate**, **Thymeleaf**, and **MySQL**.

The platform simplifies the hiring process by providing two dedicated modules:

### 👨‍🎓 Job Seeker
- Create an account
- Search available jobs
- Apply for jobs
- Upload resume
- Save favourite jobs
- Manage profile

### 👨‍💼 Recruiter
- Secure recruiter login
- Publish new job openings
- Manage posted jobs
- Update job details
- View applicants

The application follows a layered Spring Boot architecture with secure authentication, role-based authorization, REST APIs, and database integration.

---

# ✨ Key Features

## 🔐 Authentication & Security

- Secure Login & Registration
- Role-Based Authentication
- Spring Security
- BCrypt Password Encryption
- Session Management

---

## 👨‍🎓 Job Seeker Module

- Search Jobs
- Filter Jobs
- View Job Details
- Apply for Jobs
- Save Jobs
- Upload Resume
- Profile Management

---

## 👨‍💼 Recruiter Module

- Recruiter Dashboard
- Create Job Posts
- Update Existing Jobs
- Delete Jobs
- View Applicants
- Manage Posted Jobs

---

## 🌐 Backend Features

- REST APIs
- Spring MVC
- Spring Data JPA
- Hibernate ORM
- MySQL Database
- Layered Architecture

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Language | Java |
| Backend | Spring Boot, Spring MVC |
| Security | Spring Security |
| ORM | Hibernate, Spring Data JPA |
| Database | MySQL |
| Frontend | Thymeleaf, HTML5, CSS3, Bootstrap, JavaScript |
| Build Tool | Maven |
| Tools | IntelliJ IDEA, Git, GitHub, Postman |

---

# 🏗 Project Architecture

```text
                 Browser
                     │
                     ▼
            Spring Security
                     │
                     ▼
              Spring Controllers
                     │
                     ▼
              Service Layer
                     │
                     ▼
            Repository Layer
                     │
                     ▼
              MySQL Database
```

---

# 📸 Application Preview
## 🏠 Landing Page

The landing page introduces the platform, allowing users to search jobs and navigate to login or registration.

<p align="center">
<img src="assets/home.png" width="900">
</p>

---

## 🔐 Login

Secure login page for both **Job Seekers** and **Recruiters** using Spring Security Authentication.

<p align="center">
<img src="assets/login.png" width="900">
</p>

---

## 📝 Registration

New users can create an account by selecting their role as **Recruiter** or **Job Seeker**.

<p align="center">
<img src="assets/register.png" width="900">
</p>

---

## 👨‍🎓 Candidate Dashboard

Job seekers can browse opportunities, apply filters, save jobs, and explore the latest openings.

<p align="center">
<img src="assets/candidate-dashboard.png" width="900">
</p>

---

## 👤 Candidate Profile

Users can manage their profile, upload a profile picture, add skills, and upload their resume.

<p align="center">
<img src="assets/candidate-profile.png" width="900">
</p>

---

## 👨‍💼 Recruiter Dashboard

Recruiters can manage job postings, monitor applicants, and access recruitment tools from a centralized dashboard.

<p align="center">
<img src="assets/recruiter-dashboard.png" width="900">
</p>

---

## ➕ Post New Job

Recruiters can publish new job openings by entering job details, company information, work mode, and salary.

<p align="center">
<img src="assets/post-job.png" width="900">
</p>

---

## 📄 Job Details

Detailed job information page displaying company details, salary, job type, work mode, description, and applicant information.

<p align="center">
<img src="assets/job-details.png" width="900">
</p>

---

# 📂 Project Structure

```text
JobWarriors
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── controller
│   │   │   ├── service
│   │   │   ├── repository
│   │   │   ├── entity
│   │   │   ├── config
│   │   │   └── security
│   │   └── resources
│   │       ├── static
│   │       ├── templates
│   │       └── application.properties
│
├── assets
│   ├── home.png
│   ├── login.png
│   ├── register.png
│   ├── candidate-dashboard.png
│   ├── candidate-profile.png
│   ├── recruiter-dashboard.png
│   ├── post-job.png
│   └── job-details.png
│
├── pom.xml
└── README.md
```

---

# ⚙️ Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/alamintkhab1716-hash/JobWarriors.git
```

### 2️⃣ Open Project

```bash
cd JobWarriors
```

### 3️⃣ Configure MySQL Database

Update your `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/jobwarriors
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```

### 4️⃣ Build the Project

```bash
mvn clean install
```

### 5️⃣ Run the Application

```bash
mvn spring-boot:run
```

Application will be available at:

```text
http://localhost:8080
```

---

# 📡 REST API

The backend exposes RESTful endpoints for managing users, profiles, jobs, and applications.

| Method | Purpose |
|---------|---------|
| GET | Retrieve resources |
| POST | Create new resources |
| PUT | Update existing resources |
| DELETE | Remove resources |
