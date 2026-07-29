# Aravindan Subramanian

**Cloud & DevOps Engineer · AWS**

![Metrics](./github-metrics.svg)

I design, build and operate production-grade AWS platforms. My work covers the full arc: multi-account organization design, infrastructure as code for every resource, containerized workloads, and the testing that proves an environment survives real failures before users ever depend on it.

---

## Core expertise

| Area | What that looks like in practice |
|---|---|
| **Cloud architecture** | Multi-account AWS Organizations with OU guardrails · 3-tier Multi-AZ VPC design · private-subnet workloads with VPC endpoints · edge protection with WAF |
| **Platform engineering** | Everything in CloudFormation, nothing hand-built · ECS Fargate services behind path-routed ALBs · circuit-breaker deployments with automatic rollback · CI/CD with image-scan security gates |
| **Reliability engineering** | Chaos drills with AWS Fault Injection Simulator (full AZ blackhole) · forced Multi-AZ database failover validation · load testing to autoscaling ceilings · SLO-driven alarms and dashboards |
| **Security & governance** | Customer-managed KMS keys across every data store · secrets generated in Secrets Manager, never typed · least-privilege IAM · organization-wide MFA enforcement · budget alarms and automated cost reporting |

## Selected work

- **Built a 14-stack CloudFormation platform** for an AI risk-assessment product — network through WAF through observability, deployable and destroyable with a single script, running in its own isolated AWS account
- **Proved zero-downtime fault tolerance**: killed an entire availability zone and forced a database failover in the same window — 99.93% request success through both, no human intervention, full recovery in minutes
- **Re-architected a monolith** into separate API and SPA containers behind a path-routed load balancer with strict CSP, deployed with zero data loss
- **Stood up a multi-account AWS Organization**: isolated workload accounts, OU-level guardrails, enforced MFA across every human identity, per-account cost visibility

## Toolbox

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-E7157B?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

📍 Canada · Home region: `ca-central-1`
