# 🔌 Course 10: APIs

Welcome to **Course 10** of the **Meta Full-Stack Developer** Professional Certificate program! This course explores the principles, tools, and best practices required to architect, construct, secure, optimize, and evaluate production-ready Web APIs. Transitioning from traditional server-side template rendering to decoupled client-server architecture, you will leverage **Django REST Framework (DRF)** to construct RESTful endpoints, implement data serialization and validation, configure role-based authentication and authorization, apply query filtering and pagination, enforce rate throttling and caching, and deploy the complete "Little Lemon" backend API service.

---

## 📝 Core Technical Objectives
- **RESTful Architecture & Design Principles:** Understanding client-server communication via HTTP/HTTPS, mapping CRUD operations to HTTP methods (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`), status code protocols, and designing clean resource routes.
- **Django REST Framework (DRF) Core:** Utilizing DRF function-based `@api_view` decorators, class-based APIViews, generic views, viewsets, and DRF routers to scaffold scalable endpoints.
- **Data Serialization & Validation:** Converting complex database model instances to JSON/XML response payloads using `ModelSerializer` classes, while validating and deserializing incoming request data safely.
- **Advanced API Optimization:** Empowering frontend consumers through `django-filters`, keyword search, dynamic ordering backends, page-number pagination, and server-side caching.
- **Security, Auth & Role Management:** Implementing token-based authentication via Djoser and JSON Web Tokens (JWT), setting up user group permissions (Managers, Delivery Crew, Customers), and applying rate throttling (`AnonRateThrottle`, `UserRateThrottle`).

---

## 🧪 Course Architecture & Module Matrix

This course is structured into 4 sequential modules that guide you from foundational REST concepts through DRF serialization, security, and capstone API deployment:

| Module / Directory | Operational Focus & Core Topics | Key Deliverables & Portfolio Assets |
| :--- | :--- | :--- |
| **[Module 1](./Module%201)** | **REST APIs**: HTTP request-response cycle, CRUD mapping, clean route naming conventions, `pipenv` environment setup, project scaffolding, JSON/XML response formats, and authentication vs. authorization concepts. | • Know Your Tools Lab<br>• Principles of API Development Check<br>• Your First API Lab |
| **[Module 2](./Module%202)** | **Django REST framework**: DRF setup, `@api_view` decorators, class-based views vs. viewsets, DRF routers, `Serializer` & `ModelSerializer` classes, relationship serializers, data validation, custom renderers, and the Django debug toolbar. | • Convert Booklist API to DRF Lab<br>• Introduction to DRF Knowledge Check<br>• Restaurant Menu Serialization Lab |
| **[Module 3](./Module%203)** | **Advanced API development**: Data sanitization, filtering, searching, ordering, pagination, server-side caching, token authentication, Djoser integration, JWT endpoints, user roles, and rate throttling. | • Menu API Filtering & Ordering Lab<br>• Essential API Tasks Knowledge Check<br>• User Account Management Lab |
| **[Module 4](./Module%204)** | **Final project assessment**: Comprehensive course recap, project structure planning, role-based access control (RBAC), menu/order workflows, and the peer-graded capstone API project for the "Little Lemon" restaurant. | • **Capstone**: Little Lemon API Project (Peer-Graded)<br>• Final Graded API Quiz |

---

## 💡 Visual Pipeline Reference

The comprehensive end-to-end RESTful API request lifecycle, serialization pipeline, and role-based security model governing Course 10:

- **End-to-End RESTful API Request & Security Pipeline**:

$$\begin{aligned} \text{Client Request: } &\text{HTTP Method + Bearer Token / JWT} \xrightarrow{\text{Throttling and Djoser Auth}} \text{Role Permission Check} \\ \text{Processing Layer: } &\text{Sanitized Payload} \xrightarrow{\text{DRF Serializer / Model validation}} \text{Database Query via ORM} \\ \text{Response Layer: } &\text{Filter, Order and Paginate} \xrightarrow{\text{JSONRenderer / Cache}} \text{Formatted JSON Response Output} \end{aligned}$$

- **Core Course 10 Taxonomy**:

| Operational Domain | Core Tools & Technologies | Professional Application |
| :--- | :--- | :--- |
| **REST Fundamentals** | HTTP Verbs, Status Codes, Route Conventions, `pipenv` | Architecting decoupled, standardized backend services for client consumers |
| **DRF Core & Views** | `@api_view`, `APIView`, `ModelViewSet`, DRF Routers | Building clean, modular API endpoints with minimal boilerplate code |
| **Serialization & Data** | `ModelSerializer`, Relationships, Input Validation, JSON | Converting complex Python ORM objects into validated, structured payloads |
| **Security & Optimization** | Token Auth, Djoser, JWT, Group Permissions, Throttling | Securing endpoints with fine-grained access control and preventing abuse |

---

## 🎯 Technical Skills Architecture

### 📊 Professional API Engineering Mastery
- **RESTful Service Architecture:** Designing intuitive, scalable API routes adhering to strict HTTP method specifications and stateless response protocols.
- **DRF Serialization & Validation:** Writing declarative serializers to handle complex multi-model relationships, custom field validation, and data transformation.
- **Endpoint Security & Access Control:** Securing sensitive business resources using JWT authentication, user group management, and automated rate throttling.

### 🤖 Applied Practice & Professional Readiness
- **Production API Development:** Building, testing, and debugging RESTful web services using industry tools like Postman, VS Code, and browser dev tools.
- **Role-Based Workflow Implementation:** Architecting real-world authorization matrix logic across distinct user groups (Admins, Managers, Delivery Personnel, Customers).
- **Specialization Progression:** Concluding API backend mastery, fully equipped to seamlessly integrate web APIs with modern frontend frameworks like React in full-stack applications.

---

## 🛠️ Production Tech Stack & Ecosystem

| Learning Framework | Core Technologies & Stack | Development & Testing Environment | Interactive Platform |
| :---: | :---: | :---: | :---: |
| ![Meta Certificate](https://img.shields.io/badge/Meta-Full--Stack_Developer-blue?style=flat&logo=meta&logoColor=white) | ![DRF](https://img.shields.io/badge/Stack-Django_REST_Framework_%7C_Python_3_%7C_JWT_%7C_Djoser-092E20?style=flat&logo=django&logoColor=white) | ![Tools](https://img.shields.io/badge/Tools-VS_Code_%7C_Pipenv_%7C_Postman_%7C_Debug_Toolbar-013243?style=flat) | ![Coursera](https://img.shields.io/badge/Coursera-Interactive_Learning-0056D2?style=flat&logo=coursera&logoColor=white) |
