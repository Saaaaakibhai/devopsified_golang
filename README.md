<img width="1536" height="1024" alt="devopsified" src="https://github.com/user-attachments/assets/49a819b8-cc68-4be0-945a-d9c23c499dba" />

# 🚀 Cloud-Native DevOps Platform on AWS EKS

[![AWS](https://img.shields.io/badge/AWS-EKS-orange)]()
[![Kubernetes](https://img.shields.io/badge/Kubernetes-v1.34-blue)]()
[![Docker](https://img.shields.io/badge/Docker-Containerized-blue)]()
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-success)]()
[![ArgoCD](https://img.shields.io/badge/GitOps-ArgoCD-red)]()
[![Helm](https://img.shields.io/badge/Helm-Package%20Manager-blueviolet)]()

## 📖 Overview

Designed and implemented a production-style cloud-native DevOps platform that automates the complete software delivery lifecycle—from source code commit to deployment on Amazon EKS.

The solution integrates containerization, Kubernetes orchestration, Infrastructure Automation, CI/CD pipelines, and GitOps practices to deliver applications reliably, consistently, and with minimal manual intervention.

---

## 🎯 Business Objectives

✔ Automate software delivery

✔ Reduce deployment effort and human error

✔ Enable scalable container orchestration

✔ Implement GitOps-based deployment workflows

✔ Improve deployment consistency and reliability

✔ Demonstrate enterprise-grade DevOps practices

---

## 🏗 Solution Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions CI/CD
    │
    ├── Build
    ├── Test
    ├── Lint
    └── Docker Build
    │
    ▼
Docker Hub Registry
    │
    ▼
Helm Chart Repository
    │
    ▼
ArgoCD GitOps Controller
    │
    ▼
Amazon EKS Cluster
    │
    ▼
AWS Load Balancer
    │
    ▼
End Users
```

---

## ⚙️ Technical Implementation

### Application Layer

* Golang Web Application
* REST-based Web Service
* Static Content Delivery

### Containerization

* Multi-stage Docker Build
* Optimized Container Images
* Docker Hub Registry Integration

### Kubernetes Platform

* Deployment Resources
* Service Resources
* Ingress Resources
* Replica Management
* Service Discovery
* Load Balancing

### Package Management

* Helm Chart Development
* Parameterized Configuration
* Environment-specific Deployments

### CI/CD Pipeline

Implemented a fully automated CI/CD workflow using GitHub Actions:

* Source Code Validation
* Automated Testing
* Static Code Analysis
* Docker Image Build
* Docker Image Push
* Helm Deployment Updates

### GitOps

Implemented continuous delivery using ArgoCD:

* Git as Single Source of Truth
* Automated Synchronization
* Self-Healing Deployments
* Declarative Infrastructure Management

### Cloud Infrastructure

Amazon Web Services (AWS)

* Amazon EKS
* IAM
* Elastic Load Balancer
* Managed Node Groups
* VPC Networking

---

## 🚀 CI/CD & GitOps Workflow

1. Developer pushes code to GitHub
2. GitHub Actions pipeline triggers automatically
3. Application is built and tested
4. Code quality checks are executed
5. Docker image is generated
6. Image is pushed to Docker Hub
7. Helm chart updates deployment configuration
8. ArgoCD detects repository changes
9. ArgoCD synchronizes desired state
10. Amazon EKS updates workloads automatically

---

## 📊 Key Achievements

✅ Built a complete end-to-end DevOps workflow

✅ Automated application deployment pipeline

✅ Successfully deployed workloads on Amazon EKS

✅ Implemented GitOps deployment strategy

✅ Integrated Docker, Kubernetes, Helm, GitHub Actions, and ArgoCD

✅ Exposed application through AWS Load Balancer

✅ Achieved fully automated cloud-native application delivery

---

## 🛠 Technologies Used

| Category           | Technologies      |
| ------------------ | ----------------- |
| Programming        | Golang            |
| Containerization   | Docker            |
| Orchestration      | Kubernetes        |
| Package Management | Helm              |
| CI/CD              | GitHub Actions    |
| GitOps             | ArgoCD            |
| Cloud              | AWS EKS, IAM, ELB |
| Version Control    | Git, GitHub       |
| Operating System   | Ubuntu 24.04 LTS  |

---

## 💡 DevOps Skills Demonstrated

* Linux Administration
* Cloud Computing
* Containerization
* Kubernetes Administration
* Helm Packaging
* GitOps Workflows
* CI/CD Pipeline Design
* AWS Infrastructure
* Application Deployment Automation
* Production Environment Management
* Cloud-Native Architecture

---

## 👨‍💻 Author

### S. M. Mahedi Hasan

Junior Software Engineer | Aspiring DevOps & Cloud Engineer

Focused on building scalable cloud-native platforms, automating software delivery pipelines, and implementing modern DevOps practices using AWS, Kubernetes, GitOps, and CI/CD technologies.

Source Code Credit: https://github.com/iam-veeramalla/go-web-app-devops ||
