# Muhammad Argya Vityasy

**Backend Engineer → Cloud / DevOps Focus**

---

## What I Do

* Build backend systems using **Go (Gin)** and **Node.js (Express)**
* Design APIs, data models, and service boundaries
* Operate containerized workloads and self-managed infrastructure
* Work with **PostgreSQL, MongoDB, Redis**, and observability stacks

---

## Experience

**Backend Engineering Intern**

* Contributed to **Identity & Access Management (IAM)** systems
* Built internal SDKs for authentication and service integration
* Developed **AI agent-based automation** for internal workflows
* Wrote **integration tests and proof-tested libraries** to ensure reliability
* Focus: **security boundaries, system design, and interoperability**

---

## Selected Work

### **JOINMUN — Event Platform**

Backend system for international Model United Nations events

* Handles ~**1000 users** with **traffic spikes during registration windows**
* Ensured **data consistency under concurrent writes** (PostgreSQL transactions)
* Implemented **idempotent retries** for safe failure recovery
* Applied **timeouts and IP-based rate limiting** at middleware level
* Integrated **structured logging** for observability

**Focus:** reliability under burst traffic, failure handling, consistency

---

### **Self-Hosting Lab (DigitalOcean)**

Personal infrastructure for running and operating services

* Provisioned with **Terraform**, configured via **Ansible**
* Observability stack: **Prometheus · Grafana · Loki · Node Exporter**
* Secured services using **Cloudflare Zero Trust**
* Designed around **monitoring-first and controlled access principles**

**Focus:** infrastructure automation, observability, secure exposure

---

### **Omahto — Tryout Platform (Architecture)**

Online testing system for timed, multi-section evaluations

* Designed **microservice architecture** with **gRPC communication**
* Planned **Redis-based session/state management**
* Focused on isolating test execution under concurrent usage

> *Architecture-focused; implementation is partial*

---

### **Invenio RDM (GitOps) — In Progress**

Exploring GitOps workflows for research data platforms

* Kubernetes-based deployment model
* Git-driven infrastructure and environment control
* Exploring **OpenTelemetry for tracing and observability**

---

## Engineering Practices

* **Structured logging** for debuggability
* Moving toward **OpenTelemetry (tracing + metrics)**
* **Idempotent operations** and retry-safe design
* **Atomic database transactions** for consistency
* **Integration testing** for reliability before release

---

## Current Focus

* Kubernetes in constrained environments
* Infrastructure as Code (Terraform)
* CI/CD and deployment automation
* Designing systems that remain stable under real-world conditions

---

> “Continuous improvement is better than delayed perfection.”
