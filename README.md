
# 🎓 TuLaBy – Full-Stack Educational Management Platform

<p align="center">
  <img src="https://img.shields.io/badge/Project-Graduation%20Project-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Database-SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

## 📌 Project Overview

**TuLaBy** is a full-stack educational management platform developed as a graduation project to support students and improve access to academic information, educational resources, and university-related services.

The platform combines a web application built with React.js and a backend API developed using ASP.NET Core. It provides a foundation for managing educational data and connecting users with academic resources through an integrated web experience.

As the **Team Leader and Full-Stack Developer**, I contributed to project development across both frontend and backend, with a focus on API development, database integration, application architecture, and user interface implementation.

---

## 🎯 Project Objectives

- 🎓 Provide students with access to educational resources and academic services.
- 📚 Organize educational content and study materials.
- 📰 Make college news and educational information accessible through a web interface.
- 🗓️ Support academic operations such as lecture and attendance management.
- 🔗 Connect frontend interfaces with backend services through RESTful APIs.
- 🔐 Support secure access through authentication and role-based authorization.
- 🧩 Organize backend components using a layered architecture for better maintainability.

---

## 🛠️ Technology Stack

### 💻 Backend Development

- **C#** — Primary backend programming language.
- **ASP.NET Core Web API** — Building RESTful endpoints and backend services.
- **Entity Framework Core** — Object-relational mapping and database operations.
- **Microsoft SQL Server** — Relational database management.
- **LINQ** — Querying and manipulating application data.
- **AutoMapper** — Mapping between entities and Data Transfer Objects.
- **JWT** — Token-based authentication.
- **Role-Based Authorization** — Controlling access to protected resources according to user roles.
- **DTOs** — Structuring data exchanged between application layers and API clients.
- **Repository Pattern** — Organizing data access operations.
- **Unit of Work Pattern** — Coordinating data access operations.
- **N-Tier Architecture** — Separating application responsibilities into distinct layers.

### ⚛️ Frontend Development

- **React.js** — Building reusable and component-based user interfaces.
- **JavaScript** — Application logic and interactive functionality.
- **Context API** — Sharing application state across React components.
- **React Router** — Client-side navigation.
- **Styled Components** — Component-level styling.
- **Responsive UI Development** — Supporting different screen sizes.

### 🔧 Development Tools

- Git
- GitHub
- Visual Studio
- Visual Studio Code
- Postman
- Swagger / OpenAPI

---

## 🏗️ Backend Architecture

The backend follows an **N-Tier Architecture** approach to separate responsibilities and make the application easier to maintain and extend.

### 📂 Main Layers

| Layer | Responsibility |
|---|---|
| **Core** | Core application entities and shared business-related components. |
| **DTOs** | Data Transfer Objects used to structure data exchanged between layers. |
| **Infrastructure** | Database-related implementation and persistence operations. |
| **Services** | Application services and business-operation handling. |
| **API** | HTTP endpoints, request handling, and communication with clients. |
| **Dashboard** | Administrative dashboard-related functionality. |

### 🔄 Request Processing Flow

A typical frontend-to-backend interaction follows this general flow:

1. The React frontend sends an HTTP request to an API endpoint.
2. The API receives the request and processes the relevant input.
3. The service layer handles the corresponding application operation.
4. The infrastructure and data-access components interact with SQL Server through Entity Framework Core.
5. The application returns the response to the frontend.
6. The frontend updates the interface based on the returned data.

*The exact flow may vary depending on the endpoint and operation.*

---

## 🔐 Authentication & Authorization

The backend uses JWT-based authentication and role-based authorization to help protect application resources.

Key concepts include:

- **JWT Authentication:** Using tokens to authenticate requests to protected endpoints.
- **Role-Based Authorization:** Restricting access to endpoints according to assigned roles.
- **Protected API Endpoints:** Applying authorization requirements to resources that need access control.

These mechanisms help establish a structured approach to API security.

---

## 🗄️ Database & Data Access

The application uses **Microsoft SQL Server** as its relational database and **Entity Framework Core** for data access.

Data-related technologies and patterns include:

- Entity Framework Core for database operations.
- LINQ for querying application data.
- Repository Pattern for organizing data access.
- Unit of Work Pattern for coordinating related persistence operations.
- DTOs for defining data exchanged through application boundaries.
- AutoMapper for mapping between data models and DTOs.

The platform includes educational data and functionality related to students, lectures, and attendance.

---

## ✨ Key Platform Features

### 🎓 Student & Academic Services
- Student-related information and profiles.
- Access to educational content.
- Academic information and student services.

### 📚 Educational Resources
- Educational materials and study resources.
- Organized access to academic content.
- Support for student learning activities.

### 📰 College Information
- College news and educational updates.
- A web interface for browsing available content.

### 🗓️ Academic Management
- Lecture-related management functionality.
- Attendance-related functionality.

### 🔗 Full-Stack Integration
- React frontend communicating with ASP.NET Core APIs.
- HTTP-based data exchange between the client and server.
- Dynamic presentation of data retrieved from backend services.

> **Note:** Include only features that are implemented in the version you are presenting. If a feature is planned or partially completed, label it accordingly.

---

## 👨‍💻 My Role & Contributions

**Role: Team Leader | Full-Stack Developer**

My work on TuLaBy covered both frontend and backend development.

### Backend Contributions
- Developed backend functionality using ASP.NET Core Web API.
- Built RESTful endpoints to support educational platform operations.
- Worked with Entity Framework Core and SQL Server for data persistence.
- Applied N-Tier Architecture to separate application responsibilities.
- Used Repository and Unit of Work patterns to organize data access.
- Worked with DTOs and AutoMapper for structured data transfer and mapping.
- Implemented JWT authentication and role-based authorization.
- Integrated backend services with the React frontend.

### Frontend Contributions
- Designed and developed web interfaces using React.js.
- Built reusable UI components.
- Used Context API for shared application state.
- Implemented client-side navigation using React Router.
- Styled interfaces using Styled Components.
- Connected frontend components to backend APIs.

### Teamwork & Project Coordination
- Served as Team Leader during the graduation project.
- Contributed to coordinating development work across the team.
- Collaborated on integrating frontend and backend components.
- Helped bring different application components together into a full-stack solution.

---

## 🧠 Technical Concepts Applied

Through this project, I worked with and applied concepts related to:

- Object-Oriented Programming (OOP).
- Separation of Concerns.
- Layered / N-Tier Architecture.
- RESTful API design.
- Relational database modeling and data access.
- DTO-based data transfer.
- Authentication and authorization.
- Reusable React components.
- Frontend-backend integration.
- Version control using Git and GitHub.

---

## 🔗 Project Links

- 🏢 **GitHub Organization:** [TuLaBy-LLC](https://github.com/TuLaBy-LLC)
- ⚛️ **Frontend Repository:** [React Web Application](https://github.com/TuLaBy-LLC/Front-End)
- ⚙️ **Backend Repository:** [ASP.NET Core Web API](https://github.com/TuLaBy-LLC/Back-End)
- 🌐 **Live Web Application:** [TuLaBy](https://tulaby.netlify.app/)
- 📖 **API Documentation:** [Swagger / API Documentation](https://tulaby-api.runasp.net/index.html)

---

## 🚀 What I Learned

Working on TuLaBy helped me strengthen my understanding of full-stack application development, particularly:

- Building APIs with ASP.NET Core.
- Working with relational databases using Entity Framework Core.
- Structuring backend code into separate layers.
- Applying common data-access patterns.
- Integrating a React application with backend services.
- Implementing authentication and authorization.
- Collaborating with a team to develop a complete software project.

---

## 📌 Future Improvements

Potential areas for further development include:

- Expanding automated testing.
- Improving API validation and error handling.
- Adding structured logging and monitoring.
- Containerizing application components with Docker.
- Establishing a CI/CD pipeline.
- Reviewing performance and security as the application grows.

---

## ⭐ Project Summary

**TuLaBy** demonstrates my experience working on a full-stack educational management application, combining **ASP.NET Core Web API, Entity Framework Core, SQL Server, and React.js**.

The project reflects my interest in backend engineering, software architecture, API development, and building maintainable web applications.

<p align="center">
  <b>Built as a graduation project at Sohag University.</b>
</p>
