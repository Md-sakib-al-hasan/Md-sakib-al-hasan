# Md Sakib Al Hasan

### Backend & System Design Engineer

**TypeScript · Node.js · NestJS · PostgreSQL · Redis · Docker · Kubernetes · AWS**

I’m a backend and system-design focused engineer building scalable APIs, distributed processing systems, real-time services, and production infrastructure.

My work focuses on turning product requirements into reliable backend architecture — from API boundaries and database design to asynchronous processing, caching, deployment, and CI/CD.

> **Design for reliability. Build for scale. Keep the system understandable.**

---

## 🚀 What I Do

- 🏗️ Design scalable backend architectures
- ⚡ Build high-performance REST APIs
- 🔄 Develop asynchronous and event-driven systems
- 🗄️ Design relational and NoSQL data systems
- 🔐 Implement authentication, authorization, and RBAC
- 📡 Build real-time systems with WebSockets
- 🐳 Containerize applications with Docker
- ☸️ Deploy and scale services with Kubernetes
- ☁️ Work with AWS infrastructure
- 🔁 Build CI/CD pipelines and automated deployments

---

# 🏭 Production Engineering

My backend work spans API development, database systems, asynchronous workloads, real-time communication, and production infrastructure.

### Backend

- TypeScript
- Node.js
- NestJS
- Express.js
- REST APIs
- Socket.IO
- WebSockets

### Data & Messaging

- PostgreSQL
- MongoDB
- Redis
- Prisma
- RabbitMQ
- Bull Queue
- Background Workers
- Scheduled Jobs

### Infrastructure

- Docker
- Kubernetes
- AWS
- Nginx
- Caddy
- GitHub Actions
- CI/CD

### Security

- JWT Authentication
- Role-Based Access Control
- Authorization
- Input Validation
- Rate Limiting
- Secure API Design

---

# 🧠 System Design

I’m particularly interested in designing systems around:

| Area | Focus |
|---|---|
| 🏗️ Architecture | Modular systems, microservices, service boundaries |
| 🌐 Scalability | Horizontal scaling, load balancing, workload isolation |
| 🔄 Distributed Systems | Queues, workers, asynchronous processing |
| 🗄️ Data Systems | PostgreSQL, MongoDB, transactions, indexing |
| ⚡ Performance | Redis caching, query optimization, background processing |
| 🛡️ Reliability | Retry, idempotency, failover, fault isolation |
| 🔐 Security | Authentication, authorization, RBAC, rate limiting |
| 🚀 Infrastructure | Docker, Kubernetes, AWS, CI/CD |

---

# 🏗️ Architecture

```text
                    ┌─────────────────────┐
                    │       Client        │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Load Balancer    │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────┐     ┌──────────┐
        │ API #1   │     │ API #2   │     │ API #3   │
        └────┬─────┘     └────┬─────┘     └────┬─────┘
             │                │                │
             └────────────────┼────────────────┘
                              │
                ┌─────────────┴─────────────┐
                │                           │
                ▼                           ▼
         ┌─────────────┐             ┌─────────────┐
         │    Redis    │             │ Message     │
         │    Cache    │             │ Queue       │
         └─────────────┘             │ RabbitMQ    │
                                     └──────┬──────┘
                                            │
                                     ┌──────▼──────┐
                                     │   Workers   │
                                     └──────┬──────┘
                                            │
                              ┌─────────────┴─────────────┐
                              ▼                           ▼
                       ┌────────────┐              ┌────────────┐
                       │ PostgreSQL │              │  MongoDB   │
                       └────────────┘              └────────────┘
