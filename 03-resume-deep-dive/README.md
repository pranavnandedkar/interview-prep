# 03 — Resume Deep Dive

The goal is to make every important resume bullet defensible for 10–15 minutes of detailed questioning.

## PayPal

### Real-Time Profile Store
Prepare:
- problem and business context
- latency and throughput requirements
- storage model
- partitioning
- consistency
- write/read paths
- backfill and replay
- schema evolution
- failure handling
- multi-region behavior
- alternatives
- ownership and cross-team influence

### Centralized Decisioning Platform
Prepare:
- why centralize decisioning
- composable pipeline
- shared state
- inbound/outbound decisioning
- cross-channel frequency/fatigue management
- extensibility
- consistency
- latency
- adoption
- governance

### Architecture RFCs
Prepare:
- one representative RFC
- competing alternatives
- disagreement
- architecture review process
- decision rationale
- adoption
- measurable outcome

### Bigtable → BigQuery/Spark optimization
Known resume context discussed previously:
- reported 21 hours → 8 hours runtime
- reported 60% runtime reduction
- reported annual savings around $55K–$73K
- reported 4,600 compute hours saved

Be ready to explain exactly which architectural or implementation changes produced the improvement.

### Customer Data Platform / personalization
Prepare:
- data ingestion
- identity
- segmentation
- feature availability
- real-time vs batch
- privacy
- activation
- reliability

### LLM / agent architecture
Prepare:
- use cases
- model orchestration
- tool execution
- guardrails
- evaluation
- latency/cost
- observability
- failure handling
- human override

## Priceline

### Enterprise identity resolution
Prepare:
- entity model
- matching strategy
- deterministic vs probabilistic matching
- data quality
- deduplication
- scale
- false positives/negatives
- downstream consumers

### Kafka platform
Prepare:
- platform architecture
- migration
- multi-application adoption
- topic/schema/ACL lifecycle
- observability
- broker health
- consumer patterns
- reliability
- governance

### Search / typeahead
Prepare:
- indexing
- ranking
- personalization
- p99 latency
- cache
- shard/replica strategy
- relevance validation
- operational trade-offs

## Rule

Do not memorize polished answers. Memorize the decision points, constraints, trade-offs, metrics, and lessons.
