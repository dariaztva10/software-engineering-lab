This repository contains small experiments, notes and implementations related to:

- Clean Code
- Design Patterns
- Software Architecture
- Distributed Systems

The goal is to build a structured knowledge base while improving implementation quality and architectural thinking.

---

## Topics

### 1. Single Responsibility Principle (SRP)

**Definition:**  
A class should have only one reason to change.

### ❌ Bad Example

```javascript
class UserService {
  createUser(userData) {
    // logic to create user
  }

  sendEmail(email) {
    // logic to send email
  }
}

```
### ✅ Better Example
```javascript
class UserService {
  createUser(userData) {
    // logic to create user
  }
}

class EmailService {
  sendEmail(email) {
    // logic to send email
  }
}
```

## Progress Log

- [x] Single Responsibility Principle (SRP)
- [ ] Open-Closed Principle (OCP)
- [ ] Dependency Inversion Principle (DIP)
- [ ] Clean Architecture basics
- [ ] Hexagonal Architecture
