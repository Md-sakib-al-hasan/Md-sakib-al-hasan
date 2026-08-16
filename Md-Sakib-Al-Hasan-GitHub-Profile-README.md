::: {align="center"}
# ⚡ Md Sakib Al Hasan

### Backend Engineer · System Design · Distributed Systems

**TypeScript · Node.js · NestJS · Python · Laravel · PostgreSQL · Redis
· Docker · Kubernetes · AWS**

Building scalable APIs, distributed processing systems, real-time
services, and production-ready infrastructure.

`<br/>`{=html}

`<a href="https://github.com/Md-sakib-al-hasan">`{=html}
`<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>`{=html}
`</a>`{=html}
`<a href="https://www.linkedin.com/in/md-sakib-al-hasan-46942126b">`{=html}
`<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>`{=html}
`</a>`{=html}
`<a href="mailto:md.sakib.al.hasan.programmer@gmail.com">`{=html}
`<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>`{=html}
`</a>`{=html}
:::

------------------------------------------------------------------------

## 🧑‍💻 About Me

I'm a **Backend & System Design Engineer** focused on building reliable,
scalable, and maintainable software systems.

My primary backend ecosystem is **TypeScript / Node.js / NestJS**, while
I also work with **Python and Laravel** for backend development.

I enjoy working beyond individual APIs --- thinking about **system
boundaries, database design, asynchronous processing, caching, queues,
real-time communication, infrastructure, CI/CD, and production
reliability**.

``` text
Build  →  Understand  →  Design  →  Scale  →  Automate
```

> **Good systems are not just built to work. They are built to keep
> working.**

------------------------------------------------------------------------

# 🏭 Production Engineering

My experience covers the complete backend lifecycle --- from API design
to production deployment.

### 🔌 Backend Engineering

-   REST API architecture
-   Node.js / NestJS / Express.js
-   Python backend development
-   Laravel backend development
-   Authentication & Authorization
-   RBAC
-   API validation
-   Real-time communication
-   WebSockets / Socket.IO

### 🧩 Distributed Systems

-   RabbitMQ
-   Bull Queue
-   Producer / Consumer architecture
-   Background workers
-   Scheduled jobs
-   Asynchronous processing
-   Event-driven architecture
-   Workload isolation

### 🗄️ Data Engineering

-   PostgreSQL
-   MongoDB
-   Redis
-   Prisma
-   Mongoose
-   Transactions
-   Indexing
-   Query optimization
-   Caching

### ☁️ Infrastructure

-   Docker
-   Kubernetes
-   AWS
-   Nginx
-   Caddy
-   Load Balancing
-   CI/CD
-   Automated Testing

------------------------------------------------------------------------

# 🧠 System Design

I'm interested in designing systems around:

  -----------------------------------------------------------------------
  Domain                              What I Work With
  ----------------------------------- -----------------------------------
  🏗️ Architecture                     Modular Architecture ·
                                      Microservices · Service Boundaries

  🌐 Scalability                      Horizontal Scaling · Load Balancing
                                      · Stateless Services

  🔄 Distributed Systems              Queues · Workers · Async Processing
                                      · Event-Driven Systems

  🗄️ Data                             PostgreSQL · MongoDB · Transactions
                                      · Indexing · Consistency

  ⚡ Performance                      Redis · Caching · Query
                                      Optimization · Background
                                      Processing

  🛡️ Reliability                      Retry · Idempotency · Failover ·
                                      Fault Isolation

  🔐 Security                         JWT · RBAC · Authorization ·
                                      Validation · Rate Limiting

  🚀 Delivery                         Docker · Kubernetes · AWS · GitHub
                                      Actions · CI/CD
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🏗️ How I Think About Backend Systems

``` text
                         ┌─────────────────┐
                         │     CLIENT      │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │  LOAD BALANCER  │
                         └────────┬────────┘
                                  │
                ┌─────────────────┼─────────────────┐
                ▼                 ▼                 ▼
          ┌──────────┐      ┌──────────┐      ┌──────────┐
          │ API #01  │      │ API #02  │      │ API #03  │
          └────┬─────┘      └────┬─────┘      └────┬─────┘
               │                 │                 │
               └─────────────────┼─────────────────┘
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
              ┌───────────┐            ┌────────────┐
              │   REDIS   │            │  RABBITMQ  │
              │   CACHE   │            │    QUEUE   │
              └───────────┘            └─────┬──────┘
                                             │
                                      ┌──────▼──────┐
                                      │   WORKERS   │
                                      └──────┬──────┘
                                             │
                              ┌──────────────┴──────────────┐
                              ▼                             ▼
                       ┌────────────┐                ┌────────────┐
                       │ PostgreSQL │                │  MongoDB   │
                       └────────────┘                └────────────┘
```

------------------------------------------------------------------------

# 🚀 Featured Engineering

## 🟣 Theta Analyze

### Multi-Tenant B2B SaaS Platform

A multi-tenant platform covering projects, investments, employees,
clients, investor analytics, billing, support, and domain management.

**Architecture Highlights**

-   Multi-tenant architecture
-   RBAC across multiple user roles
-   Submission → approval → controlled publishing workflow
-   APIs supporting **40+ analytical charts**
-   Dynamic Gantt-chart data
-   Workload separation between synchronous APIs and heavy processing
-   Docker + Kubernetes deployment
-   AWS infrastructure
-   Load balancing for horizontal scalability
-   CI/CD with automated testing

**Stack**

`Node.js` `NestJS` `PostgreSQL` `Prisma` `Docker` `Kubernetes` `AWS`

------------------------------------------------------------------------

## 🔵 Digital Screen Advertising Platform

A scheduling-driven platform for remotely managing digital advertising
screens.

**Architecture Highlights**

-   API → scheduling → background processing → screen delivery
-   Full-day, half-day, and time-slot scheduling
-   Dynamic content updates
-   Rescheduling workflows
-   Background workers
-   Asynchronous processing
-   Subscription management
-   Revenue reporting
-   Content management

**Stack**

`Node.js` `NestJS` `PostgreSQL` `Redis` `Docker` `AWS`

------------------------------------------------------------------------

## 🟢 Wellness & Lifestyle Monitoring System

A system designed around continuous data processing and automated
condition-based actions.

### Processing Pipeline

``` text
User Data
    │
    ▼
   API
    │
    ▼
Scheduled Jobs
    │
    ▼
Condition Evaluation
    │
    ▼
Notification / Action
```

**Architecture Highlights**

-   Cron-based recurring workloads
-   Asynchronous processing
-   Long-running workload isolation
-   Modular / microservice-style execution
-   Dockerized workloads
-   Kubernetes deployment

**Stack**

`Node.js` `NestJS` `Firebase` `Docker` `Kubernetes`

------------------------------------------------------------------------

## 🟠 Enterprise Workforce Management Platform

A modular backend system focused on workforce management workflows.

**Architecture Highlights**

-   Authentication & authorization
-   Role-based access control
-   API validation
-   Relational database design
-   Reusable services
-   Modular backend architecture
-   Production API structure

**Stack**

`Node.js` `NestJS` `PostgreSQL` `Prisma` `Docker`

------------------------------------------------------------------------

# ⚙️ Tech Stack

### 🔴 Backend

```{=html}
<p align="left">
```
`<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white"/>`{=html}
```{=html}
</p>
```
### 🗄️ Database & Messaging

```{=html}
<p align="left">
```
`<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>`{=html}
```{=html}
</p>
```
### ☁️ Cloud & DevOps

```{=html}
<p align="left">
```
`<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Caddy-0E8A16?style=for-the-badge&logo=caddy&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>`{=html}
```{=html}
</p>
```
### 🎨 Frontend Experience

```{=html}
<p align="left">
```
`<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>`{=html}
`<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"/>`{=html}
`<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

# 🔄 CI/CD & Production Workflow

``` text
                     ┌──────────────────┐
                     │    Pull Request  │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │      Lint        │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │    Type Check    │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │      Tests       │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │      Build       │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │   Docker Image   │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │      Deploy      │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │     Monitor      │
                     └──────────────────┘
```

------------------------------------------------------------------------

# 🧩 Engineering Principles

``` text
01  Understand the problem before designing the system.

02  Keep services simple and boundaries clear.

03  Prefer asynchronous processing for long-running workloads.

04  Design APIs around predictable contracts.

05  Treat database design as part of system design.

06  Use caching where it solves a real bottleneck.

07  Design for failure, not just the happy path.

08  Automate testing and deployment.

09  Measure before optimizing.

10  Build systems that other engineers can understand.
```

------------------------------------------------------------------------

# 📈 GitHub

::: {align="center"}
`<img height="180" src="https://github-readme-stats.vercel.app/api?username=Md-sakib-al-hasan&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true"/>`{=html}

`<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Md-sakib-al-hasan&layout=compact&theme=github_dark&hide_border=true"/>`{=html}
:::

------------------------------------------------------------------------

# 🔥 Contribution Streak

::: {align="center"}
`<img src="https://streak-stats.demolab.com?user=Md-sakib-al-hasan&theme=github-dark-blue&hide_border=true"/>`{=html}
:::

------------------------------------------------------------------------

# 🏆 GitHub Trophies

::: {align="center"}
`<img src="https://github-profile-trophy.vercel.app/?username=Md-sakib-al-hasan&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7"/>`{=html}
:::

------------------------------------------------------------------------

# 📊 Contribution Graph

::: {align="center"}
`<img src="https://github-readme-activity-graph.vercel.app/graph?username=Md-sakib-al-hasan&theme=github-compact&hide_border=true"/>`{=html}
:::

------------------------------------------------------------------------

# 🎯 Currently Exploring

``` text
Distributed Systems
        ↓
System Design
        ↓
Microservices
        ↓
Event-Driven Architecture
        ↓
Database Scalability
        ↓
Cloud Infrastructure
        ↓
Production Reliability
```

------------------------------------------------------------------------

# 🌐 Let's Connect

::: {align="center"}
`<a href="https://github.com/Md-sakib-al-hasan">`{=html}
`<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>`{=html}
`</a>`{=html}

`<a href="https://www.linkedin.com/in/md-sakib-al-hasan-46942126b">`{=html}
`<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>`{=html}
`</a>`{=html}

`<a href="mailto:md.sakib.al.hasan.programmer@gmail.com">`{=html}
`<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>`{=html}
`</a>`{=html}
:::

`<br/>`{=html}

::: {align="center"}
### ⚡ Backend · Systems · Infrastructure

**Designing reliable systems today, learning how to scale them
tomorrow.**

`<br/>`{=html}

`<img src="https://komarev.com/ghpvc/?username=Md-sakib-al-hasan&style=for-the-badge&color=0e75b6"/>`{=html}
:::
