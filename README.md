#  Bug Reports

This repository contains examples of bug reports created as part of my QA learning journey.

---

##  Note

This content is written in English to follow industry standards.

---

##  Bug #1: Error on user registration

### 📌 Description

The system returns an error when submitting the registration form with valid data.

---

### 🔁 Steps to reproduce

1. Access the registration page
2. Fill all required fields correctly
3. Click on "Submit"

---

### ✅ Expected result

The user should be successfully registered.

---

### ❌ Actual result

An error message is displayed and the registration is not completed.

---

### 📎 Evidence

Simulated log:

```json
{
  "error": "Internal Server Error",
  "status": 500
}
```

---

##  Bug #2: Login allows invalid credentials

### 📌 Description

The system allows login even when incorrect credentials are provided.

---

### 🔁 Steps to reproduce

1. Go to login page
2. Enter invalid email and password
3. Click on "Login"

---

### ✅ Expected result

The system should deny access and display an error message.

---

### ❌ Actual result

The user is logged into the system.

---

### 📎 Evidence

Unexpected behavior observed during testing.

---

💬 These examples are based on common QA scenarios and practices.
