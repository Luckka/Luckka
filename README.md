<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=Senior+AI+%26+Backend+Engineer;RAG+%7C+Agents+%7C+Evals;Python+%7C+C%23%2F.NET+%7C+AWS;Building+RagKit%2C+IAEngine+%26+InfraSentinel" alt="Typing introduction" />

<h1>Hi, I'm Lucka Silva 👋</h1>

<p>
Senior Backend Engineer building reliable distributed systems and AI-powered engineering platforms with C#, .NET and AWS.
</p>

<p>
<a href="https://www.linkedin.com/in/lucka-silva-94b854201/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://www.instagram.com/lucka_denubila/">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
</a>
<a href="mailto:luckadev.silva@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
</p>

<img src="https://komarev.com/ghpvc/?username=Luckka&style=flat-square&color=36BCF7" alt="Profile views"/>

</div>

---

## About me

I believe software engineering is about understanding complex problems, designing reliable systems and delivering solutions that create measurable value.

I am a Senior Backend Engineer with 6+ years of experience building high-throughput financial and distributed systems using C#/.NET and AWS.

My work focuses on:

- scalable backend services;
- event-driven architectures;
- asynchronous processing;
- resilient financial workflows;
- AI-powered backend systems;
- security and identity validation;
- infrastructure automation;
- observability and engineering quality.

I enjoy working at the intersection of software architecture, cloud infrastructure and artificial intelligence.

---

## ⭐ Flagship project

### [RagKit](https://github.com/Luckka/RagKit)

> **Production-grade, provider-agnostic RAG toolkit in Python, built around measured retrieval quality.**

<p>
<img src="https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Bedrock"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white" alt="Pinecone"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://github.com/Luckka/RagKit/actions/workflows/ci.yml/badge.svg" alt="CI"/>
</p>

RagKit turns any document collection (PDF, DOCX, PPTX, HTML) into a searchable knowledge base, and proves with numbers which retrieval strategy actually works for it.

- **Structure-aware ingestion** with Docling: heading breadcrumbs, tables kept intact, page-level citations;
- **Hybrid retrieval**: dense embeddings + BM25 sparse vectors fused with Reciprocal Rank Fusion;
- **Two-stage retrieval**: a cross-encoder reranker (Cohere Rerank 3.5) on top of hybrid recall;
- **Metadata-aware query routing**: identifiers in a question boost matching chunks as a soft filter;
- **Built-in evaluation**: synthetic golden sets and hit@k / MRR comparisons across configurations;
- **Provider-agnostic**: AWS Bedrock (Claude, Cohere) or OpenAI behind the same interfaces;
- **Corpus-as-config**: a new document collection is a YAML file, not a code fork;
- **Engineering quality**: typed Python, offline tests with fakes, CI with lint and a data-leak guard.

```text
Documents → Docling → Structure-aware chunks → Dense + BM25 (Pinecone)
                                                      ↓
Question → Query hints → Hybrid search (RRF) → Cross-encoder rerank → Top-k with citations
                                                      ↓
                                     Evaluation: hit@1, hit@5, hit@10, MRR
```

---

## Featured projects

### [IAEngine](https://github.com/Luckka/IAEngine)

A technology-neutral AI engineering engine for coordinating software development workflows through specialized agents.

IAEngine provides:

- agent orchestration;
- task and milestone execution;
- deterministic validation;
- independent review;
- remediation loops;
- retries and recovery;
- persistent execution state;
- approval boundaries;
- `HUMAN_REQUIRED` decisions;
- semantic Git checkpoints;
- project adapters and validators.

The architecture is designed to support multiple consumers without embedding project-specific rules into the engine core.

```text
IAEngine.Core
      ↓
Project Adapter
      ↓
OnlineOS | InfraSentinel | Future Projects
```

### [InfraSentinel](https://github.com/Luckka/InfraSentinel)

> **An AI-orchestrated infrastructure security and resilience engineering platform built with C#/.NET.**

InfraSentinel evaluates whether infrastructure is secure, resilient, observable and capable of handling failure before it reaches production.

Unlike a traditional scanner, InfraSentinel combines:

- AI-driven engineering orchestration;
- deterministic security and resilience validators;
- Terraform and IaC static analysis;
- architecture defense gates;
- infrastructure invariants;
- observability and evidence generation;
- remediation workflows;
- human approval boundaries;
- semantic Git checkpoints;
- adapters for different project technologies.

Powered by [IAEngine](https://github.com/Luckka/IAEngine), the workflow is:

```text
Task
  → Validation
  → Independent Review
  → Remediation
  → Human Approval
  → Evidence
  → Semantic Checkpoint
```

The platform is being developed with a local-first and deterministic approach before controlled cloud observation and real infrastructure integrations.

---

## Engineering focus

### Backend and cloud

- C#
- .NET
- ASP.NET Core
- Entity Framework Core
- REST APIs
- AWS Lambda
- API Gateway
- SQS
- SNS
- DynamoDB
- S3
- ECS Fargate
- CloudWatch
- IAM
- Redis
- PostgreSQL
- SQL Server

### Architecture

- Clean Architecture
- SOLID
- Domain-Driven Design
- CQRS
- Saga orchestration
- Event-driven systems
- Microservices
- Transactional Outbox
- Idempotency
- Concurrency control
- Retry and recovery strategies
- Observability

### AI engineering

- LLM API orchestration
- Retrieval-Augmented Generation
- Vector databases
- AI agents
- Multi-agent collaboration
- Asynchronous inference workflows
- AI-assisted code review
- Deterministic quality gates
- Human approval boundaries
- MCP integration design

### Infrastructure and delivery

- Terraform
- Docker
- Kubernetes
- GitHub Actions
- CI/CD
- AWS Secrets Manager
- IAM roles
- Unit testing
- Integration testing
- Testcontainers
- Structured logging

---

## Engineering principles

```text
Autonomy for execution.
Strictness for quality.
Human authority at meaningful boundaries.
```

I value systems that are:

- explicit instead of heuristic;
- observable instead of opaque;
- deterministic where possible;
- secure by default;
- resilient under failure;
- easy to test;
- designed around clear boundaries;
- built with maintainability in mind.

---

## What I am building now

Currently focused on:

- building RagKit into a complete RAG platform: grounded answers with citations, RAGAS evals and guardrails;
- evolving IAEngine into a reusable engineering platform;
- building InfraSentinel as a security and resilience validation system;
- designing agent-driven development workflows;
- exploring controlled MCP boundaries for infrastructure observation;
- improving AI-assisted engineering practices;
- combining autonomous execution with deterministic quality gates and human approval.

---

## GitHub activity

<div align="center">

<a href="https://github.com/Luckka">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Luckka&theme=tokyonight&hide_border=true" alt="GitHub contribution streak"/>
</a>

</div>

<p align="center">
<a href="https://github.com/Luckka?tab=overview">
View my complete GitHub activity →
</a>
</p>
---

## Let's connect

I am interested in discussing:

- distributed systems;
- C#/.NET backend engineering;
- AWS architectures;
- event-driven systems;
- AI agents and orchestration;
- infrastructure security;
- resilience engineering;
- system design;
- engineering productivity.

<a href="mailto:luckadev.silva@gmail.com">Get in touch</a>
