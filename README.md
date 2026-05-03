# Task Manager App 🚀

A simple full-stack Task Manager application built using **Spring Boot (Java)** for the backend and **HTML, CSS, JavaScript** for the frontend. This app allows users to create, view, complete, and delete tasks.

---

## 🔗 Live Demo

👉 https://task-manager-app-hore.onrender.com

---

## 📌 Features

* Add new tasks
* View all tasks
* Mark tasks as completed
* Delete tasks
* Clean and responsive UI
* RESTful API integration

---

## 🛠 Tech Stack

### Backend

* Java 17
* Spring Boot
* Spring Data JPA
* H2 Database

### Frontend

* HTML
* CSS
* JavaScript

### Deployment

* Docker
* Render

---

## 📁 Project Structure

```
taskapp/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/example/taskapp/
 │   │   │   ├── controller/
 │   │   │   ├── model/
 │   │   │   ├── repository/
 │   │   │   └── TaskappApplication.java
 │   │   └── resources/
 │   │       ├── static/
 │   │       │   ├── index.html
 │   │       │   └── assets
 │   │       └── application.properties
 ├── Dockerfile
 ├── pom.xml
```

---

## ⚙️ API Endpoints

| Method | Endpoint               | Description        |
| ------ | ---------------------- | ------------------ |
| GET    | `/tasks`               | Get all tasks      |
| POST   | `/tasks`               | Create new task    |
| DELETE | `/tasks/{id}`          | Delete task        |
| PATCH  | `/tasks/{id}/complete` | Mark task complete |

---

## ▶️ Run Locally

### 1. Clone repo

```
git clone https://github.com/Anubhaw064/task-manager-app.git
cd task-manager-app/taskapp
```

### 2. Run application

```
mvn spring-boot:run
```

### 3. Open browser

```
http://localhost:8080
```

---

## 🐳 Docker Setup

### Build image

```
docker build -t task-manager-app .
```

### Run container

```
docker run -p 8080:8080 task-manager-app
```

---

## ⚠️ Notes

* Free hosting may cause initial delay (cold start)
* Uses in-memory database (data resets on restart)

---

## 👨‍💻 Author

Anubhaw Kumar

---


