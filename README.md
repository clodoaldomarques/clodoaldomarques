# Hi, I'm Clodoaldo Marques 👋

### Senior Backend Software Engineer | Go | Distributed Systems | Cloud-Native

I'm a Senior Software Engineer with 15+ years of experience and strong performance over the last 4 years in mission-critical microservices for the banking and financial sector. Solid experience in Golang, Java, and Kotlin, with expertise in Domain-Driven Design (DDD), Clean Architecture, Design Patterns (GoF), and Cloud Native practices. Worked on the core banking platform at Pismo/Visa, dealing with high scalability and regulatory requirements. Solid experience in observability (OpenTelemetry, Prometheus, Grafana, Honeycomb) and container orchestration (Docker/Kubernetes) in production environments. Seeking to evolve into Staff Engineer and Architecture roles, with a focus on technical leadership and business impact.

---

## 🚀 What I Work With

### Backend

- Go (Golang)
- Java
- REST APIs
- Microservices
- Distributed Systems
- Event-Driven Architecture
- Asynchronous Processing
- Software Architecture
- Design Patterns

### Cloud & Infrastructure

- AWS
- Kubernetes
- Docker
- Terraform
- Minikube
- LocalStack

### Messaging

- Amazon SQS
- Amazon SNS
- Event-driven systems
- Message-based architectures

### Data

- MySQL
- Database migrations
- Flyway

### Observability

- OpenTelemetry
- Prometheus
- Grafana
- Zipkin

### AI & Developer Tools

- Generative AI
- Local LLMs
- Ollama
- AI-assisted software development

---

## 🧩 Engineering Focus

I'm particularly interested in:

- Distributed systems
- Microservices architecture
- Event-driven systems
- Backend scalability
- Asynchronous processing
- Resilient services
- Cloud-native architectures
- Developer experience
- Observability
- AI-assisted software engineering

---

# ⭐ Featured Projects

Some of the projects in my GitHub portfolio explore different aspects of modern backend engineering.

## [Balances API](https://github.com/clodoaldomarques/balances-api)

**Go · AWS · SQS · SNS · Kubernetes · Terraform · MySQL · Flyway · LocalStack**

A Go-based backend service for balance management, integrating synchronous APIs with asynchronous messaging and cloud-native infrastructure.

The project explores:

- Go backend development
- Event-driven architecture
- AWS messaging
- Kubernetes
- Infrastructure as Code
- Database migrations
- Local AWS development with LocalStack

---

## [Ledger Worker](https://github.com/clodoaldomarques/ledger-worker)

**Go · AWS · SQS · Event Processing · Resilience**

A Go-based worker focused on asynchronous ledger event processing.

The project explores:

- Background processing
- Message consumption
- Event-driven architecture
- Distributed processing
- Resilience patterns
- Service integration

---

## [Core SDK](https://github.com/clodoaldomarques/core-sdk)

**Go · AWS SDK · Messaging · OpenTelemetry**

A reusable Go SDK providing shared infrastructure components for backend services.

The project focuses on reducing duplicated infrastructure code across services and providing reusable components for areas such as messaging, AWS integration and observability.

---

## [Infra Local](https://github.com/clodoaldomarques/infra-local)

**Kubernetes · Minikube · Docker · LocalStack · Observability**

A reusable local cloud-native infrastructure environment for developing and testing distributed systems.

It brings together infrastructure such as:

- Kubernetes / Minikube
- LocalStack
- MySQL
- Redis
- OpenTelemetry
- Prometheus
- Grafana
- Zipkin
- MockServer
- Ollama

The goal is to provide a reproducible local environment for cloud-native backend development.

---

## [Code Review Agent](https://github.com/clodoaldomarques/codereview-agent)

**Go · Ollama · Qwen2.5-Coder · Generative AI**

An experimental Go API exploring AI-assisted code review using a locally hosted Large Language Model.

The project explores the intersection between:

- Backend engineering
- Generative AI
- Local LLM inference
- Prompt engineering
- Developer tooling

---

# 🔭 Other Projects

### [Balances Worker](https://github.com/clodoaldomarques/balances-worker)

Go-based background worker responsible for processing balance-related events and generating daily balance reports.

### [Ledger Events](https://github.com/clodoaldomarques/ledger-events)

Go backend service focused on accounting events within the Ledger ecosystem.

### [Ledger Config](https://github.com/clodoaldomarques/ledger-config)

Go-based service focused on configuration capabilities within the Ledger ecosystem.

---

# 🏗️ Architecture & Engineering

A recurring theme across my projects is the separation of responsibilities between APIs, workers, messaging and infrastructure.

```text
                         ┌──────────────────┐
                         │      Clients     │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │    Go APIs       │
                         │                  │
                         │ Balances / Ledger│
                         └────────┬─────────┘
                                  │
                           Events / Messages
                                  │
                                  ▼
                         ┌──────────────────┐
                         │   SNS / SQS      │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │      Workers     │
                         │                  │
                         │ Async Processing │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │     Storage      │
                         │      MySQL       │
                         └──────────────────┘

                    Infrastructure & Platform
                                  │
             ┌────────────────────┼────────────────────┐
             ▼                    ▼                    ▼
        Kubernetes            Terraform            Observability
             │                    │                    │
          Minikube            LocalStack        OpenTelemetry
                                                  Prometheus
                                                   Grafana
```

This architecture reflects my interest in building backend systems where application code, messaging, infrastructure and observability work together as part of a cohesive platform.

---

# 🛠️ Technology Stack

```text
Languages
├── Go
└── Java

Backend
├── REST APIs
├── Microservices
├── Distributed Systems
└── Event-Driven Architecture

Cloud
├── AWS
├── SQS
└── SNS

Infrastructure
├── Kubernetes
├── Docker
├── Terraform
├── Minikube
└── LocalStack

Databases
├── MySQL
└── Flyway

Observability
├── OpenTelemetry
├── Prometheus
├── Grafana
└── Zipkin

AI
├── Ollama
├── Local LLMs
└── AI-assisted development
```

---

# 📚 Engineering Principles

I value:

- **Simplicity over unnecessary complexity**
- **Separation of concerns**
- **Clear boundaries between services**
- **Explicit and maintainable architecture**
- **Automation**
- **Observability**
- **Resilience**
- **Reproducible infrastructure**
- **Continuous learning**

---

# 📈 Current Focus

Currently focused on deepening my expertise in:

**Go · Distributed Systems · Cloud-Native Architecture · AWS · Kubernetes · Event-Driven Systems · Observability · AI-assisted Software Engineering**

I'm particularly interested in backend engineering challenges involving **high-scale systems, asynchronous processing, distributed architectures and cloud-native platforms**.

---

# 🤝 Let's Connect

I'm open to connecting with engineers, architects, recruiters and companies working on interesting backend and distributed-systems problems.

### LinkedIn

[linkedin.com/in/clodoaldomarques](https://www.linkedin.com/in/clodoaldomarques/)

### GitHub

[github.com/clodoaldomarques](https://github.com/clodoaldomarques)

---

> Building backend systems, exploring distributed architectures, and continuously learning new ways to solve engineering problems.
