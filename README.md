# 🚀 Go Web App - End-to-End DevOps Project

## 📌 Project Overview

This project demonstrates a complete DevOps workflow by deploying a Go Web Application on Amazon EKS using modern DevOps practices and tools.

The project covers containerization, Kubernetes orchestration, Helm packaging, CI/CD automation, cloud deployment, and GitOps-based continuous delivery.

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions
(Build + Test + Lint + Docker Build)
    │
    ▼
Docker Hub
    │
    ▼
Helm Chart
    │
    ▼
ArgoCD (GitOps)
    │
    ▼
Amazon EKS
    │
    ▼
AWS Load Balancer
    │
    ▼
End Users
```

---

## 🔧 Technologies Used

### Application

* Golang

### Containerization

* Docker
* Docker Hub

### Kubernetes

* Kubernetes
* Minikube
* Amazon EKS
* Ingress Controller

### Package Management

* Helm

### CI/CD

* GitHub Actions

### GitOps

* ArgoCD

### Cloud

* AWS IAM
* AWS EKS
* AWS Load Balancer

### Operating System

* Ubuntu 24.04 LTS

---

## ✨ Key Features

* Containerized Go application using Docker
* Kubernetes Deployment, Service, and Ingress
* Helm Chart for application packaging
* Automated CI/CD using GitHub Actions
* Docker image publishing to Docker Hub
* Deployment on Amazon EKS
* AWS Load Balancer integration
* GitOps deployment using ArgoCD
* Automated application synchronization from GitHub

---

## 🚀 CI/CD Workflow

1. Developer pushes code to GitHub
2. GitHub Actions pipeline starts automatically
3. Go application is built and tested
4. Code quality checks are executed
5. Docker image is built
6. Docker image is pushed to Docker Hub
7. Helm manifests are updated
8. ArgoCD detects repository changes
9. ArgoCD synchronizes changes to EKS
10. Application is updated automatically

---

## ☁️ AWS Deployment

### EKS Cluster

* Managed Node Group
* Kubernetes v1.34

### Load Balancer

* AWS Elastic Load Balancer
* Public Application Access

---

## 📊 Skills Demonstrated

* Linux Administration
* Git & GitHub
* Docker
* Kubernetes
* Helm
* GitHub Actions
* CI/CD Automation
* AWS EKS
* AWS IAM
* AWS Load Balancer
* GitOps
* ArgoCD
* Cloud-Native Deployments

---

## 🎯 Project Outcome

Successfully designed and implemented a production-style DevOps workflow that automates application delivery from source code to Kubernetes deployment using CI/CD and GitOps principles.

---

## 👨‍💻 Author

S. M. Mahedi Hasan

Aspiring DevOps & Cloud Engineer
