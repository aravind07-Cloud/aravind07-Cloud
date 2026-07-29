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

---

## 🛠️ Tech Stack

**Cloud & DevOps**

![Cloud & DevOps](https://skillicons.dev/icons?i=aws,terraform,docker,kubernetes,githubactions,jenkins,bash&theme=dark)

**Languages**

![Languages](https://skillicons.dev/icons?i=python,typescript,javascript,go,bash&theme=dark)

**Frontend**

![Frontend](https://skillicons.dev/icons?i=react,vite,html,css,tailwind&theme=dark)

**Backend & Databases**

![Backend](https://skillicons.dev/icons?i=fastapi,nodejs,postgres,redis,nginx&theme=dark)

**Tools & Observability**

![Tools](https://skillicons.dev/icons?i=git,github,linux,vscode,prometheus,grafana&theme=dark)

---

📍 Canada · Home region: `ca-central-1`
