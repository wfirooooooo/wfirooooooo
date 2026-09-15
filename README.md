# Hi, I'm Fyx WANG 👋

### Senior SRE / Platform Engineer

**Cloud Infrastructure · Kubernetes · DevOps · AI Infrastructure**

10+ years of experience building and operating reliable infrastructure and platform systems across enterprise environments, with a focus on **automation, scalability, reliability, security, and cost optimization**.

I enjoy turning complex infrastructure problems into **simple, automated, observable, and maintainable engineering systems**.

---

## 💼 Professional Experience Highlights

10+ years across **telecom** and **finance** infrastructure teams, spanning operations engineering → SRE → platform engineering:

- **Reliability** — Designed and operated Kubernetes-based platforms at **99.9%+ availability**; led incident response, RCA and disaster-recovery drills
- **Cloud Optimization** — Reduced cloud spend by up to **50%** through architecture optimization, right-sizing and FinOps practices
- **Enterprise Compliance** — Delivered **ISO 27001 / MLPS L3 / CMMI 3** compliance programmes end-to-end
- **AI in Production** — Key contributor to an **LLM-powered intelligent customer service platform** serving production traffic
- **Automation** — Built CI/CD pipelines, IaC workflows and self-service tooling that replaced repetitive manual operations

## 🎓 Education

**MSc, Data Science & Artificial Intelligence** — Hang Seng University of Hong Kong (HSUHK), 2026

- CGPA **3.64 / 4.0** · **Excellence Scholarship** recipient
- Coursework & projects: machine learning, data engineering, data mining, cloud-based ML infrastructure

## 📜 Certifications

![PMP](https://img.shields.io/badge/PMP-Project_Management_Professional-013089?style=flat&logo=pmi&logoColor=white)
![RHCE](https://img.shields.io/badge/RHCE-Red_Hat_Certified_Engineer-EE0000?style=flat&logo=redhat&logoColor=white)
![CISP-SSDP](https://img.shields.io/badge/CISP--SSDP-Security_Specialist-1B6ACB?style=flat)
![HCIA-AI](https://img.shields.io/badge/HCIA--AI-Huawei_Certified_AI_Associate-0091DA?style=flat)
![Gemini](https://img.shields.io/badge/Gemini--Certified-Educator-4285F4?style=flat&logo=google&logoColor=white)

---

## 🚀 Engineering Focus

### ☁️ Cloud & Infrastructure

- AWS / Azure / Alibaba Cloud / Tianyi Cloud
- Cloud Architecture & High Availability
- Infrastructure as Code — Terraform & Ansible
- Networking, IAM & Security
- Capacity Planning & Cost Optimization

### ☸️ Platform Engineering

- Kubernetes / EKS · Docker & Helm
- Multi-Environment Management
- RBAC & Workload Security
- Autoscaling & Resource Management

### 🔄 DevOps & Delivery

- CI/CD — GitHub Actions / Jenkins / GitLab CI / CircleCI
- GitOps & Release Engineering
- Automated Testing & Deployment · DevSecOps

### 📊 SRE & Observability

- SLI / SLO / SLA · Reliability Engineering
- Incident Response & RCA
- Prometheus / Grafana · Logging & Distributed Observability

### 🤖 AI & Data

- AWS SageMaker · Model Training & Serving
- XGBoost / TensorFlow / PySpark
- LLM Application Infrastructure

**Languages:** Python · Go · Rust · Bash

---

## 📈 Selected Impact

| Area | Impact |
| --- | --- |
| **Reliability** | Operated Kubernetes-based platforms with **99.9%+ availability** |
| **Cloud Optimization** | Achieved up to **50% cloud cost reduction** through architecture and resource optimization |
| **Experience** | **10+ years** across SRE, DevOps, Cloud and Platform Engineering |
| **Enterprise Engineering** | Experience with **ISO 27001 / MLPS L3 / CMMI 3** environments |
| **AI Platform** | Designed and implemented cloud-based AI / ML platform capabilities |

---

## 🏗️ Selected Engineering Projects

### 🛰️ Novbot — Intelligent Inspection & Observability Platform

A production-grade infrastructure monitoring platform written in **Rust** — my main open engineering project.

- **Community Edition** (open-source ready): single-binary agent + server, async Rust architecture (Tokio / Axum)
- OS checks (CPU / memory / disk / network) + **8 middleware health checks** (MySQL, PostgreSQL, Redis, MongoDB, Kafka, RabbitMQ, Nginx, Elasticsearch) with per-check timeout and failure isolation
- Alert engine with rule evaluation, **silence windows**, concurrent multi-channel notifications (webhook / SMTP), SQLite persistence
- HTML / Markdown inspection reports, TUI dashboard, systemd integration, **amd64 + arm64** CI releases
- **Enterprise Edition**: distributed Edge→Region architecture (gRPC / NATS JetStream), multi-tenancy, TimescaleDB, compliance engine (127 controls), MCP tooling

**Technologies:** `Rust` `Tokio` `Axum` `SQLx` `gRPC` `NATS` `Docker` `GitHub Actions`

→ [github.com/wfirooooooo/novbot](https://github.com/wfirooooooo/novbot) · enterprise edition in a private repo

---

### 🔬 Predicting Superconductor Critical Temperatures

Cloud ML coursework project: benchmarked **13 classical & deep models** for superconductor critical temperature prediction.

- Best model: **RMSE 8.74 / R² 0.933**
- Deployed on **AWS SageMaker** (ml.m5.xlarge) — both serverless and real-time inference endpoints
- End-to-end pipeline: feature engineering → model selection → cloud deployment

**Technologies:** `Python` `SageMaker` `XGBoost` `TensorFlow` `PySpark`

---

### 🛠️ Engineering Practice Repos

Smaller repositories capturing real operational patterns:

| Repo | What it demonstrates |
| --- | --- |
| [blue-green-pub](https://github.com/wfirooooooo/blue-green-pub) | **Blue-green deployment** on OpenResty (Nginx + Lua + Redis + ZooKeeper) |
| [MySQL-benchmark-chart](https://github.com/wfirooooooo/MySQL-benchmark-chart) | **MySQL performance benchmarking** with sysbench — methodology, scripts & charts |
| [falcon-message](https://github.com/wfirooooooo/falcon-message) | **Alert delivery component** for Open-Falcon monitoring (Go) |
| [Py-MapLine](https://github.com/wfirooooooo/Py-MapLine) | Concurrent line-oriented **text processing tool** (Python) |
| [com6004-datamining](https://github.com/wfirooooooo/com6004-datamining) | Data mining coursework notebooks (Jupyter) |

---

## 🧰 Technology Stack

| Domain | Stack |
| --- | --- |
| **Cloud** | AWS · Azure · Alibaba Cloud · Tianyi Cloud |
| **IaC** | Terraform · Ansible |
| **Containers & Platform** | Docker · Kubernetes · EKS · Helm |
| **CI/CD** | GitHub Actions · Jenkins · GitLab CI · CircleCI |
| **Observability** | Prometheus · Grafana · ELK · OpenTelemetry · Open-Falcon |
| **Programming** | Python · Go · Rust · Bash |
| **Data & AI** | SageMaker · XGBoost · TensorFlow · PySpark · Hadoop · LLM |
| **OS** | Linux (RHEL · Ubuntu) |

---

## 🧠 Engineering Principles

I focus on engineering systems rather than individual tools.

**Reliability First** — design for failure: SLI/SLO-driven engineering, failure isolation, graceful degradation, disaster recovery.

**Infrastructure as Code** — version controlled, reproducible, reviewable, testable, automated.

**Automation Over Manual Operations** — CI/CD, self-service platforms, automated validation and recovery.

**Observability as a Design Requirement** — metrics, logs, traces and alerts designed together with the application and platform.

**Security by Default** — least-privilege IAM, RBAC, secrets management, image scanning, compliance controls.

**Cost Is an Engineering Metric** — balance **Reliability × Performance × Security × Cost**, not any single dimension in isolation.

---

## 🤝 Connect

- 📍 Hong Kong (NT) · Open to Senior SRE / Platform / AI-Infra roles
- 🗣️ Mandarin (Native) · English (Fluent) · Cantonese (Basic)
- 🔗 [LinkedIn — fair-walker](https://linkedin.com/in/fair-walker)

---

<p align="center">
  <i>Build it. Automate it. Observe it. Improve it.</i>
</p>
