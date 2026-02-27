# Vehicle Management System (VMS)

## 📌 Introduction

Vehicle Management System (VMS) is a full-stack web application for managing vehicles, drivers, and routes.
The system allows administrators to monitor vehicle information, assign drivers, manage routes, and track statistics.

This project is built with Spring Boot (Backend) and React + Vite (Frontend).

---

## 🧰 Technologies Used

### Backend

* Java 17
* Spring Boot 3
* Spring Data JPA
* Spring Validation
* Spring WebSocket
* OAuth2 Resource Server
* MapStruct
* Lombok
* MySQL
* Gradle

### Frontend

* React 18
* Vite
* Redux Toolkit
* React Router
* Axios
* TailwindCSS
* Material UI / Ant Design
* WebSocket (STOMP, SockJS)

---

## 📁 Project Structure

```
VMS
├── VMS-repo-BE        # Spring Boot backend
│
├── VMS-repo-FE        # React frontend
│
└── README.md
```

---

## ⚙️ Backend Setup

### 1. Go to backend folder

```
cd VMS-repo-BE
```

### 2. Configure database in application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/vms
spring.datasource.username=root
spring.datasource.password=your_password
```

### 3. Run backend

```
./gradlew bootRun
```

Backend runs at:

```
http://localhost:8080
```

---

## ⚙️ Frontend Setup

### 1. Go to frontend folder

```
cd VMS-repo-FE
```

### 2. Install dependencies

```
npm install
```

### 3. Run frontend

```
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## ✨ Features

* Manage vehicles
* Manage drivers
* Manage routes
* Assign driver to vehicle
* View statistics dashboard
* WebSocket real-time updates
* RESTful API integration

---

## 📡 API Example
GET /api/vehicles
POST /api/drivers
GET /api/routes

## 🚀 Future Improvements

* Deployment to cloud
* Update Mobile responsive UI
* 
