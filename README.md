# Enterprise PHP Backend

[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![CI Lint & Tests](https://github.com/OdeToTheWind/enterprise-php-backend/actions/workflows/tests.yml/badge.svg)](https://github.com/OdeToTheWind/enterprise-php-backend/actions)
[![PHPStan](https://img.shields.io/badge/PHPStan-Level%206-2C7A7B?style=for-the-badge)](https://phpstan.org/)
[![PSR-12](https://img.shields.io/badge/Code%20Style-PSR--12-4F5D95?style=for-the-badge)](https://www.php-fig.org/psr/psr-12/)

**100 Days of Professional PHP Backend Mastery**  
A structured, enterprise-grade learning journey from raw PHP to production-ready architectures.

> **Repository Location (Local):** `/opt/lampp/htdocs/enterprise-php-backend`  
> **Purpose:** Safe local development with XAMPP + full GitHub versioning for learning & portfolio showcase.

---

## Overview

**enterprise-php-backend** is a **monorepo-style** educational project that demonstrates 100 progressive PHP backend demos — carefully divided into **Beginner (25)**, **Intermediate (25)**, **Advanced (25)**, and **Real-World (25)** levels.

Each demo lives in its own isolated folder with complete code, tests, documentation, and learning notes — following modern enterprise PHP standards (PSR-12, Composer, PHPUnit, PHPStan, etc.).

This repository serves as both a **personal learning path** and a **professional portfolio** to showcase senior-level PHP backend engineering skills.

---

## Why This Repository?

- Master PHP the **enterprise way** — not just tutorials, but real architecture, testing, CI/CD, and scalability patterns.
- Learn progressively: from basic routing to Clean Architecture, CQRS, Event Sourcing, and microservices.
- Everything runs locally in **XAMPP** (`/opt/lampp/htdocs/`) for safe experimentation.
- Fully GitHub-integrated with workflows for linting, static analysis, and testing.
- Documented journey with Architectural Decision Records (ADRs) and daily progress logs.
- Prepares you for real-world backend roles in SaaS, fintech, e-commerce, and large-scale applications.

---

## Repository Structure

```bash
enterprise-php-backend/
├── .github/
│   ├── ISSUE_TEMPLATE/          # Professional feedback handling
│   └── workflows/               # CI: Lint, PHPStan, PHPUnit
├── .editorconfig
├── phpunit.xml
├── phpstan.neon
├── composer.json                # Centralized + per-demo dependencies
├── CHANGELOG.md
├── docs/
│   ├── progress/                # Detailed learning logs (demo_01_xxx.md)
│   └── architecture/            # ADRs & system diagrams
├── demos/
│   ├── beginner/                # 25 foundational demos
│   ├── intermediate/            # 25 tool-rich demos
│   ├── advanced/                # 25 architecture-focused demos
│   └── real-world/              # 25 production-grade applications
├── shared/
│   ├── contracts/               # Reusable interfaces
│   ├── utils/                   # Logger, helpers, benchmarking
│   └── infrastructure/          # Base Dockerfiles, configs
├── LICENSE
├── package.json                 # Helper scripts (optional)
├── .gitignore
└── README.md                    # ← You are here
```

## Daily Progress

| Day | Project / Demo                          | Level          | Status      | Key Learnings / Deliverables |
|-----|-----------------------------------------|----------------|-------------|---------------------------------------------------------------------------------------------|
| 01  | 01-basic-router                        | Beginner       | ⏳ Planned  | Simple custom router, .htaccess rewrite rules, clean URLs |
| 02  | 02-basic-crud-mysql                    | Beginner       | ⏳ Planned  | MySQLi CRUD operations, prepared statements, basic security |
| 03  | 03-form-validation                     | Beginner       | ⏳ Planned  | Server-side validation, input sanitization, error handling |
| 04  | 04-session-management                  | Beginner       | ⏳ Planned  | Session handling, basic login system, flash messages |
| 05  | 05-cookie-management                   | Beginner       | ⏳ Planned  | Cookie management, remember-me functionality, security implications |
| 06  | 06-file-upload                         | Beginner       | ⏳ Planned  | Single & multiple file upload, MIME validation, secure storage |
| 07  | 07-pdo-basics                          | Beginner       | ⏳ Planned  | PDO CRUD, prepared statements, exception handling |
| 08  | 08-basic-rest-api                      | Beginner       | ⏳ Planned  | JSON API with vanilla PHP, HTTP methods, proper responses |
| 09  | 09-pagination                          | Beginner       | ⏳ Planned  | Pagination logic, LIMIT/OFFSET, dynamic page links |
| 10  | 10-search-filter                       | Beginner       | ⏳ Planned  | Search & filter with LIKE queries, dynamic WHERE clauses |
| 11  | 11-user-registration                   | Beginner       | ⏳ Planned  | User registration, password hashing, email verification simulation |
| 12  | 12-password-reset                      | Beginner       | ⏳ Planned  | Forgot password flow, secure token generation & validation |
| 13  | 13-image-gallery                       | Beginner       | ⏳ Planned  | Image upload, listing, directory handling |
| 14  | 14-contact-form                        | Beginner       | ⏳ Planned  | Contact form, PHPMailer integration, spam protection basics |
| 15  | 15-basic-mvc                           | Beginner       | ⏳ Planned  | Tiny MVC structure without framework, separation of concerns |
| 16  | 16-error-handling                      | Beginner       | ⏳ Planned  | Custom error & exception handler, logging errors |
| 17  | 17-logging-system                      | Beginner       | ⏳ Planned  | Simple file-based logger, log levels |
| 18  | 18-date-time-handling                  | Beginner       | ⏳ Planned  | DateTime class, timezone handling, formatting |
| 19  | 19-csv-export-import                   | Beginner       | ⏳ Planned  | CSV export/import using fputcsv/fgetcsv |
| 20  | 20-basic-auth-middleware               | Beginner       | ⏳ Planned  | Simple route protection middleware concept |
| 21  | 21-json-config                         | Beginner       | ⏳ Planned  | JSON-based configuration management |
| 22  | 22-basic-cache                         | Beginner       | ⏳ Planned  | File-based caching system |
| 23  | 23-multi-language                      | Beginner       | ⏳ Planned  | Basic i18n using PHP arrays |
| 24  | 24-dashboard-layout                    | Beginner       | ⏳ Planned  | Admin panel layout with template includes |
| 25  | 25-unit-testing-basics                 | Beginner       | ⏳ Planned  | First PHPUnit tests, assertions, test structure |
| 26  | 01-composer-autoload                   | Intermediate   | ⏳ Planned  | PSR-4 autoloading, Composer setup, namespaces |
| 27  | 02-dependency-injection                | Intermediate   | ⏳ Planned  | Manual DI container, constructor injection |
| 28  | 03-twig-templating                     | Intermediate   | ⏳ Planned  | Twig template engine, inheritance, filters |
| 29  | 04-monolog-logging                     | Intermediate   | ⏳ Planned  | Professional logging with Monolog, handlers |
| 30  | 05-doctrine-dbal                       | Intermediate   | ⏳ Planned  | Database abstraction layer, QueryBuilder |
| 31  | 06-laravel-illuminate-collections      | Intermediate   | ⏳ Planned  | Fluent collections, higher-order functions |
| 32  | 07-jwt-auth                            | Intermediate   | ⏳ Planned  | JSON Web Token authentication |
| 33  | 08-rate-limiting                       | Intermediate   | ⏳ Planned  | API rate limiting (Redis + custom) |
| 34  | 09-queued-jobs                         | Intermediate   | ⏳ Planned  | Database queue system, worker script |
| 35  | 10-event-dispatcher                    | Intermediate   | ⏳ Planned  | Event system, observer pattern |
| 36  | 11-validator-component                 | Intermediate   | ⏳ Planned  | Symfony Validator with custom constraints |
| 37  | 12-middleware-pipeline                 | Intermediate   | ⏳ Planned  | PSR-15 middleware stack |
| 38  | 13-cors-handling                       | Intermediate   | ⏳ Planned  | Proper CORS middleware & security headers |
| 39  | 14-api-documentation                   | Intermediate   | ⏳ Planned  | OpenAPI/Swagger documentation |
| 40  | 15-database-migrations                 | Intermediate   | ⏳ Planned  | Custom migration system |
| 41  | 16-seeders                             | Intermediate   | ⏳ Planned  | Database seeding with Faker |
| 42  | 17-repository-pattern                  | Intermediate   | ⏳ Planned  | Repository + Entity pattern |
| 43  | 18-service-layer                       | Intermediate   | ⏳ Planned  | Service classes for business logic |
| 44  | 19-caching-redis                       | Intermediate   | ⏳ Planned  | Redis caching layer with tags |
| 45  | 20-unit-testing-advanced               | Intermediate   | ⏳ Planned  | PHPUnit with mocks & data providers |
| 46  | 21-integration-testing                 | Intermediate   | ⏳ Planned  | Testing with real database (SQLite) |
| 47  | 22-psr-7-http-message                  | Intermediate   | ⏳ Planned  | PSR-7 Request/Response with Guzzle |
| 48  | 23-env-configuration                   | Intermediate   | ⏳ Planned  | Environment variables with phpdotenv |
| 49  | 24-static-analysis                     | Intermediate   | ⏳ Planned  | PHPStan Level 5+ configuration |
| 50  | 25-coding-standards                    | Intermediate   | ⏳ Planned  | PHP_CodeSniffer (PSR-12) enforcement |
| 51  | 01-hexagonal-architecture              | Advanced       | ⏳ Planned  | Ports & Adapters, dependency inversion |
| 52  | 02-ddd-tactical                        | Advanced       | ⏳ Planned  | Entities, Value Objects, Aggregates |
| 53  | 03-cqrs-basic                          | Advanced       | ⏳ Planned  | Command Query Responsibility Segregation |
| 54  | 04-event-sourcing-intro                | Advanced       | ⏳ Planned  | Basic event store implementation |
| 55  | 05-microservices-communication         | Advanced       | ⏳ Planned  | Sync & async communication (RabbitMQ) |
| 56  | 06-api-gateway-pattern                 | Advanced       | ⏳ Planned  | Lightweight API gateway |
| 57  | 07-clean-architecture                  | Advanced       | ⏳ Planned  | Full Clean Architecture layers |
| 58  | 08-domain-events                       | Advanced       | ⏳ Planned  | Domain event dispatching |
| 59  | 09-specification-pattern               | Advanced       | ⏳ Planned  | Business rules as specifications |
| 60  | 10-saga-pattern                        | Advanced       | ⏳ Planned  | Orchestration-based saga pattern |
| 61  | 11-graphql-server                      | Advanced       | ⏳ Planned  | GraphQL with webonyx/graphql-php |
| 62  | 12-async-php                           | Advanced       | ⏳ Planned  | Non-blocking I/O with ReactPHP/Amp |
| 63  | 13-message-bus                         | Advanced       | ⏳ Planned  | Command/Query bus implementation |
| 64  | 14-feature-flags                       | Advanced       | ⏳ Planned  | Advanced feature toggle system |
| 65  | 15-observability                       | Advanced       | ⏳ Planned  | OpenTelemetry tracing & metrics |
| 66  | 16-database-sharding                   | Advanced       | ⏳ Planned  | Horizontal sharding simulation |
| 67  | 17-read-replicas                       | Advanced       | ⏳ Planned  | Master-Slave database routing |
| 68  | 18-performance-profiling               | Advanced       | ⏳ Planned  | Blackfire / Xdebug profiling |
| 69  | 19-security-hardening                  | Advanced       | ⏳ Planned  | OWASP Top 10 mitigations |
| 70  | 20-multi-tenancy                       | Advanced       | ⏳ Planned  | Multi-tenant architecture strategies |
| 71  | 21-event-driven-architecture           | Advanced       | ⏳ Planned  | Full Event-Driven Architecture |
| 72  | 22-api-versioning                      | Advanced       | ⏳ Planned  | Header & URL versioning strategies |
| 73  | 23-circuit-breaker                     | Advanced       | ⏳ Planned  | Resilience pattern implementation |
| 74  | 24-distributed-locking                 | Advanced       | ⏳ Planned  | Redis Redlock for concurrency |
| 75  | 25-monorepo-structure                  | Advanced       | ⏳ Planned  | Managing packages in monorepo |
| 76  | 01-ecommerce-backend                   | Real-World     | ⏳ Planned  | Full e-commerce API with cart, orders, inventory |
| 77  | 02-saas-multi-tenant                   | Real-World     | ⏳ Planned  | Subscription SaaS platform with tenant isolation |
| 78  | 03-hospital-management                 | Real-World     | ⏳ Planned  | Healthcare appointment & patient management |
| 79  | 04-learning-management-system          | Real-World     | ⏳ Planned  | LMS with courses, progress tracking, quizzes |
| 80  | 05-banking-core                        | Real-World     | ⏳ Planned  | Core banking simulation with transactions |
| 81  | 06-logistics-platform                  | Real-World     | ⏳ Planned  | Delivery & real-time tracking system |
| 82  | 07-social-media-backend                | Real-World     | ⏳ Planned  | Feeds, likes, follows, media handling |
| 83  | 08-hr-management                       | Real-World     | ⏳ Planned  | Employee, leave, attendance & payroll system |
| 84  | 09-real-estate-crm                     | Real-World     | ⏳ Planned  | Property listing & CRM system |
| 85  | 10-fintech-wallet                      | Real-World     | ⏳ Planned  | Digital wallet with transfers & KYC |
| 86  | 11-restaurant-pos                      | Real-World     | ⏳ Planned  | POS + kitchen display system |
| 87  | 12-ticketing-system                    | Real-World     | ⏳ Planned  | Event ticket booking with seat reservation |
| 88  | 13-project-management                  | Real-World     | ⏳ Planned  | Task, sprint & board management (Jira-like) |
| 89  | 14-inventory-erp                       | Real-World     | ⏳ Planned  | Warehouse & supply chain management |
| 90  | 15-telemedicine-backend                | Real-World     | ⏳ Planned  | Doctor-patient consultation platform |
| 91  | 16-crowdfunding-platform               | Real-World     | ⏳ Planned  | Campaign, pledge & reward system |
| 92  | 17-news-portal-cms                     | Real-World     | ⏳ Planned  | Content publishing with editorial workflow |
| 93  | 18-ai-powered-job-board                | Real-World     | ⏳ Planned  | Job portal with matching engine |
| 94  | 19-blockchain-explorer                 | Real-World     | ⏳ Planned  | Blockchain data API (simulation) |
| 95  | 20-iot-device-management               | Real-World     | ⏳ Planned  | IoT device registry & telemetry |
| 96  | 21-compliance-audit-system             | Real-World     | ⏳ Planned  | Regulatory compliance & audit trails |
| 97  | 22-multi-vendor-marketplace            | Real-World     | ⏳ Planned  | Multi-vendor e-commerce platform |
| 98  | 23-fleet-management                    | Real-World     | ⏳ Planned  | Vehicle tracking & maintenance system |
| 99  | 24-enterprise-rbac                     | Real-World     | ⏳ Planned  | Advanced Role-Based Access Control |
| 100 | 25-full-microservices                  | Real-World     | ⏳ Planned  | Distributed system (Order + Payment + Notification) |
---

## Table of Progress

| Level          | Demos | Focus                                              | Status      |
|----------------|-------|----------------------------------------------------|-------------|
| **Beginner**   | 1–25  | Core PHP, routing, CRUD, basic MVC                 | ⏳ Planned  |
| **Intermediate**| 26–50 | Composer, DI, testing, modern tools & patterns     | ⏳ Planned  |
| **Advanced**   | 51–75 | Clean/Hexagonal Architecture, DDD, CQRS, scalability | ⏳ Planned  |
| **Real-World** | 76–100| Complete production-grade applications             | ⏳ Planned  |
| **Total**      | **100**| Enterprise PHP Backend Mastery                     | **0/100**   |

---

## Backend Tech Stack & Deployment Strategy

**Core Stack**
- PHP 8.2+
- Composer (dependency & autoloading management)
- PDO & Doctrine DBAL (database abstraction)
- MySQL (primary database)
- Twig (templating engine)
- Monolog (structured logging)
- PHPUnit + PHPStan + PHP_CodeSniffer (PSR-12)
- Redis (caching & rate limiting)
- RabbitMQ (advanced queuing & events – used from intermediate/advanced demos)
- JWT (authentication – firebase/php-jwt)
- Guzzle + PSR-7 (HTTP client & messages)
- Symfony Components (Validator, HttpFoundation, EventDispatcher, etc. – used selectively, not full Symfony framework)

**Architecture Patterns (Progressive Learning)**
- Beginner → Basic MVC & procedural
- Intermediate → Service Layer + Repository Pattern + Middleware
- Advanced → Hexagonal / Ports & Adapters → Clean Architecture
- Real-World → CQRS + Event Sourcing + Domain-Driven Design (DDD) + Event-Driven Architecture

**Advanced / Future Tools**
- Webonyx GraphQL (for GraphQL demos)
- ReactPHP / Amp (async PHP)
- OpenTelemetry (observability & tracing)
- Docker & Docker Compose (for advanced & real-world demos)

**Deployment Strategy**
- **Local Development**: XAMPP (placed safely in `/opt/lampp/htdocs/enterprise-php-backend`) – ideal for quick iteration and learning without container overhead.
- **Version Control & CI/CD**: Git + GitHub with automated workflows (linting with PHP_CodeSniffer, static analysis with PHPStan, tests with PHPUnit).
- **Environment Management**: `.env` files via `vlucas/phpdotenv`.
- **Development (from Intermediate+)**: Docker Compose with PHP-FPM + Nginx + MySQL + Redis + RabbitMQ (for realistic service simulation).
- **Production (Real-World demos)**: PHP 8.2+ on Nginx/Apache, Redis, RabbitMQ with supervised workers (e.g., Supervisor), scalable to Kubernetes in future demos.
- **Monitoring**: OpenTelemetry integration (planned in advanced & real-world demos). Future: Prometheus + Grafana.

This stack ensures **progressive learning** — you start with pure PHP + XAMPP and gradually introduce enterprise-grade tools and deployment practices while keeping each demo runnable independently.

---

## Key Features

- **100 Progressive Demos** – From basic routing to full microservices
- **Enterprise-Grade Structure** – Monorepo with shared contracts & utilities
- **Modern PHP Standards** – PSR-12, Composer, PHPUnit, PHPStan Level 6+
- **Isolated & Runnable** – Every demo works independently with its own README
- **Daily Documented Progress** – Detailed learning logs in `docs/progress/`
- **Architectural Decision Records (ADRs)** – Professional documentation
- **CI/CD Ready** – Automated linting, static analysis and testing
- **Focus on Real-World Skills** – Security, performance, scalability and maintainability
- **Portfolio Showcase** – Clean Git history and professional folder structure
- **Safe Local Setup** – Designed for XAMPP in `/opt/lampp/htdocs/`

---
## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/OdeToTheWind/enterprise-php-backend.git
   cd enterprise-php-backend
   ```

2. **Place the project inside XAMPP htdocs (recommended path):**
   ```bash
   /opt/lampp/htdocs/enterprise-php-backend
   ```

3. **Install dependencies:**
   ```bash
   composer install
   ```

4. **Start XAMPP (Apache + MySQL) and visit:**
   ```bash
   http://localhost/enterprise-php-backend/
   ```

5. **Run quality checks:**
   ```bash
   composer analyse   # PHPStan
   composer test      # PHPUnit
   ```

### Each demo folder contains its own detailed `README.md` with setup and learning notes.
---

## Contributing

This is a personal challenge repository, but issues, suggestions, and thoughtful discussions are welcome.

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.