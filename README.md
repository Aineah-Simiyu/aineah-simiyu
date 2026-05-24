# Aineah Musuya

**Senior Full-Stack Software Engineer · Data Engineer**  
Nairobi, Kenya · [LinkedIn](https://linkedin.com/in/aineah-musuya-a47289145) · [Portfolio](https://aineah-musuya-portfolio-0izh5a.vercel.app/) · aineamusuya@gmail.com

---

## About

I build production SaaS systems and data pipelines — not prototypes.

6+ years across fintech, edtech, and data-intensive platforms. I work primarily in **Node.js**, **Python**, and **Next.js**, and I'm hands-on with the full lifecycle: architecture, APIs, ETL pipelines, workflow orchestration, deployments, and infrastructure. I founded **[Quaxt Labs](https://quaxt.co.ke)** in Nairobi where I'm currently building a portfolio of five live SaaS products.

My engineering philosophy: layered, testable architecture with zero shortcuts — every system I ship is designed to be maintained by someone else at 2am.

---

## What I'm Building

| Product | What It Does | Stack |
|---|---|---|
| **[Swifta](https://swifta.co.ke)** | M-Pesa payment infrastructure — STK Push, embeddable checkout SDK, signed webhooks | Node.js, MongoDB, BullMQ, Redis |
| **[Qboot](https://qboot.co.ke)** | Multi-tenant bootcamp management — cohorts, enrollment, real-time chat, M-Pesa billing | Next.js, Node.js, MongoDB, Socket.io |
| **[Qbeam](launching soon)** | Multi-channel messaging SaaS — WhatsApp, SMS, Email, Telegram, FCM Push | Node.js, BullMQ, Baileys, Africa's Talking |
| **[Q-learn](launching soone)** | Enterprise LMS — HLS adaptive video, dynamic RBAC, multi-tenant, plan gating | Node.js, MinIO, FFmpeg, MongoDB |
| **Rova** | KES-to-crypto on/off ramp aggregator — pure broker, Swifta inbound, Yellow Card rails | Node.js, MongoDB, BullMQ |

---

## Engineering Focus Areas

**Full-Stack Software Engineering**
- RESTful API design with modular layered architecture (Model → Repo → Service → Controller → Route)
- Multi-tenant SaaS systems with dynamic RBAC, session auth, plan gating, and audit trails
- Real-time systems: Socket.io, Redis pub/sub, BullMQ job queues with dead-letter and failover
- Server-rendered and SPA frontends: Next.js App Router, React, Tailwind CSS, TanStack Query
- Payment systems: M-Pesa Daraja API (STK Push, C2B, B2C, Paybill), HMAC-signed webhooks

**Data Engineering**
- ETL/ELT pipeline design: ingestion, transformation, validation, reconciliation
- Apache Airflow DAG authoring and task orchestration in production
- Data quality frameworks: anomaly detection, upstream validation, exception reduction
- Python data stack: pandas, scikit-learn, NumPy, Matplotlib, PostgreSQL, Redis
- ML pipeline deployment: Flask model serving, Dockerized inference, PostgreSQL persistence
- Automated reporting: scheduled jobs, stakeholder dashboards, operational KPI tracking

**Infrastructure & DevOps**
- Docker, Docker Swarm, Dokploy, Traefik, Cloudflare DNS
- Tailscale VPN-connected hybrid clusters (VPS manager + bare-metal worker)
- Self-hosted MinIO object storage with presigned URL access control
- Linux server administration, GitHub Actions CI/CD, environment hardening

---

## Selected Work

**Dockerized Healthcare ML Pipeline**  
Flask inference service + Apache Airflow DAG orchestration + PostgreSQL — containerized on a Dokploy/Docker Swarm cluster. Solved Docker volume collision, network isolation, and entrypoint permission issues in production. Airflow manages the full data ingestion and inference schedule.

**Swifta Bank Paybill STK Push**  
Reverse-engineered the Daraja API to execute STK Push flows where the `BusinessShortCode` is Swifta's own credentials and `PartyB` is the target bank paybill — achieving direct competitor feature parity. First implementation of this pattern in a Kenyan multi-tenant payment gateway.

**Q-learn HLS Video Pipeline**  
Raw video uploads → FFmpeg BullMQ worker → adaptive bitrate HLS segments → MinIO storage → Video.js playback. Per-tenant presigned URL access control. Entire transcode pipeline runs asynchronously with job retry and dead-letter handling.

**Swifta Postpaid Billing Engine**  
Designed a billing model that avoids CBK PSP licensing: no wallet, postpaid per-transaction (Free 50tx/mo → Growth KES 2/tx → Scale KES 1/tx after 500), auto-invoiced via STK Push on the 1st of each month with a D+7 → D+14 → D+21 grace cycle. Fully automated with BullMQ workers and MongoDB usage records.

---

## Tech Stack

**Languages:** JavaScript, TypeScript, Python, SQL, Bash  
**Backend:** Node.js, Express, NestJS, Flask, FastAPI  
**Frontend:** Next.js, React, Tailwind CSS, shadcn/ui, Handlebars  
**Data & Pipelines:** Apache Airflow, pandas, scikit-learn, NumPy, PostgreSQL, DBT (working knowledge)  
**Databases:** MongoDB, PostgreSQL, Redis, MySQL, SQLite, Microsoft SQL Server  
**Messaging & Queues:** BullMQ, Socket.io, Kafka (working knowledge), Redis Streams  
**Infrastructure:** Docker, Docker Swarm, Dokploy, Traefik, AWS (S3, EC2), Azure, Cloudflare, MinIO, Nginx  
**ML & Visualization:** TensorFlow, PyTorch, Keras, scikit-learn, Matplotlib, Plotly  
**DevOps:** GitHub Actions, GitLab CI, Git, Linux  

---

## Background

| Role | Company | Period |
|---|---|---|
| Senior Software Engineer & Founder | Quaxt Labs | 2025 – Present |
| Software Developer | Madfun | 2023 – 2025 |
| Software Developer | Riverbank Solutions | 2022 – 2023 |
| Data Analyst | M-Kopa Solar | 2021 – 2022 |
| Junior Software Developer | Ezen Financials | 2019 – 2020 |

---

## Currently

- Scaling **Qboot** and **Swifta** to paying customers across East Africa
- Building out **Rova** — KES-to-crypto with Yellow Card and Kotani Pay rails
- Completing a **Data Engineering** certification at LuxDev
- Open to senior software engineering and data engineering roles (remote or Nairobi-based)

---

*Available for contract work, senior roles, and technical co-founder conversations.*
