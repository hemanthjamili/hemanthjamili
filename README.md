<h1 align="center">Hi, I'm Hemanth Jamili 👋</h1>

<h3 align="center">
Staff Software Engineer · Distributed Systems · Platform Engineering
</h3>

<p align="center">
  <i>I build systems that scale and platforms that create leverage.</i>
</p>

<p align="center">
  <a href="https://hemanthjamili.github.io/profile/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/hemanthjamili/">LinkedIn</a>
</p>

---

## About

I'm a **Staff Software Engineer with 9+ years of experience** designing and scaling distributed systems, high-throughput backend platforms, and shared engineering capabilities.

My work sits at the intersection of **backend engineering, distributed data processing, and platform architecture**. I enjoy solving complex technical problems, especially when the solution can become a reusable capability that helps other teams move faster.

Currently, my work includes large-scale identity resolution, centralized IAM, reusable backend platform components, real-time bidding systems, and AI-powered semantic search.

**Open to Staff, Lead & Platform Engineering roles across Backend and Distributed Systems.**

---

## What I Work On

- ⚡ **Distributed Systems** — High-throughput backend architectures and large-scale data processing
- 🏗️ **Platform Engineering** — Shared capabilities that create leverage across teams and products
- 🔐 **Identity & Access Management** — Multi-tenant authentication, authorization, RBAC, and policy-based access
- 📊 **Distributed Data Processing** — Apache Spark, Apache Iceberg, and large-scale data pipelines
- 🎯 **AdTech Platforms** — Real-Time Bidding, DSP systems, SSP integrations, and high-QPS services
- 🤖 **Applied AI** — Semantic search, vector retrieval, embeddings, AWS Bedrock, and LLM-powered applications

---

## Selected Engineering Work

### 🔗 Massive-Scale Identity Resolution

Re-architected a legacy HTTP/MongoDB identity platform into a **Spark-native architecture using Apache Iceberg and EMR-on-EKS**, orchestrated through Airflow.

- Resolves identities against a **65B+ historical mapping dataset**
- Processes **10B+ incoming device records daily**
- Reduced end-to-end processing from **~18–20 hours to ~60 minutes**
- Designed shuffle-efficient processing using **Iceberg Storage Partition Joins**
- Achieved **zero OOMs and zero disk spills** at production scale
- Implemented deterministic and idempotent ID resolution to prevent duplicate assignments
- Added incremental identity activity and opt-out state tracking
- Automated metadata cleanup and compaction to control small-file fragmentation and maintain stable performance

### 🔐 Centralized Identity & Access Management Platform

Built and own a centralized **IAM platform serving 15+ microservices**, replacing fragmented per-service authentication and authorization implementations.

Key capabilities include:

- Multi-tenant authentication
- JWT and API-key issuance
- Fine-grained role- and policy-based access control
- Shared token introspection and validation APIs
- Standardized authentication and authorization across services

The platform provides a shared security foundation and reduces duplicated implementation effort across engineering teams.

### 🧩 Reusable Backend Platform SDK

Architected a reusable **Java/Spring Boot platform SDK adopted across 8+ products**, providing shared building blocks for common backend capabilities.

The SDK includes:

- Authentication and RBAC
- Distributed caching
- NoSQL data-access layers
- Request-level tracing and observability
- Metrics instrumentation
- Standardized error handling

Automated semantic-versioned releases through CI/CD to an internal artifact registry, making shared capabilities easier to consume and evolve across products.

### ⚡ High-Throughput Real-Time Bidding Platform

Designed and scaled backend systems for a distributed **Real-Time Bidding platform handling 100K+ requests per second**.

Key areas include:

- Low-latency backend processing
- Distributed system design
- Multi-SSP and ad-exchange integrations
- High-throughput request handling
- Scalable service architecture

The platform contributes to approximately **60% of company revenue**.

### 🔎 AI-Powered Semantic Search

Built an AI-powered semantic search platform indexing **100K+ brands, audiences, and locations** using:

- Vector search
- Embeddings
- Vector databases
- AWS Bedrock
- LLM-powered retrieval

---

## Platform Impact

A significant part of my work focuses on building systems that other engineers and products can reuse.

**15+ services, one IAM foundation.**

**8+ products, one shared platform SDK.**

I have also helped standardize engineering workflows through:

- GitHub Actions
- Automated releases
- Release tagging
- Conventional commits
- PR and commit conventions
- Architecture and code reviews

I enjoy solving difficult technical problems, but I get the most satisfaction when the solution also makes other engineers faster and removes problems they would otherwise have to solve repeatedly.

---

## Core Technologies

**Backend & Platform**

`Java` · `Spring Boot` · `Microservices` · `REST APIs` · `Kafka` · `Redis`

**Distributed Systems & Data**

`Apache Spark` · `Apache Iceberg` · `Airflow` · `Distributed Data Processing`

**Cloud & Infrastructure**

`AWS` · `EMR-on-EKS` · `ECS` · `S3` · `Docker` · `GitHub Actions` · `CI/CD`

**Platform Engineering**

`System Design` · `IAM` · `Multi-tenancy` · `JWT` · `RBAC` · `API Design` · `Observability`

**Applied AI**

`Semantic Search` · `Vector Search` · `Embeddings` · `AWS Bedrock` · `LLM-powered Retrieval`

---

## Currently Exploring

I'm actively exploring and experimenting with:

- 🤖 AI agents and agentic workflows
- 🔗 Model Context Protocol (MCP)
- 🧠 LLM-powered developer workflows
- 🏗️ AI-assisted platform engineering
- ⚙️ Distributed systems performance and scalability patterns
- 📚 Building practical examples of backend and system design concepts

---

## What You'll Find Here

I'm building this GitHub profile as a public engineering portfolio.

Over time, I plan to add practical repositories and experiments around:

- Distributed systems patterns
- Java and Spring Boot platform components
- Apache Spark and Apache Iceberg
- System design implementations
- Large-scale data processing
- Backend architecture patterns
- AI-powered backend applications

---

## Let's Connect

If you're interested in discussing distributed systems, backend architecture, platform engineering, or building systems at scale, feel free to connect.

🌐 **Portfolio:** https://hemanthjamili.github.io/profile/

💼 **LinkedIn:** https://www.linkedin.com/in/hemanthjamili/

**Open to Staff, Lead & Platform Engineering roles across Backend and Distributed Systems.**
