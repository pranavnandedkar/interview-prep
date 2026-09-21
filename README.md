# Senior Staff Engineer Interview Prep
https://hld.handbook.academy/curriculum/case-studies/url-shortener/

A practical interview-preparation repository for Staff / Senior Staff backend and distributed-systems interviews.

## Goal

Prepare for interviews that test more than coding: system design, architecture judgment, technical strategy, influence, execution, and deep ownership of large distributed systems.

## Personalization

The curriculum is tailored to the user's background:
- Senior Staff Engineer at PayPal
- Earlier Principal Software Engineer / Principal Backend Java Engineer at Priceline
- 11+ years of backend/distributed-systems experience
- Java and Spring Boot as the default implementation stack
- Kafka/Kafka Streams/Kafka Connect, GCP/GKE, Firestore, BigQuery/GCS/Pub/Sub
- Solr/Lucene/OpenSearch, Spark, Beam, Flink, gRPC/REST, Vertex AI/GenAI

## Interview weighting

| Area | Target |
|---|---:|
| Coding | 15% |
| System Design | 25% |
| Architecture & Technical Leadership | 25% |
| Project / Resume Deep Dive | 15% |
| Behavioral & Influence | 15% |
| Product / Strategy | 5% |

These are preparation priorities, not interview guarantees.

## Repository structure

- [01-system-design](01-system-design/README.md) — distributed-system design practice
- [02-architecture-leadership](02-architecture-leadership/README.md) — RFCs, trade-offs, strategy, influence
- [03-resume-deep-dive](03-resume-deep-dive/README.md) — turn resume bullets into 10–15 minute deep dives
- [04-coding](04-coding/README.md) — targeted Java coding practice
- [05-behavioral](05-behavioral/README.md) — leadership, conflict, failure, influence, mentorship
- [06-mocks](06-mocks/README.md) — mock interview loops
- [07-fundamentals](07-fundamentals/README.md) — distributed-systems fundamentals
- [system-design-context.md](system-design-context.md) — portable context for another ChatGPT session

## Staff-level answer framework

1. Clarify requirements and constraints.
2. Establish scale and SLOs.
3. Propose the simplest viable architecture.
4. Define APIs and data model.
5. Explain partitioning, consistency, concurrency and scaling.
6. Walk through failure modes and recovery.
7. Discuss trade-offs and rejected alternatives.
8. Explain evolution, operations, cost and organizational adoption.

## First deep dives

1. Real-Time Profile Store
2. Centralized Decisioning Platform
3. Customer Identity Resolution
4. Enterprise Kafka Platform
5. Customer Data Platform / real-time segmentation
6. Search / typeahead
7. Agentic / LLM architecture
8. Rate limiter

The first three should become polished 45–60 minute Staff/Senior Staff system-design exercises.
