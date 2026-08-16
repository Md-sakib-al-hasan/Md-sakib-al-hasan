# 👋 Md Sakib Al Hasan

<div align="center">

## Backend Engineer · System Design · Full-Stack Development

### TypeScript · Node.js · NestJS · Python · PostgreSQL · MongoDB · Redis · Docker · Kubernetes · AWS

<p>
  <a href="mailto:md.sakib.al.hasan.programmer@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Md-sakib-al-hasan">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/md-sakib-al-hasan-46942126b">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

</div>

---

## 🧑‍💻 About Me

I'm a **backend-focused software engineer** who enjoys designing and building reliable, scalable, and production-ready software systems.

My primary ecosystem is **TypeScript + Node.js**, with strong experience across **NestJS, Express.js, PostgreSQL, MongoDB, Prisma, Redis, REST APIs, WebSockets, RabbitMQ, Bull Queue, Docker, Kubernetes, AWS, and CI/CD**.

I also work with **Python, React, Next.js, Redux, Firebase, and modern frontend technologies** when building complete end-to-end products.

I enjoy going beyond simply writing APIs — understanding **how services communicate, how databases behave under load, how background jobs are processed, how systems recover from failures, and how applications are deployed and scaled in production**.

> **Build simple. Design clearly. Automate everything possible. Scale when necessary.**

---

# ⚡ Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ Backend Engineering

- REST API Architecture
- NestJS & Express.js
- Authentication & Authorization
- JWT & RBAC
- API Validation
- Error Handling
- Business Logic
- Modular Architecture
- Service / Repository Pattern
- Dependency Injection

</td>

<td width="50%" valign="top">

### 🧩 System Design

- Microservices
- Event-driven Architecture
- Distributed Processing
- Load Balancing
- Horizontal Scaling
- Caching
- Message Queues
- Background Workers
- Fault Tolerance
- High Availability

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🗄️ Database Engineering

- PostgreSQL
- MongoDB
- Redis
- Prisma
- Database Relationships
- Indexing
- Transactions
- Query Optimization
- Connection Management
- Data Consistency

</td>

<td width="50%" valign="top">

### ☁️ Infrastructure

- Docker
- Kubernetes
- AWS
- Nginx
- Caddy
- GitHub Actions
- CI/CD
- Automated Testing
- Deployment Automation
- Linux

</td>
</tr>
</table>

---

# 🛠️ Technology Stack

<div align="center">

### Backend

<img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,express,python" />

### Database & Storage

<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma" />

### Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,redux" />

### DevOps & Cloud

<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,nginx,githubactions,linux" />

</div>

### Additional Technologies

`RabbitMQ` · `Bull Queue` · `Socket.IO` · `WebSockets` · `WebRTC` · `Firebase` · `JWT` · `OAuth` · `REST APIs` · `Git` · `GitHub` · `CI/CD`

---

# 🏗️ Architecture Mindset

```text
                         ┌──────────────────────┐
                         │       CLIENTS        │
                         │ Web · Mobile · API   │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │    LOAD BALANCER     │
                         └──────────┬───────────┘
                                    │
                    ┌───────────────┼───────────────┐
                    ▼               ▼               ▼
              ┌──────────┐   ┌──────────┐   ┌──────────┐
              │ API #1   │   │ API #2   │   │ API #3   │
              └─────┬────┘   └─────┬────┘   └─────┬────┘
                    │              │              │
                    └──────────────┼──────────────┘
                                   ▼
                         ┌──────────────────────┐
                         │   BUSINESS SERVICES  │
                         │   NestJS / Node.js   │
                         └──────────┬───────────┘
                                    │
              ┌─────────────────────┼─────────────────────┐
              ▼                     ▼                     ▼
       ┌─────────────┐       ┌─────────────┐       ┌─────────────┐
       │ PostgreSQL  │       │    Redis    │       │   MongoDB   │
       └─────────────┘       └─────────────┘       └─────────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │    MESSAGE QUEUE     │
                         │ RabbitMQ / Bull      │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │ BACKGROUND WORKERS   │
                         │ Async Processing     │
                         └──────────────────────┘
