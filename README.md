# 👋 Md Sakib Al Hasan

<div align="center">

# Backend Engineer · System Design · Full-Stack Development

### Building scalable APIs, distributed systems, real-time applications & production infrastructure

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

<p>
  <a href="mailto:md.sakib.al.hasan.programmer@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Md-sakib-al-hasan">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/md-sakib-al-hasan-46942126b">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

</div>

---

## 🧠 What I Do

I'm a **backend-focused software engineer** who builds reliable and scalable software systems.

My strongest area is the **TypeScript + Node.js ecosystem**, particularly:

**NestJS · Express.js · PostgreSQL · Prisma · MongoDB · Redis · REST APIs · WebSockets**

I also work with:

**RabbitMQ · Bull Queue · Docker · Kubernetes · AWS · CI/CD · Python · Next.js · React · Firebase**

I don't only focus on making an API work.

I care about:

- How the system behaves under load
- How services communicate
- How databases are designed and optimized
- How background jobs are processed
- How failures are handled
- How data remains consistent
- How applications scale horizontally
- How deployments become repeatable
- How production systems remain reliable

> **I build systems with the next stage of scale in mind.**

---

# ⚡ Engineering at a Glance

<div align="center">

| 🏗️ Backend | 🧩 System Design | 🗄️ Data | ☁️ Infrastructure |
|:---:|:---:|:---:|:---:|
| REST APIs | Distributed Systems | PostgreSQL | Docker |
| NestJS | Microservices | MongoDB | Kubernetes |
| Express.js | Event-driven Architecture | Redis | AWS |
| Authentication | Load Balancing | Prisma | CI/CD |
| WebSockets | Horizontal Scaling | Indexing | Linux |
| RBAC | Fault Tolerance | Transactions | Deployment |

</div>

---

# 🏆 Featured Engineering Work

## 🟣 Theta Analyze

### B2B SaaS · Investment Analytics · Project Management

> **A multi-tenant business platform combining project management, investment analytics, workforce management, reporting, billing and automated business workflows.**

This is one of the systems where I worked with **large business workflows, multiple user roles, analytics, project lifecycle management, automation and production infrastructure.**

### 🔑 Core Engineering

**Multi-Tenant Architecture**
- Multiple businesses can operate inside the platform
- Tenant-aware data and workflows
- Centralized administration

**Role-Based Workflows**
- Client
- Manager
- Employee
- Investor
- Viewer
- Admin
- Super Admin

**Project Management**
- Multiple projects
- Multiple project sections
- Project progress tracking
- Employee assignment
- Investment tracking
- Project lifecycle management

**Analytics**
- **40+ analytical charts**
- Investment analytics
- Business performance data
- Project analytics
- Dynamic reporting
- Gantt chart visualization

**Workflow Automation**
- Data upload workflows
- Manager approval process
- Automated notifications
- Background processing
- Dynamic data updates

**Business Infrastructure**
- Billing
- Payment workflows
- Subscription-related operations
- Support system
- Automatic domain connection
- Admin & Super Admin management

**Production Infrastructure**
- Docker
- Kubernetes
- AWS
- Load balancing
- CI/CD
- Automated testing

### 🧱 Architecture Thinking

```text
Users
  │
  ▼
Authentication / RBAC
  │
  ▼
API Layer
  │
  ▼
Business Services
  │
  ├───────────────┐
  ▼               ▼
Database       Message Queue
  │               │
  ▼               ▼
PostgreSQL     Background Workers
  │               │
  └───────┬───────┘
          ▼
     Analytics
          │
          ▼
      Dashboards
