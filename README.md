# TheCodex Platform

> Building a production-inspired Platform Engineering lab from scratch.

## 🚀 Overview

TheCodex Platform is a long-term platform engineering project focused on designing, building, and operating a modern self-hosted platform using industry best practices.

Rather than simply hosting applications, this project aims to replicate the workflows, tooling, and operational mindset used by modern Platform Engineering and DevOps teams.

Every component of the platform is built with automation, Infrastructure as Code, GitOps, observability, and security in mind.

---

## 🎯 Vision

Create a self-hosted platform that serves as:

* A personal cloud
* A learning laboratory
* A Platform Engineering portfolio
* A production-like Kubernetes environment
* A place to experiment safely with modern cloud-native technologies

The goal is not simply to run services, but to understand *why* each technology exists and how they work together.

---

## 🏗️ Architecture

The platform will evolve in phases.

```text
GitHub
    │
GitHub Actions
    │
Container Registry
    │
Argo CD
    │
k3s Kubernetes
    │
Traefik
    │
Cloudflare Tunnel
    │
thecodex.in
    │
──────────────────────────────
Platform Services
Applications
Monitoring
AI
Personal Cloud
```

---

## 📁 Repository Structure

```text
.
├── applications/
├── assets/
├── config/
├── docs/
├── infrastructure/
├── platform/
├── tests/
└── .github/
```

### Directory Overview

| Directory         | Purpose                                                                 |
| ----------------- | ----------------------------------------------------------------------- |
| `applications/`   | Applications deployed on the platform                                   |
| `platform/`       | Shared platform services (Traefik, Argo CD, monitoring, etc.)           |
| `infrastructure/` | Infrastructure provisioning, automation, Terraform, Ansible and scripts |
| `config/`         | Shared configuration files                                              |
| `docs/`           | Documentation, architecture and ADRs                                    |
| `assets/`         | Images, diagrams and screenshots                                        |
| `tests/`          | Validation and automated tests                                          |
| `.github/`        | GitHub Actions, templates and repository automation                     |

---

## 🛠️ Planned Technology Stack

### Platform

* Docker
* Kubernetes (k3s)
* Argo CD
* Traefik
* Cloudflare Tunnel

### CI/CD

* GitHub Actions
* GitHub Container Registry
* GitOps

### Infrastructure

* Terraform
* Ansible
* Bash
* PowerShell

### Observability

* Grafana
* Prometheus
* Loki
* Uptime Kuma

### Applications

* Homepage
* Gitea
* Immich
* Nextcloud
* Paperless-ngx
* AI services

---

## 🗺️ Roadmap

### Sprint 0 — Foundation

* [x] Repository setup
* [x] SSH authentication
* [x] Project structure
* [ ] README
* [ ] Repository standards
* [ ] Initial GitHub Actions workflow

### Sprint 1 — Docker Platform

* [ ] Docker installation
* [ ] Networking
* [ ] Volumes
* [ ] Traefik

### Sprint 2 — Secure Access

* [ ] Cloudflare Tunnel
* [ ] HTTPS
* [ ] Authentication

### Sprint 3 — CI/CD

* [ ] GitHub Actions
* [ ] Build pipelines
* [ ] Container registry
* [ ] Automated deployments

### Sprint 4 — Platform Services

* [ ] Monitoring
* [ ] Logging
* [ ] Dashboards
* [ ] Backup strategy

### Sprint 5 — Kubernetes

* [ ] k3s
* [ ] Helm
* [ ] Ingress

### Sprint 6 — GitOps

* [ ] Argo CD
* [ ] GitOps workflows
* [ ] Progressive deployments

---

## 📜 Engineering Principles

* Git is the single source of truth.
* Everything is managed as code.
* Automate repetitive work.
* Keep documentation close to the code.
* Prefer simple, maintainable solutions.
* Build incrementally and understand every component.

---

## 🎓 Learning Objectives

This project is designed to gain practical experience with:

* Platform Engineering
* Kubernetes
* GitOps
* CI/CD
* Infrastructure as Code
* Cloud-native technologies
* Observability
* Security
* Automation

---

## 🤝 Contributing

This project is primarily a personal engineering laboratory, but ideas, discussions, and feedback are always welcome.

---

## 📄 License

This project is licensed under the MIT License.

