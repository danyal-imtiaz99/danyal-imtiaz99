# Danyal Imtiaz

Backend software engineer with a focus on Java, Spring Boot, and the systems
that run underneath enterprise applications — batch pipelines, event-driven APIs,
microservice ecosystems, and the debugging work that comes with all of it.

I've spent four years in enterprise fintech infrastructure. That experience gave me
exposure to real production complexity. What it didn't always give me was the time
to understand it deeply. That's what I'm doing now — building the technical
foundation that turns experience into understanding.

I care about clean code, honest documentation, thorough testing, and the kind of
engineering that holds up when someone else has to maintain it.

---

## Current Build Direction

I'm actively exploring how agentic AI can support backend engineering workflows —
not as a replacement for fundamentals, but as a practical layer on top of them.

Specifically: using LLM-backed tools to assist with documentation, test generation,
legacy code comprehension, and service-level analysis inside Spring Boot microservice
ecosystems. The goal is not to automate engineering. It's to reduce the time
engineers spend on the parts of complex codebases that are slow to understand, so
they can spend more time on the parts that actually require judgment.

This work lives alongside OCP/OpenShift modernization, Spring Batch pipelines,
and REST API design — not as a separate track, but as part of the same question:
how do you work effectively in a large, complex backend system?

---

## Core Engineering Focus

**Languages & Frameworks**
Java 17+, Spring Boot 3, Spring Batch, Spring Security, Spring Data JPA, Hibernate

**Messaging & Events**
Apache Kafka, event-driven architecture, async processing patterns

**Data**
MySQL, Oracle, MongoDB, PostgreSQL — schema design, query tuning, data migrations

**Infrastructure & CI/CD**
Docker, OpenShift / OCP, GCP (Cloud Run, Cloud SQL), Harness, GitHub Actions

**Testing**
JUnit 5, Mockito, Testcontainers, BDD / Cucumber

**Practical AI Tooling**
Spring AI, agentic workflows, LLM-assisted documentation and test support

**Build & Tools**
Maven, Gradle, Postman, IntelliJ IDEA, Swagger / OpenAPI

---

## How I Think

I want to understand why a system is slow before I change it.
I document what I learn because clarity is part of the work, not extra work.
I write tests before I call something done — not because I'm told to, but because
I've seen what happens when they're not there.
I treat code review as one of the most valuable things a team can do together.
When something breaks, I want to own the investigation, not route it away.
I try to be the kind of engineer people can ask questions without judgment.
I don't think being unsure about something is a weakness.
I think pretending you're not unsure is.

---

## What I'm Building

### [`loan-application-processor`](https://github.com/danyal-imtiaz99) *(in progress)*
Event-driven loan processing API with a Kafka-based state machine, idempotent
write handling, and a Testcontainers-backed integration test suite.

`Java 17 · Spring Boot 3 · Kafka · MySQL · Docker · Testcontainers`

*Demonstrates: API design, event-driven state transitions, idempotency,
fault-tolerant processing, integration testing with real infrastructure.*

---

### [`batch-data-pipeline`](https://github.com/danyal-imtiaz99) *(in progress)*
Spring Batch pipeline with configurable chunk processing, skip/retry policy,
restartable job execution, and a REST trigger with status polling.

`Spring Batch · MySQL · Docker · JUnit 5`

*Demonstrates: Chunk-oriented processing, skip listeners, job restartability,
operational concerns — the batch patterns that matter in production.*

---

### [`service-doc-assistant`](https://github.com/danyal-imtiaz99) *(planned)*
CLI tool that analyzes a Spring Boot microservice codebase and uses an LLM
to generate structured service documentation: endpoint inventory, data flow
summary, dependency map, and test coverage gaps.

`Java · Spring AI · Spring Boot · Docker`

*Demonstrates: Practical agentic AI applied to backend engineering. Not a chatbot.
A tool that helps engineers understand large codebases faster.*

---

### [`inventory-service`](https://github.com/danyal-imtiaz99) *(planned)*
Clean microservice with layered architecture, domain validation, idempotency keys,
soft delete, and a full Testcontainers integration test suite.

`Spring Boot 3 · PostgreSQL · Testcontainers · Springdoc OpenAPI`

*Demonstrates: Clean API design, exception hierarchy, test discipline, and
the kind of code quality that survives a code review.*

---

## Current Focus

- **Java internals** — JVM memory model, garbage collection, concurrency primitives
- **Networking fundamentals** — TCP/IP, DNS, HTTP/HTTPS from first principles
- **Data structures & algorithms** — building the reasoning precision that interviews surface
- **System design** — distributed patterns, consistency models, practical tradeoffs
- **Spring Boot depth** — security, batch, advanced configuration, production observability
- **Agentic AI** — Spring AI, RAG pipelines, LLM tool use for engineering workflow support

---

## Contact

[LinkedIn](https://www.linkedin.com/in/danyal-imtiaz/) · danyal.imtiaz99@gmail.com
