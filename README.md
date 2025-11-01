# Laravel REST API Authentication Using Sanctum

This repository provides a complete example of **REST API Authentication** built with **Laravel** using **Sanctum**.  
It demonstrates how to create secure token-based authentication for modern web and mobile applications that communicate with a backend server.

---

## Features

This project implements the following REST APIs:

| Endpoint        | Method | Description                          | Auth |
| --------------- | ------ | ------------------------------------ | ---- |
| `/api/register` | POST   | Register a new user                  | ❌   |
| `/api/login`    | POST   | Authenticate user and generate token | ❌   |
| `/api/profile`  | GET    | Retrieve authenticated user details  | ✅   |
| `/api/logout`   | POST   | Revoke current token                 | ✅   |

---

## Technologies Used

-   **Laravel (v12 compatible)**
-   **Laravel Sanctum** (Token-based API authentication)
-   **MySQL** (Database)
-   **Composer** (Dependency management)
-   **Postman** (API testing)

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/laravel-rest-api-auth-sanctum.git
cd laravel-rest-api-auth-sanctum
```

### 2. Install Dependencies

```bash
composer install
```

### 3. Configure Environment

```bash
cp .env.example .env
```
