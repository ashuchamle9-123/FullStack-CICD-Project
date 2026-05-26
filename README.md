 🚀 FullStack CI/CD Project

This project demonstrates a complete CI/CD pipeline for a Full Stack Application using React, Node.js, Docker, GitHub Actions, DockerHub, and AWS EC2.

---

# 📂 Project Structure

```bash
FullStack-CICD-Project/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── Dockerfile
│   ├── package.json
│   └── .dockerignore
│
├── backend/
│   ├── server.js
│   ├── Dockerfile
│   ├── package.json
│   └── .dockerignore
│
├── .github/
│   └── workflows/
│       └── cicd.yml
│
├── docker-compose.yml
└── README.md
```

---

# 🛠️ Technologies Used

* React.js
* Node.js
* Docker
* Docker Compose
* GitHub Actions
* DockerHub
* AWS EC2

---

# ⚙️ What We Implemented

## ✅ Frontend Setup

* Created React frontend application
* Installed frontend dependencies
* Built frontend using npm
* Dockerized frontend application

---

## ✅ Backend Setup

* Created Node.js backend server
* Installed backend dependencies
* Dockerized backend application

---

## ✅ Docker Integration

* Created Dockerfiles for frontend and backend
* Built Docker images
* Used Docker Compose for container management

---

## ✅ GitHub Actions CI/CD Pipeline

Implemented automated pipeline for:

* Installing dependencies
* Building frontend
* Building Docker images
* Pushing Docker images to DockerHub

---

# 🐳 Docker Commands Used

## Build Frontend Image

```bash
docker build -t frontend-app ./frontend
```

## Build Backend Image

```bash
docker build -t backend-app ./backend
```

## Run Containers

```bash
docker compose up -d
```

---

# ☁️ AWS EC2 Deployment

Project deployed on AWS EC2 Ubuntu instance.

Services used:

* EC2 Instance
* Security Groups
* Docker Engine
* Docker Compose

---

# 📸 Screenshots

## GitHub Actions Pipeline

```md
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/8f13ee97-2ff5-460f-b3aa-8ce0daa829c7" />#
```

## Docker Containers Running

```md
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c44e1e95-29bb-483c-be1a-8bf93e946cca" />

```

## Frontend Application

```md
<img width="1920" height="1080" alt="FullStack-CICD-Project frontend run sucessfully" src="https://github.com/user-attachments/assets/3113b4f1-5f51-4c51-b497-c305eb6b998a" />

```

---

# 👨‍💻 Author

Ashu Chamle
CI/CD Pipeline Updated
