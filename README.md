# 🛠️ Spring Boot Student CRUD App

A simple and clean **CRUD (Create, Read, Update, Delete)** REST API built with **Spring Boot**, demonstrating how to manage student records with **MySQL database** and **Spring Data JPA**.

This project covers:

- ✅ Spring Boot project setup from scratch  
- ✅ Connecting to **MySQL** database  
- ✅ Creating REST APIs using `@RestController`  
- ✅ Performing full **CRUD** operations  
- ✅ Integrating with **Spring Data JPA**  
- ✅ Testing endpoints with **Postman**

---

## 📌 Features Covered

- ➕ Add new student  
- 📂 View all students  
- ✏️ Update student details  
- ❌ Delete student by ID  

---

## 🔧 Tools & Technologies

- ☕ **Java 17+**  
- 🚀 **Spring Boot**  
- 📦 **Spring Data JPA**  
- 🗃️ **MySQL**  
- 🔍 **Postman**

---

## 📁 Project Structure

```bash
src/
└── main/
    ├── java/
    │   └── com/
    │       └── crud/
    │           └── student_ms_a/
    │               ├── model/
    │               │   └── Student.java
    │               ├── StudentController/
    │               │   └── StudentController.java
    │               ├── StudentRep/
    │               │   └── StudentRepo.java
    │               └── StudentMsAApplication.java
    ├── resources/
    │   ├── static/
    │   ├── templates/
    │   └── application.properties
