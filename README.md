# TaskFlow Pro — Full Stack Task Management Application

A modern task management web application built with **React, Vite, Java, and Spring Boot**. TaskFlow Pro helps users organize tasks, manage priorities, track progress, and improve productivity through a clean dashboard.

##  Live Demo

**Frontend:** https://taskflow-pro-sandy-eta.vercel.app/

**Backend API:** https://taskflow-backend-wllt.onrender.com/api/tasks

##  Features

-  Create and manage tasks
-  Mark tasks as completed
-  Organize tasks by category and priority
-  Track task progress through a dashboard
-  Connect frontend and backend using REST APIs
-  Responsive user interface
-  Fast frontend development with Vite

##  Tech Stack

**Frontend**
- React.js
- Vite
- JavaScript
- HTML5
- CSS3

**Backend**
- Java
- Spring Boot
- REST API
- Maven
- H2 Database

**Tools & Deployment**
- Git & GitHub
- Vercel — Frontend deployment
- Render — Backend deployment
- VS Code

##  Project Structure

```text
taskflow-pro-fullstack/
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── Dockerfile
└── README.md
```

##  Getting Started

### Prerequisites

- Node.js and npm
- Java JDK
- Maven (or the included Maven Wrapper)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/priyankanadendla/taskflow-pro-fullstack1.git
cd taskflow-pro-fullstack1
```

### 2. Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in your terminal, usually `http://localhost:5173`.

### 3. Run the Backend

Open another terminal:

```bash
cd backend
```

On Windows, run:

```powershell
.\mvnw.cmd spring-boot:run
```

The backend typically starts at `http://localhost:8080`, depending on the application configuration.

### 4. API Endpoint

```text
GET http://localhost:8080/api/tasks
```

For local development, configure the frontend API URL to point to your local backend.

##  Deployment

- **Frontend:** Deployed on Vercel
- **Backend:** Deployed on Render
- **API Communication:** REST API

##  Project Objective

The objective of TaskFlow Pro is to demonstrate full-stack web development skills, including responsive frontend development, REST API integration, backend development with Spring Boot, database integration, version control, and deployment.

##  Author

**Priyanka Nadendla**

B.Tech — Information Technology

GitHub: [@priyankanadendla](https://github.com/priyankanadendla)

---

If you find this project interesting, consider giving the repository a star!# taskflow-pro-fullstack

