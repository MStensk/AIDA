---

title: "AI Code Agent: Login System with JWT"
date: 2026-04-27
draft: false
------------

# 🤖 AI Code Agent: Login System

This project demonstrates how I used an AI code agent to design and implement a secure login system.

---

## 🎯 Task

Build a login system using:

* Java
* Javalin
* Hibernate
* JWT authentication

---

## ⚙️ Features

* User registration
* Secure login
* Password hashing (BCrypt)
* JWT authentication
* Protected routes

---

## 🔄 Workflow with AI

### 1. Architecture design

I started by prompting the AI:

> "Create a login system using Javalin, Hibernate and JWT"

The AI suggested a layered architecture:

* Controller
* Service
* DAO
* JWT Utility

---

### 2. Initial implementation

The AI generated:

* Register endpoint
* Login endpoint
* JWT token generation

However, the initial solution had issues:

* Missing validation
* Weak error handling
* No route protection

---

### 3. Debugging

I collaborated with the AI to fix:

* Hibernate mapping issues
* Null pointer errors
* Incorrect JWT configuration

---

### 4. Refactoring

The AI helped improve:

* Separation of concerns
* Code readability
* Naming conventions

---

### 5. Security improvements

We added:

* BCrypt password hashing
* JWT middleware
* Token validation

---

## Key Learnings

* AI is effective for scaffolding backend systems
* Debugging requires human understanding
* Security must be validated manually
* Iteration improves output quality

---

## Example flow

```text
User registers → Password hashed → Stored in DB
User logs in → JWT generated → Used for protected routes
```

---

## Conclusion

AI code agents can significantly speed up backend development, but require:

* Critical thinking
* Validation
* Security awareness

They are best used as **collaborative tools** rather than replacements.

---
