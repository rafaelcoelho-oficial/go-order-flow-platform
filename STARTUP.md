You are a senior staff backend engineer, distributed systems architect, and elite open source maintainer.

Your task is to fully bootstrap a production-grade Golang backend portfolio project called:

GO ORDER FLOW PLATFORM

This project must simulate a real enterprise distributed order processing ecosystem used by e-commerce / ERP / logistics companies.

====================================================
PRIMARY OBJECTIVE
====================================================

Generate the complete initial professional repository foundation, including:

1. A highly professional README.md
2. Full folder/file architecture skeleton
3. Initial Golang project bootstrap files
4. Docker Compose infrastructure
5. Architectural documentation files
6. Empty but realistic service contracts/interfaces
7. Makefile
8. Environment configuration templates
9. GitHub-worthy project presentation

This repository must look like a serious backend engineering case study, not a tutorial CRUD.

====================================================
TECH STACK TO ASSUME
====================================================

- Golang 1.24+
- Gin or Fiber
- PostgreSQL
- Redis
- MongoDB
- RabbitMQ
- Prometheus
- Grafana
- Jaeger/OpenTelemetry
- Docker / Docker Compose
- Clean Architecture
- Domain Driven Design
- SOLID
- TDD-first mindset

====================================================
BUSINESS CONTEXT
====================================================

The platform processes customer orders across multiple business domains:

- order creation
- payment confirmation
- inventory reservation
- status transitions
- notification dispatch
- analytics event generation
- audit event persistence

The system must contain realistic microservice boundaries such as:

- api-gateway
- order-service
- payment-service
- inventory-service
- notification-worker
- analytics-worker

====================================================
WHAT README.MD MUST CONTAIN
====================================================

Generate a COMPLETE enterprise-grade README.md with:

- project title
- strong subtitle
- realistic project overview
- business problem statement
- architecture goals
- tech stack section
- microservices overview
- event-driven flow explanation
- DDD and clean architecture explanation
- observability stack
- testing strategy
- project folder structure
- docker startup instructions
- roadmap milestones
- future enhancements
- why this project is valuable for backend engineering portfolio

README must be written in polished professional GitHub English.

====================================================
REPOSITORY STRUCTURE
====================================================

Generate a FULL realistic monorepo tree including:

/cmd
/internal
/pkg
/services
/deployments
/docs
/tests
/scripts

and detailed subfolders for each service using:

domain/
application/
infrastructure/
interfaces/

====================================================
ALSO GENERATE
====================================================

- docker-compose.yml
- Makefile
- .env.example
- docs/architecture.md
- docs/event-flow.md
- docs/testing-strategy.md
- docs/adr/0001-initial-architecture.md

Generate all files with realistic starter content, not placeholders like "TODO".

====================================================
IMPORTANT OUTPUT FORMAT
====================================================

Output in this exact order:

1. COMPLETE README.md
2. COMPLETE repository tree
3. COMPLETE content of every starter file

Do not summarize.
Do not explain your choices.
Directly generate the repository foundation.
