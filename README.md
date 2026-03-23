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

* Built an orchestration layer coordinating modular decision stages across services
* Deterministic engine computes cost/time tradeoffs under constraints
* Integrated LLM-based components for scenario evaluation alongside deterministic logic
* MCP-style tool adapters for operations, supplier data, and decision logging
* Implemented RBAC using JWT for role-based access
* Exposes “what-if” simulation endpoints returning quantified outcomes

---

### **[EcoBer](https://github.com/adithi2905/ecober)**

**Distributed ride allocation system**
*Tech: Java, Spring Boot, Redis, AWS Aurora*

Spring Boot backend for real-time ride matching and trip lifecycle management.

* Managed distributed ride state under concurrent requests using Redis
* Resolved race conditions in driver assignment under load
* Implemented ranking logic (proximity, trust score, emissions) under real-time constraints
* Coordinated trip lifecycle with consistent state transitions across services

---

### **[Credify](https://github.com/adithi2905/unified-kyc-system)**

**Identity verification backend**
*Tech: Java, Spring Boot, REST APIs, OCR, Hashing*

Backend pipeline for extracting identity data from documents and issuing reusable credentials.

* Extracts structured identity data from documents using OCR
* Issues credentials reused across verification workflows
* Eliminates repeated document processing for returning users
* Introduced hashed audit logs for traceability and tamper detection
* Handles multi-step verification flows with consistent state transitions

---

### **[Graphlix](https://github.com/adithi2905/graphlix)**

**Recommendation API**
*Tech: Python, Flask, Neo4j, REST APIs*

Backend API for movie recommendations using collaborative filtering and graph-based techniques.

* Improved ranking quality (NDCG@10 from 0.36 → 0.6)
* Handles cold-start scenarios using embedding-based mapping
* Supports fuzzy title matching and user-based recommendations

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

ctly where you want to land.
