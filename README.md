# 🚀 Zomato Clone – End-to-End DevOps CI/CD Pipeline

<p align="center">
  <img src="https://img.shields.io/badge/DevOps-Project-blue?style=for-the-badge&logo=devops" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
</p>

---

# 📌 Project Overview

This project demonstrates a **production-style DevOps CI/CD pipeline** for deploying a **Zomato Clone Application** on a Kubernetes cluster using modern DevOps tools and AWS infrastructure.

The project covers the complete software delivery lifecycle—from source code management to automated deployment, security scanning, containerization, orchestration, monitoring, and Infrastructure as Code (IaC).

---

# ✨ Features

- Complete CI/CD Pipeline
- Docker Containerization
- Kubernetes Deployment
- Jenkins Automation
- Terraform Infrastructure
- SonarQube Code Quality Analysis
- Trivy Security Scanning
- Prometheus Monitoring
- Grafana Dashboards
- AWS Cloud Deployment
- GitOps Ready
- Production-style Architecture

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Cloud | AWS EC2 |
| SCM | Git, GitHub |
| CI/CD | Jenkins |
| Containerization | Docker |
| Orchestration | Kubernetes |
| IaC | Terraform |
| Quality Analysis | SonarQube |
| Security | Trivy |
| Monitoring | Prometheus |
| Visualization | Grafana |
| Web Server | Nginx |
| OS | Ubuntu Linux |

---

# 📂 Project Structure

```
.
├── Dockerfile
├── Jenkinsfile
├── deployment.yaml
├── service.yaml
├── terraform/
├── kubernetes/
├── monitoring/
├── src/
├── assets/
└── README.md
```

---

# ⚙️ DevOps Workflow

```
Developer
      │
      ▼
 GitHub Repository
      │
      ▼
 Jenkins Pipeline
      │
      ├──────────────► SonarQube Scan
      │
      ├──────────────► Trivy Scan
      │
      ▼
 Docker Build
      │
      ▼
 Docker Image
      │
      ▼
 Kubernetes Cluster
      │
      ▼
 Zomato Application
      │
      ▼
 Prometheus
      │
      ▼
 Grafana Dashboard
```

---

# 🏗 Architecture

```text
                +----------------+
                |     GitHub     |
                +--------+-------+
                         |
                         |
                  Webhook Trigger
                         |
                +--------▼-------+
                |    Jenkins     |
                +--------+-------+
                         |
      +------------------+------------------+
      |                                     |
SonarQube Analysis                   Trivy Scan
      |                                     |
      +------------------+------------------+
                         |
                    Docker Build
                         |
                    Docker Image
                         |
                  Kubernetes Cluster
                         |
                Zomato Clone Application
                         |
              +----------+-----------+
              |                      |
        Prometheus              Grafana
```

---

# 🚀 CI/CD Pipeline

### Stage 1

- Pull Source Code

### Stage 2

- Build Application

### Stage 3

- SonarQube Code Analysis

### Stage 4

- Security Scan using Trivy

### Stage 5

- Docker Image Build

### Stage 6

- Push Image

### Stage 7

- Deploy to Kubernetes

### Stage 8

- Verify Deployment

### Stage 9

- Monitor using Prometheus & Grafana

---

# ☁ AWS Infrastructure

The infrastructure is provisioned using **Terraform**.

Resources include:

- EC2 Instance
- Security Groups
- IAM Roles
- VPC
- Internet Gateway
- Route Tables
- Kubernetes Worker Node

---

# 🐳 Docker

Build Image

```bash
docker build -t zomato-clone .
```

Run Container

```bash
docker run -d -p 80:80 zomato-clone
```

---

# ☸ Kubernetes

Deploy Application

```bash
kubectl apply -f deployment.yaml
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

---

# 📊 Monitoring

Prometheus collects metrics from:

- Kubernetes Cluster
- Nodes
- Containers
- Jenkins
- Docker

Grafana provides dashboards for:

- CPU Usage
- Memory Usage
- Network
- Pod Status
- Cluster Health

---

# 🔐 Security

Security is implemented using:

- SonarQube
- Trivy
- Docker Best Practices
- Kubernetes RBAC
- IAM Policies

---

# 📈 Project Highlights

✅ Infrastructure as Code

✅ Continuous Integration

✅ Continuous Deployment

✅ Containerization

✅ Kubernetes Orchestration

✅ DevSecOps

✅ Monitoring & Alerting

✅ Production-ready Workflow

---

# 📷 Screenshots
Add screenshots here:
https://github.com/pm-Praveenm/Devops-project-zomato-praveenm/blob/main/Deployment%20of%20Online%20Food%20Ordering%20and%20Delivery%20Application(praveenm).pdf
---

# 📚 Learning Outcomes

- Docker Fundamentals
- Kubernetes Deployments
- Jenkins Pipelines
- Infrastructure as Code
- AWS Cloud
- DevSecOps
- Monitoring & Observability
- CI/CD Automation


<p align="center">

### 💙 Happy Learning & Happy DevOps 🚀

Made with ❤️ using Docker • Kubernetes • Jenkins • AWS • Terraform

</p>
