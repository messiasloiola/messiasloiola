<!--
  Este README vai no repositório: github.com/messiasloiola/messiasloiola
  GitHub renderiza automaticamente na página do seu perfil.
  O nome do repositório precisa ser EXATAMENTE igual ao seu username.
-->

<h1 align="center">Olá, eu sou o Messias 👋</h1>

<p align="center">
  <b>Platform Engineer · Cloud & DevOps · AI-Augmented Infrastructure</b><br/>
  <sub>Brasília, Brasil · 7+ anos construindo infraestrutura crítica</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/messias-loiola"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:messiasloiolas@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## Sobre

Cuido sozinho da plataforma AWS multi-account da **Ticket and Go** (SaaS multi-tenant de bilheteria digital) — plataforma com **elasticidade obrigatória pra absorver bursts de venda concentrados em janelas curtas** (lançamentos de evento, abertura de lotes). No dia-a-dia trabalho com infraestrutura Terraform-first, segurança em camadas (**PCI-DSS Nível 4**, **LGPD**), connection pooling em escala, migrações de banco blue/green sem downtime e FinOps.

Antes disso, foram 5+ anos operando infra on-premises e híbrida no setor público brasileiro — Banco do Brasil, Polícia Militar do DF e Ministério da Educação — e construção de plataformas AWS de porte médio na Heiliger Tech.

## No que estou trabalhando agora

- 🏗️ Migrando estado monolítico em ECS pra **arquitetura serverless event-driven** (Lambda + Aurora Serverless v2 + RDS Proxy + EventBridge + SQS FIFO/DLQ)
- 🔐 Modelando um **padrão canônico de RBAC em PostgreSQL** (Group Roles NOLOGIN + Owner Role) replicável em ambientes multi-account
- 🌐 Substituindo port-forward via SSM por **Cloudflare Zero Trust** (WARP + Tunnel + SAML IdP via AWS SSO)
- 🤖 Operando infra de produção com **workflow LLM-assisted** (Claude Code + sub-agentes customizados + MCP servers + rules-as-code versionadas)

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

**Dados & Mensageria**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Observabilidade**

![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

## Open Source

Módulos publicados — destilações sanitizadas de padrões reais de produção:

- [`terraform-aws-multi-account-foundation`](https://github.com/messiasloiola/terraform-aws-multi-account-foundation) — base de VPC opinionada pra setups AWS multi-account: 4 tiers de subnet × N AZs, NAT em HA, VPC Flow Logs, default SG locked down
- [`terraform-aws-rds-proxy-rbac`](https://github.com/messiasloiola/terraform-aws-rds-proxy-rbac) — RDS Proxy + Secrets Manager multi-consumer + templates SQL canônicos de **RBAC PostgreSQL** (PCI-DSS R7+R8): TLS+SCRAM, password rotation out-of-band, Group Roles NOLOGIN
- 🚧 Próximos: reusable workflows GitHub Actions com OIDC, playbooks de platform engineering

## Certificações

- Gravitee Event-native API Management — **Professional** (2025)
- Gravitee Event-native API Management — **Foundations** (2025)
- Kubernetes / Linux / Docker Essentials — LINUXtips (2024)
- AWS Certified **Cloud Practitioner** (2023)

## Contato

- 💬 [LinkedIn](https://www.linkedin.com/in/messias-loiola) — melhor lugar pra trocar ideia
- 📬 [messiasloiolas@gmail.com](mailto:messiasloiolas@gmail.com)

---

<sub>Este perfil está em construção — a maior parte do meu trabalho vive em repositórios privados de infraestrutura. Os módulos open-source acima são destilações sanitizadas de padrões que uso em produção.</sub>
