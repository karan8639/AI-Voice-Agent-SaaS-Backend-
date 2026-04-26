# AI-Voice-Agent-SaaS (Backend)

A multi-tenant SaaS platform providing AI-driven voice receptionists for automated client communication and lead management.

## 🚀 Tech Stack
- **Framework:** Spring Boot 3.x (Java 21)
- **Database:** PostgreSQL (with pgvector for AI context)
- **Security:** Spring Security & JWT (Multi-tenant isolation)
- **Containerization:** Docker & Docker Compose
- **Cloud:** AWS (RDS, EC2, S3)
- **AI/Voice:** OpenAI API / Vapi / Twilio

## 🛠️ Features (Phase 1)
- [ ] Multi-tenant Database Schema
- [ ] JWT-based Authentication with Role-Based Access Control (RBAC)
- [ ] Tenant-aware persistence logic

## 🏗️ Getting Started
1. Clone the repository.
2. Run `docker-compose up -d` to start the PostgreSQL instance.
3. Configure `application.yml` with your database credentials.
