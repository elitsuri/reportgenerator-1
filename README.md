# reportgenerator-1

> ReportGenerator 1: Automated report generation with PDF, Excel, and email delivery

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Go, Cron, PostgreSQL, Docker

## 🏗️ Architecture
Three-tier architecture: Go, Cron backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/reportgenerator-1
cd reportgenerator-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
