# Adriano Fratelli

**Senior Solutions Architect at MongoDB** · Data & AI platforms

I design and build production-minded proofs of value at the intersection of
operational data, search, AI, security, and real-time systems. My work turns an
architecture decision into something stakeholders can inspect, run, measure,
and challenge.

Public-facing overviews and code are written in English. PoV interfaces and
presentation scripts may remain in Brazilian Portuguese when they are designed
for local customer conversations.

## Selected work

| Project | What it demonstrates |
|---|---|
| [Torre — Atlas Control Plane](https://github.com/adrianofratelli-glitch/atlas-control-plane) | Fleet health, FinOps, scaling, Performance Advisor, observability, and an AI assistant grounded in live Atlas metrics |
| [MongoDB to Apache Iceberg](https://github.com/adrianofratelli-glitch/iceberg-mongodb-lakehouse) | Atlas Stream Processing CDC into S3/Iceberg, including updates, deletes, schema evolution, time travel, and measured propagation latency |
| [Queryable Encryption](https://github.com/adrianofratelli-glitch/atlas-queryable-encryption) | Equality and range queries over randomized ciphertext, with application and DBA views shown side by side |
| [RAG on MongoDB Atlas](https://github.com/adrianofratelli-glitch/atlas-rag-multitenant) | Hybrid retrieval with Vector Search and BM25, RRF fusion, reranking, citations, tenant isolation, and default-deny ACLs |
| [Economic Group Graph](https://github.com/adrianofratelli-glitch/atlas-graph-economic-group) | `$graphLookup`, fuzzy entity resolution, concentration analysis, visibility hierarchies, and measured graph workloads |
| [Multi-Agent on MongoDB](https://github.com/adrianofratelli-glitch/atlas-multi-agent-coordination) | MongoDB Atlas as both the data plane and coordination plane for stateful, observable, policy-constrained agents |
| [Agent Intelligence Layer](https://github.com/adrianofratelli-glitch/atlas-agent-intelligence-layer) | Prompts, model config, semantic cache, guardrails, and short/long-term agent memory stored as documents and changed live |
| [Search vs Vector vs Hybrid](https://github.com/adrianofratelli-glitch/atlas-search-vs-vector-marketplace) | Atlas Search, Vector Search, `$rankFusion` / `$scoreFusion`, analytics, and a LangGraph agent over a 20M-product catalog |
| [Time Series for Payments](https://github.com/adrianofratelli-glitch/atlas-timeseries-payments) | Live payment-rail ingestion into a time series collection, with physical bucket inspection and measured storage reduction |
| [Atlas Feature Showcase](https://github.com/adrianofratelli-glitch/mongodb-atlas-feature-showcase) | Online reindexing, hot/cold tiering, schema validation, Change Streams, ACID transactions, and Kafka / Stream Processing |

## Engineering focus

- MongoDB data modeling, performance, sizing, and distributed architecture
- Atlas Search, Vector Search, hybrid retrieval, and AI agent systems
- Real-time processing, change streams, CDC, and lakehouse integration
- Encryption in use, tenant isolation, guardrails, and auditable write paths
- Observability, resilience testing, FinOps, and evidence-based trade-offs
- React/FastAPI applications that make architecture inspectable in a live PoV

## How I approach a PoV

1. Start from the decision the customer needs to make.
2. Model the failure modes and security boundaries before the happy path.
3. Use synthetic or anonymized data and keep credentials outside the repository.
4. Measure behavior against real infrastructure whenever the claim depends on it.
5. Document limitations and trade-offs explicitly; a demo is evidence, not a production guarantee.

## Connect

- [LinkedIn](https://www.linkedin.com/in/afratelli/)
- São Paulo, Brazil

<sub>Opinions and experiments published here are my own. MongoDB and MongoDB Atlas are trademarks of MongoDB, Inc.</sub>
