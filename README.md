# 🚀 BrowserHub – End-to-End DevOps CI/CD Project

BrowserHub is a simple web application developed to demonstrate a complete DevOps CI/CD workflow using GitHub, Jenkins, Docker, Kubernetes, Bash scripting, and AWS EC2.

---

## 📌 Project Overview

This project demonstrates how to automate the software delivery process using modern DevOps tools.

The application is:

- Developed using HTML & CSS
- Containerized using Docker
- Automated using Jenkins CI/CD Pipeline
- Deployed using Kubernetes
- Hosted on AWS EC2
- Monitored using Bash Scripts

---

## 🛠 Tech Stack

- HTML5
- CSS3
- Git
- GitHub
- Docker
- Jenkins
- Kubernetes (Minikube)
- AWS EC2 (Ubuntu)
- Bash Scripting
- Nginx

---

## 📂 Project Structure

```
BrowserHub/
│
├── index.html
├── style.css
├── Dockerfile
├── Jenkinsfile
├── deployment.yaml
├── service.yaml
├── health.sh
├── README.md
└── screenshots/
```

---

# ⚙️ CI/CD Workflow

```
Developer
      │
      ▼
 GitHub Repository
      │
      ▼
 Jenkins Pipeline
      │
      ▼
 Docker Build
      │
      ▼
 Docker Container
      │
      ▼
 Kubernetes Deployment
      │
      ▼
 BrowserHub Application
```

---

# 🚀 Features

- Responsive BrowserHub Landing Page
- Dockerized Nginx Web Server
- Jenkins Automated Build Pipeline
- Kubernetes Deployment
- Bash Health Monitoring Script
- AWS EC2 Deployment
- GitHub Version Control

---

# 📦 Docker Commands

Build Docker Image

```bash
docker build -t browserhub .
```

Run Docker Container

```bash
docker run -d --name browserhub -p 8081:80 browserhub
```

List Containers

```bash
docker ps
```

Stop Container

```bash
docker stop browserhub
```

Remove Container

```bash
docker rm browserhub
```

---

# ☸ Kubernetes Commands

Deploy Application

```bash
kubectl apply -f deployment.yaml
```

Deploy Service

```bash
kubectl apply -f service.yaml
```

Check Pods

```bash
kubectl get pods
```

Check Services

```bash
kubectl get svc
```

Open Application

```bash
minikube service browserhub-service
```

---

# 🔧 Jenkins Pipeline

Pipeline Stages

- Checkout Source Code
- Build Docker Image
- Run Docker Container
- Deploy to Kubernetes
- Verify Deployment

---

# 🖥 AWS EC2 Deployment

Clone Repository

```bash
git clone https://github.com/silar512/-BrowserHub---DevOps-CI-CD-Project.git
```

Navigate to Project

```bash
cd BrowserHub
```

Build Docker Image

```bash
docker build -t browserhub .
```

Run Container

```bash
docker run -d -p 80:80 browserhub
```

Access Application

```
http://<EC2-PUBLIC-IP>
```

Example

```
http://52.73.61.164
```

---

# 📊 Health Monitoring Script

Run

```bash
chmod +x health.sh

./health.sh
```

The script displays

- Current Date & Time
- CPU Usage
- Memory Usage
- Disk Usage
- Running Docker Containers
- Kubernetes Pod Status

---

# 📷 Screenshots

## BrowserHub Home Page

Add your application screenshot here.

## Jenkins Pipeline

Add successful Jenkins build screenshot.

## Docker Container

Add Docker running container screenshot.

## Kubernetes Deployment

Add kubectl get pods screenshot.

## AWS EC2 Deployment

Add EC2 application screenshot.

---

# 📈 Future Enhancements

- GitHub Webhooks
- Docker Hub Integration
- Terraform Infrastructure
- Ansible Automation
- Prometheus Monitoring
- Grafana Dashboard
- HTTPS using Nginx
- Jenkins Shared Library

---

# 👨‍💻 Author

**Shaik Silar**

GitHub

https://github.com/silar512

LinkedIn

https://www.linkedin.com/in/shaik-silar
