# Hi, I'm Ahmed Boudouh 

**Cloud & DevOps Developer** · Azure · Terraform · Kubernetes · CI/CD
2026 Graduate — Dean's Honours · Sherbrooke, Québec 🇨🇦

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

---

I'm an IT professional with **7+ years of hands-on experience** in network setup, Windows support, ERP configuration and custom application development — now specialized in **cloud infrastructure and DevOps**.

In 2026 I graduated from Algonquin College with two credentials — a **Computer Programming Diploma** and a **Post-Graduate Certificate in Cloud Computing and Operations** — both with honours and a place on the Dean's Honours List. Through intensive academic and personal projects, I've designed and deployed multi-environment Azure infrastructure with Terraform, containerized microservices on Azure Kubernetes Service, event-driven serverless pipelines, and end-to-end GitHub Actions CI/CD.

I'm looking for a **junior Cloud/DevOps role** (Sherbrooke on-site or remote across Québec) where I can contribute from day one and keep growing. Trilingual: French · English · Arabic.

---

## 🛠️ Technical Skills

**Cloud & Platforms (Azure)**
Azure Kubernetes Service (AKS) · Azure Functions · Container Apps · Service Bus · Container Registry · Key Vault · PostgreSQL Flexible Server · Storage · IAM

**Infrastructure as Code**
Terraform · Terratest · TFLint

**CI/CD & Containers**
GitHub Actions · Git/GitHub · Docker · Docker Compose · Kubernetes · Linux

**Cloud Migration**
Workload assessment · Migration strategy (rehost / replatform / rearchitect) · Planning & cutover

**Security**
Authentication & authorization (JWT / OAuth2) · Secrets management (Key Vault) · DevSecOps fundamentals

**Languages**
Python · Bash · HCL · SQL · JavaScript · Java

**Backend & Data**
FastAPI · Node.js / Express · REST APIs · PostgreSQL · MySQL · MongoDB · Redis · Azure Service Bus

**Familiar with**
Azure DevOps · Jenkins · Ansible · Azure Bicep · Pulumi · Go · Rust · React · Vue.js

---

## ☁️ Cloud & DevOps Projects

### [BestBuy Cloud-Native App on AKS](https://github.com/AhmedBoudouh/BestBuy-Cloud-Native-Demo-Application)
Microservices e-commerce platform on **Azure Kubernetes Service**: independently containerized services (store-front, admin, product catalog, order processing) with **MongoDB as a StatefulSet** in-cluster. Orders flow through **Azure Service Bus** to an **Azure Function** that auto-completes low-value orders and routes high-value ones to manual review — automating the routine path while keeping human control where risk is higher. Per-service GitHub Actions CI/CD (build → Docker Hub → rollout).
> AKS · Azure Service Bus · Azure Functions · Docker · Kubernetes · CI/CD · Microservices

### [Multi-Environment Azure Infrastructure as Code](https://github.com/AhmedBoudouh/weatherapp-aks-cicd) · *Group Project*
Provisioned and managed Azure resources with **modular Terraform and remote state**; automated plan/apply via CI/CD for reproducible deployments across environments. Infrastructure quality enforced with **TFLint** (static analysis) and **Terratest** (automated infrastructure tests).
> Terraform · HCL · Azure · Remote State · Terratest · TFLint · CI/CD

### [Serverless Expense-Approval — Durable Functions vs Logic Apps](https://github.com/AhmedBoudouh/azure-serverless-functions/tree/main/CST8917-FinalProject-AhmedBoudouh)
Implemented the *same* human-in-the-loop approval workflow **two ways** — Azure **Durable Functions** (Python v2) and **Logic Apps + Service Bus** — then compared them across development experience, testability, error handling, human interaction, observability, and cost, with a reasoned recommendation. Demonstrates client/orchestrator/activity-chaining and the `wait_for_external_event` + durable-timer pattern.
> Python · Azure Durable Functions · Logic Apps · Service Bus · Serverless · Event-Driven

### [Azure Cloud Migration & Zero Trust Landing Zone](https://github.com/AhmedBoudouh/CST8913-Cloud-Migration)
Cloud migration strategy work — workload assessment and lift-and-shift vs. replatform vs. rearchitect analysis — plus a **Zero Trust landing zone** design (hub-and-spoke, Entra ID Conditional Access, PIM, RBAC, Azure Policy) for a healthcare scenario under HIPAA/GDPR/PIPEDA.
> Azure · Cloud Migration · Zero Trust · Landing Zone · Architecture

---

## 💻 Full-Stack & Security Projects

### [WCAG Learning Platform](https://github.com/AhmedBoudouh/wcag-accessibility-webapp) · *Group Project*
Full-stack platform where developers practice WCAG 2.1 AA rules by fixing HTML/CSS, validated in real time by a backend engine with scoring and progress tracking. **React + TypeScript** frontend; **FastAPI** backend with async SQLAlchemy and JWT/OAuth2; PostgreSQL 15 + Redis 7; fully containerized with **Docker Compose**; deployed to Azure with **Terraform** (Container Apps, PostgreSQL Flexible Server, ACR, Key Vault) and GitHub Actions CI/CD.
> React · TypeScript · FastAPI · PostgreSQL · Redis · Docker Compose · Terraform · Azure

### [Secure Access Control System](https://github.com/AhmedBoudouh/portfolio/tree/main/secure-access-control-system)
Independently designed and built a simulation of a secure access-control system in Python — card-based identity verification, OTP authentication, protection of PIN/OTP data, and per-zone authorization. All logic and architecture built from scratch.
> Python · OTP · Security · Access Control

---

## 👔 Professional Background

Before Canada, I spent **15+ years in business leadership, including 7+ years delivering hands-on IT services**:

- **Presto Office** — deployed and supported IT infrastructure for **200+ recurring business clients**: 50+ LAN deployments (routers, switches, Wi-Fi, cabling), Windows workstation setup and troubleshooting, multi-user **ERP** (Sage) configuration and user training, and custom **VBA** applications (e.g. an appointment system for a medical clinic, a sample-intake/results-tracking system for a medical lab). Advanced hardware upgrades, data recovery, and BIOS-level troubleshooting. Managed and trained a team of 5–10.

This background is why I'm not a typical new grad: I understand the network and systems layer beneath the cloud abstractions, and I've delivered under real business constraints.

---

## 🚧 Currently Building & Learning

- **[LMS Project](https://github.com/AhmedBoudouh/LMS-project)** *(in progress)* — a Learning Management System built as a practical exploration of **working effectively with AI as a development partner**: my own product idea, AI-accelerated implementation, every output reviewed and validated.
- **AZ-104** — studying toward the Microsoft Azure Administrator certification.

<sub>Additional academic & personal work (Java web app, accessible SPA, Android/REST) lives in my [pinned repositories](https://github.com/AhmedBoudouh?tab=repositories).</sub>

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmed-boudouh)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ahmedboudouh84@gmail.com)

*Open to junior Cloud/DevOps opportunities across Québec — feel free to reach out!*
