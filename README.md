# 🚀 Project 03 – Dockerized DevOps Portfolio

A production-ready static portfolio website containerized with Docker and deployed using Docker Compose and Nginx.

This project demonstrates how a static web application can be packaged into a Docker image, deployed consistently across environments, and managed using Docker Compose following DevOps best practices.

---

## 📖 Project Overview

The objective of this project was to containerize my personal DevOps portfolio website and create a reproducible deployment environment using Docker.

Instead of serving the website directly from the host machine, the application runs inside an Nginx container, making deployment portable, consistent, and easy to manage.

---

## ✨ Features

* Responsive portfolio website
* Dockerized using a custom Dockerfile
* Nginx as the web server
* Docker Compose deployment
* Health check configuration
* Custom Docker network
* Automatic restart policy
* Clean project structure
* Production-style deployment workflow

---

## 🛠️ Technologies Used

* Docker
* Docker Compose
* Nginx
* HTML5
* CSS3
* JavaScript
* Git
* Linux (Ubuntu)

---

## 📂 Project Structure

```
Project-03-Docker
│
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
├── .gitignore
├── README.md
│
├── docker/
│   └── nginx.conf
│
├── website/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
│
├── diagrams/
│
└── screenshots/
```

---

## 🏗️ Architecture

```
                  User
                   │
                   ▼
              Web Browser
                   │
         http://localhost:8080
                   │
                   ▼
         Docker Engine (Port Mapping)
              8080 ─────► 80
                   │
                   ▼
      Portfolio Container (Nginx)
                   │
                   ▼
      /usr/share/nginx/html/
                   │
                   ▼
         HTML • CSS • JavaScript
```

---

## 🚀 Deployment

Clone the repository:

```bash
git clone https://github.com/usamakhalid212/Project-03-Docker.git
```

Navigate into the project:

```bash
cd Project-03-Docker
```

Build and start the application:

```bash
docker compose up --build -d
```

Open:

```
http://localhost:8080
```

Stop the application:

```bash
docker compose down
```

---

## 📸 Screenshots

* Portfolio Homepage
* Projects Section
* Docker Image Build
* Docker Compose Deployment
* Running Container
* Docker Network
* Project Structure
* Architecture Diagram

---

## 📚 What I Learned

Through this project I gained practical experience with:

* Writing Dockerfiles
* Building Docker images
* Running containers
* Docker Compose
* Container networking
* Health checks
* Image inspection
* Container monitoring
* Nginx container deployment

---

## 🔮 Future Improvements

* Deploy the application to AWS EC2
* Automate deployment using Jenkins
* Provision infrastructure with Terraform
* Configure servers using Ansible
* Deploy on Kubernetes
* Add monitoring with Prometheus and Grafana

---

## 👨‍💻 Author

**Usama Khalid**

