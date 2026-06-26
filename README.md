# TheCodex Platform

> **Learning Platform Engineering by building a production-inspired self-hosted platform, one sprint at a time.**

> **Status:** 🚧 Under Active Development

---

## 🚀 Overview

TheCodex Platform is a long-term Platform Engineering project built to design, automate, and operate a modern self-hosted infrastructure using production-inspired engineering practices.

The goal is not simply to host applications. Instead, this repository documents the complete journey of building a platform from the ground up while learning the technologies, workflows, and operational principles used by modern engineering teams.

Every decision is made intentionally, documented, and automated whenever possible.

---

# 🎯 Vision

TheCodex Platform is designed to become:

* ☁️ A personal cloud
* 🧪 A platform engineering laboratory
* 📚 A continuous learning project
* 💼 A professional portfolio
* 🚀 A production-inspired Kubernetes environment
* 🤖 A playground for automation and AI

The objective is to understand not only **how** technologies work, but also **why** they exist and when they should be used.

---

# 🚧 Current Sprint

## Sprint 0 – Foundation

### Completed

* [x] Git repository created
* [x] SSH authentication
* [x] Repository structure
* [x] Initial README
* [x] Git workflow established

### In Progress

* [ ] Repository standards
* [ ] GitHub Actions
* [ ] Architecture Decision Records (ADRs)

---

# 🏗️ High-Level Architecture

The platform will evolve over multiple phases.

```text
                    GitHub
                       │
                GitHub Actions
                       │
           GitHub Container Registry
                       │
                    Argo CD
                       │
                 Kubernetes (k3s)
                       │
                    Traefik
                       │
              Cloudflare Tunnel
                       │
                  thecodex.in
                       │
        ┌──────────────┼──────────────┐
        │              │              │
   Platform        Applications    Monitoring
    Services
```

This architecture will grow incrementally throughout the project rather than being implemented all at once.

---

# 📂 Repository Structure

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

| Directory         | Description                                                      |
| ----------------- | ---------------------------------------------------------------- |
| `applications/`   | Applications deployed on the platform                            |
| `platform/`       | Shared platform services such as Traefik, Argo CD and monitoring |
| `infrastructure/` | Terraform, Ansible, Docker and automation scripts                |
| `config/`         | Shared configuration files                                       |
| `docs/`           | Documentation, architecture and ADRs                             |
| `assets/`         | Images, diagrams and screenshots                                 |
| `tests/`          | Validation and automated tests                                   |
| `.github/`        | GitHub workflows and repository automation                       |

---

# 🛠️ Technology Stack

## Platform

* Docker
* Kubernetes (k3s)
* Argo CD
* Traefik
* Cloudflare Tunnel

## CI/CD

* GitHub Actions
* GitHub Container Registry
* GitOps

## Infrastructure

* Terraform
* Ansible
* Bash
* PowerShell

## Observability

* Grafana
* Prometheus
* Loki
* Uptime Kuma

## Applications

* Homepage
* Gitea
* Nextcloud
* Immich
* Paperless-ngx
* AI Services

---

# 🤔 Why These Technologies?

| Technology        | Purpose                                      |
| ----------------- | -------------------------------------------- |
| Docker            | Application containerization                 |
| k3s               | Lightweight Kubernetes cluster               |
| Argo CD           | GitOps continuous delivery                   |
| Traefik           | Reverse proxy and ingress                    |
| GitHub Actions    | Continuous Integration                       |
| Terraform         | Infrastructure as Code                       |
| Cloudflare Tunnel | Secure remote access without port forwarding |
| Grafana           | Visualization and dashboards                 |
| Prometheus        | Metrics collection                           |
| Loki              | Centralized logging                          |

Every technology introduced into the platform must solve a real problem and have a clear purpose.

---

# 🗺️ Roadmap

## Sprint 0 — Foundation

Build the repository, documentation, engineering standards and CI foundation.

---

## Sprint 1 — Docker Platform

Create a container platform using Docker, networking, volumes and Traefik.

---

## Sprint 2 — Secure Access

Securely expose services through Cloudflare Tunnel with HTTPS and authentication.

---

## Sprint 3 — Continuous Integration & Delivery

Build automated pipelines using GitHub Actions for testing, image builds and deployments.

---

## Sprint 4 — Observability

Deploy a complete monitoring stack with Grafana, Prometheus, Loki and Uptime Kuma.

---

## Sprint 5 — Kubernetes

Migrate workloads to k3s and introduce Helm and Kubernetes-native deployments.

---

## Sprint 6 — GitOps

Adopt Argo CD to automate deployments and manage platform state through Git.

---

# 🌿 Git Workflow

All changes follow a Git workflow inspired by professional engineering teams.

```text
main
│
├── feature/*
├── docs/*
├── ci/*
├── build/*
└── fix/*
```

Every change is developed in its own branch and merged through a Pull Request.

---

# 📜 Engineering Principles

* Git is the single source of truth.
* Everything is managed as code.
* Automate repetitive work.
* Documentation evolves with the platform.
* Prefer simple and maintainable solutions.
* Learn by building.
* Every tool should solve a real problem.
* Incremental improvements are preferred over large rewrites.

---

# 🎓 Learning Objectives

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
* Production-inspired engineering practices

---

# 🤝 Contributing

TheCodex Platform is primarily a personal engineering laboratory.

Suggestions, ideas and constructive feedback are always welcome.

---

# 📄 License

This project is licensed under the MIT License.

