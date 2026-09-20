# Interview Prep Context

## Purpose

This file is portable context for continuing the interview-preparation work in another ChatGPT conversation.

## Candidate profile

- Current role: Senior Staff Engineer at PayPal.
- Earlier role: Principal Software Engineer / Principal Backend Java Engineer at Priceline.
- Experience: 11+ years.
- Primary language: Java.
- Core backend/distributed-systems areas: Spring Boot, Kafka, Kafka Streams, Kafka Connect, GCP/GKE, Firestore, BigQuery, GCS, Pub/Sub, Solr/Lucene, OpenSearch, Spark, Beam, Flink, gRPC, REST, Vertex AI/GenAI.

## Resume-driven strengths to prepare

The resume material discussed previously includes:
- PayPal Real-Time Profile Store.
- PayPal Centralized Decisioning Platform.
- 8+ architecture RFCs and architecture review boards.
- Bigtable to BigQuery/Spark optimization with a reported 60% runtime reduction.
- Customer Data Platform / personalization.
- LLM / agent architecture.
- Priceline enterprise identity resolution.
- Kafka platform leadership across 50+ applications.
- Search/typeahead with single-digit-ms p99.
- Mentoring 14 engineers.

Treat these as interview story candidates. Do not invent metrics, architecture details, ownership boundaries, or outcomes that are not in the resume or supplied by the candidate.

## Senior Staff interview priorities

The preparation should emphasize:
1. Architecture judgment.
2. System design at scale.
3. Technical strategy.
4. Influence without authority.
5. Cross-team adoption.
6. Deep project ownership.
7. Execution under ambiguity.
8. Coding fluency without over-investing in generic LeetCode.

## Standard system-design flow

### 1. Requirements
Functional requirements, non-functional requirements, users, consistency, latency, availability, durability, privacy/security.

### 2. Scale
QPS, peak QPS, data size, growth, read/write ratio, hot keys, retention.

### 3. Architecture
Clients → API/service → cache/storage/streaming layer → asynchronous processing → observability.

### 4. Data model and APIs
Keys, partitioning, indexes, TTL, schema evolution, idempotency.

### 5. Distributed systems
Consistency, ordering, retries, deduplication, concurrency, backpressure, leader election, failure isolation.

### 6. Reliability
Dependency failures, partial failures, regional failure, replay/recovery, graceful degradation.

### 7. Trade-offs
Explain at least two alternatives and why the chosen design fits the requirements.

### 8. Evolution
MVP → scale-up → multi-region → platformization → cost optimization.

## Coding focus

Prefer practical Staff-level coding over a large quantity of generic problems:
- HashMap/frequency patterns
- intervals
- heaps
- graphs/BFS/DFS
- topological sorting
- binary search
- sliding window
- concurrency
- producer/consumer
- cache and TTL
- schedulers
- rate limiting
- thread-safe data structures

Default to clean Java with explicit complexity and concurrency discussion.

## Behavioral framework

Build reusable STAR stories for:
- architecture disagreement
- influencing without authority
- failed decision
- ambiguous problem
- incident / production failure
- major migration
- mentoring
- raising engineering standards
- delivering through multiple teams
- saying no / reducing scope
- strategic technical investment

## Interview bar

For every major project, be ready for three levels:

**Staff:** Can you design and operate this system?

**Senior Staff:** How did you get multiple teams to adopt the architecture?

**Principal-level:** Why should the organization build this capability, what strategy does it enable, and what alternatives did you reject?

## Current repository

This repository is the central study repo. Keep new material consistent with the structure above and use Java by default for implementation examples.
