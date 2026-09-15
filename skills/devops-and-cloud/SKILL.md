---
name: devops-and-cloud
description: Docker containerization, multi-stage builds, docker-compose orchestration, GitHub Actions CI/CD pipelines, and cloud deployments.
---

# AAS DevOps & Cloud Skill

Use this skill whenever containerizing applications, building CI/CD pipelines, or configuring deployment scripts.

## 🛠 Core Principles
1. **Multi-Stage Docker Builds**: Minimize final container image sizes using minimal base images (`python:3.12-slim` or `alpine`).
2. **Non-Root Execution**: Never run application processes inside containers as `root`. Create a dedicated app user.
3. **Environment Security**: Keep `.env` and secrets OUT of version control. Use `.env.example` templates.
4. **Automated CI/CD**: Create `.github/workflows/ci.yml` for automated linting, testing, and container build checks.
5. **Health Check Endpoints**: Implement `/healthz` or `/ready` endpoints for container orchestrators.