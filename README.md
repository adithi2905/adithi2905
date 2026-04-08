---

# Adithi Varadarajan

Software engineer focused on backend and distributed systems, building reliable, production-grade systems that operate under real-world constraints such as concurrency, latency, and consistency.

---

## What I’ve built

### **[LLMWatch](https://github.com/adithi2905/LLMWatch)**

**LLM observability middleware (Python)**
*Tech: Python, Prometheus, Grafana, REST APIs*

A wrapper that instruments latency, TTFT (time-to-first-token), cost, and token usage across multiple LLM providers.

* Tested on 1,000+ real API calls (~486K tokens, $0.125 tracked spend)
* Exposes system-level metrics via Prometheus and Grafana
* Captures TTFT, a key latency metric not surfaced by standard tooling
* Built for monitoring and debugging LLM-backed services under real workloads

---

### **[SupplySense AI](https://github.com/adithi2905/cummins_xtern_challenge)**

**Distributed decision system for supply chain workflows**
*Tech: Python, Flask, REST APIs, JWT, MCP*

Backend system for evaluating supply chain actions (WAIT, EXPEDITE, SWITCH) using structured inputs such as inventory and disruption risk.

* Built a decision system that evaluates supply chain actions (WAIT, EXPEDITE, SWITCH) under disruption scenarios using inventory levels and risk signals
* Designed a human-in-the-loop what-if simulator that quantifies cost and delay trade-offs (e.g., impact of delaying or expediting by up to 8 days)
* Implemented a deterministic decision engine modeling cost, shortage, and severity to generate actionable recommendations under constraints
* Integrated LLM-assisted evaluation alongside deterministic logic to support scenario reasoning without relying solely on probabilistic outputs
* Developed an orchestration layer coordinating modular decision stages, enabling extensibility across suppliers, logistics, and operational inputs
* Exposed APIs that return quantified decision outcomes, enabling operators to evaluate trade-offs before execution

---

### **[EcoBer](https://github.com/adithi2905/ecober)**

**Distributed ride allocation system**
*Tech: Java, Spring Boot, Redis, AWS Aurora*

Spring Boot backend for real-time ride matching and trip lifecycle management.

* Built a distributed ride allocation backend that ranks drivers using a composite score (proximity, trust, CO₂ efficiency), integrating sustainability into real-time matching
* Designed a closed feedback loop where trip-level CO₂ savings and vehicle fuel type continuously update driver scores, influencing future allocations
* Resolved race conditions in driver assignment under concurrent requests using Redis-backed coordination, improving reliability from 60% → 95% under load
* Implemented carbon scoring pipeline using Haversine-based distance estimation to compute per-trip emissions, mapped to normalized scores and cost metrics
* Developed scheduled scoring system that updates driver trust scores based on vehicle fuel type and historical efficiency, enabling long-term ranking optimization

---


## Stack

**Languages**
Python, Java, SQL, JavaScript

**Backend & Distributed Systems**
Spring Boot, Flask, REST APIs, PostgreSQL, Redis, Neo4j, MongoDB

**Cloud & DevOps**
AWS, Docker, Kubernetes, GitHub Actions, CI/CD

---

## Experience

**Senior Software Engineer : Bank of America**
Built and operated distributed systems for infrastructure orchestration across 260K+ servers, improving reliability as a part of the Never DOwn Intiative (99.99% uptime) and reducing MTTR by 60%.

**M.S. Computer Science : Indiana University Bloomington (May 2026)**

---

## Focus

Interested in backend and distributed systems roles involving:

* service orchestration and real-time systems
* concurrency, consistency, and failure handling
* systems operating at scale under production constraints

---

*Open to SWE roles in backend and distributed systems.*

---
