# Security-Feature-1
# Spring Security Learning Project

## Overview
This is a simple Spring Boot project created to learn and understand the fundamentals of Spring Security. It focuses on implementing basic authentication and authorization using in-memory users without involving a database or additional layers like services or repositories.

The goal of this project is to build a strong foundation in Spring Security before moving on to advanced topics like JWT and OAuth2.

## Features
- Spring Security integration
- In-memory authentication (no database)
- Role-based authorization (USER and ADMIN)
- Form-based login page (default Spring Security login)
- Protected and public endpoints

## Endpoints

| Endpoint | Access | Description |
|----------|--------|-------------|
| `/norm` | Public | Home page |
| `/user` | USER / ADMIN | Accessible to logged-in users |
| `/admin` | ADMIN only | Accessible only to admin users |

---

## Default Users

### User
- Username: `fofo`
- Password: `1234`

### Admin
- Username: `admin`
- Password: `admin123`

---

## Tech Stack
- Java
- Spring Boot
- Spring Security


- Understand authentication vs authorization
- Learn how Spring Security filter chain works
- Implement role-based access control
- Understand form-based login flow
- Prepare foundation for JWT and OAuth2

