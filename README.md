# Employee Management System

A production-style DevOps project built with Spring Boot, MySQL, Docker, Kubernetes, GitLab CI/CD, Helm, ArgoCD, Prometheus and Grafana.

## Tech Stack

- Java 17
- Spring Boot
- MySQL
- Docker
- Kubernetes
- GitLab CI/CD
- Helm
- ArgoCD
- Prometheus
- Grafana

## Features

- Employee CRUD API
- Validation
- Global Exception Handling
- Swagger UI
- Health Checks
- Metrics
- Rolling Updates

## Project Structure

```text
app/
manifests/
helm/
argocd/
gitlab/
docs/
```

## Architecture

Developer
   ↓
GitLab
   ↓
Docker Build
   ↓
Trivy Scan
   ↓
Docker Hub
   ↓
GitOps Branch
   ↓
ArgoCD
   ↓
Kubernetes
   ↓
Prometheus/Grafana

## CI/CD Pipeline

(To be added)

## Monitoring

(To be added)