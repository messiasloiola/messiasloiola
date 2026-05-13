<!--
  This README goes in the repository: github.com/messiasloiola/messiasloiola
  GitHub auto-renders it on your profile page.
  Create the repo with the EXACT same name as your username, then push this file as README.md.
-->

<h1 align="center">Hi, I'm Messias 👋</h1>

<p align="center">
  <b>Platform Engineer · Cloud & DevOps · AI-Augmented Infrastructure</b><br/>
  <sub>Brasília, Brazil · 7+ years building critical infrastructure</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/messias-loiola"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:messiasloiolas@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

I run the AWS multi-account platform at **Ticket and Go** (multi-tenant SaaS ticketing) — a platform that handles **10–50x traffic spikes** during event launches. Day-to-day I think about Terraform-first infrastructure, security in depth (**PCI-DSS Level 4**, **LGPD**), connection pooling at scale, blue/green database migrations and FinOps.

Before that, I spent 5+ years operating on-prem and hybrid infrastructure for the Brazilian public sector — Banco do Brasil, DF Military Police, Ministry of Education — and built mid-size AWS platforms at Heiliger Tech.

## What I'm currently up to

- 🏗️ Migrating a monolithic ECS estate to a **serverless event-driven architecture** (Lambda + Aurora Serverless v2 + RDS Proxy + EventBridge + SQS FIFO/DLQ)
- 🔐 Modeling a **canonical PostgreSQL RBAC pattern** (NOLOGIN Group Roles + Owner Role) across multi-account environments
- 🌐 Replacing SSM port-forwarding with **Cloudflare Zero Trust** (WARP + Tunnel + SAML IdP via AWS SSO)
- 🤖 Operating production infra with an **LLM-assisted workflow** (Claude Code + custom sub-agents + MCP servers + versioned rules-as-code)

## Tech Stack

**Cloud & IaC**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Serverless](https://img.shields.io/badge/Serverless_Framework-FD5750?style=flat&logo=serverless&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Platform**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Observability**

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

## Open Source

Modules and playbooks I'm working on (work in progress):

- 🚧 [`terraform-aws-multi-account-foundation`](https://github.com/messiasloiola/terraform-aws-multi-account-foundation) — opinionated VPC base for multi-account AWS setups: 4-tier subnets × N AZs, HA NAT, VPC Flow Logs, hub-and-spoke-ready
- 🚧 More to come — RDS Proxy + RBAC pattern, GitHub Actions OIDC reusable workflows, platform engineering playbooks

## Certifications

- Gravitee Event-native API Management — **Professional** (2025)
- Gravitee Event-native API Management — **Foundations** (2025)
- Kubernetes / Linux / Docker Essentials — LINUXtips (2024)
- AWS Certified **Cloud Practitioner** (2023)

## Reach me

- 💬 [LinkedIn](https://www.linkedin.com/in/messias-loiola) — best place to chat
- 📬 [messiasloiolas@gmail.com](mailto:messiasloiolas@gmail.com)

---

<sub>This profile is a work in progress — most of what I do lives in private infrastructure repos. The open-source modules above are sanitized distillations of patterns I use in production.</sub>
