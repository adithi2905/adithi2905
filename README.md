# Adithi Varadarajan

AI/ML Systems Engineer • Backend & Distributed Systems • LLM Infrastructure

## About

Backend and AI/ML systems engineer with **3+ years of experience** designing and building production-grade systems across enterprise and early-stage environments. My work spans **distributed systems, LLM infrastructure, multi-agent orchestration, and backend platform engineering** , often in contexts where reliability, observability, and scale shape the solution.

I'm particularly interested in **making AI systems production-ready and interpretable** , building the infrastructure layer that sits between raw LLM capabilities and real-world applications.

## Core Tech Stack

### Backend & Distributed Systems

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/>
</p>

### AI/ML Infrastructure & LLM Systems

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic-000000?style=flat"/>
  <img src="https://img.shields.io/badge/RAG-444444?style=flat"/>
  <img src="https://img.shields.io/badge/Multi--Agent%20Systems-555555?style=flat"/>
  <img src="https://img.shields.io/badge/MLOps-666666?style=flat"/>
</p>

### Cloud & DevOps

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
</p>

## Projects

### LLMWatch : Generic LLM Observability Middleware
**AI/ML Systems Infrastructure** (GitHub: https://github.com/adithi2905/LLMWatch)

- Designed and built **production-grade LLM observability middleware** supporting OpenAI, Anthropic, and Groq with zero-friction integration - metrics recorded in a single wrapped call.
- Engineered a **real-time cost forecasting engine** using a sliding window algorithm to project hourly, daily, and monthly LLM spend across providers and models.
- Implemented **multi-agent specific metrics** including disagreement scoring, debate turn tracking, and orchestrator decision distribution - uniquely designed for agentic AI architectures.
- Shipped a **provider-agnostic Python SDK** with Prometheus instrumentation, SQLite structured logging, retry logic, and an importable Grafana dashboard covering p95/p99 latency, token usage, and agent performance.

### SupplySense AI : Multi-Agent Supply Chain Decision System
**AI/ML Systems • Multi-Agent Orchestration** (GitHub: https://github.com/adithi2905/cummins_xtern_challenge)

- Built a **multi-agent decision system** for supply chain disruption management using a debate architecture where Financial, Risk, and Constraint agents independently evaluate scenarios before an Orchestrator Agent synthesizes a final recommendation.
- Designed a **deterministic triage layer** with fallback logic separating rule-based escalation triggers from LLM-driven reasoning, ensuring system stability when AI components fail.
- Implemented **disagreement scoring** using vote entropy across agents, routing high-conflict decisions to mandatory human review while allowing consensus decisions to auto-approve.
- Engineered a **what-if simulation engine** evaluating WAIT, EXPEDITE, and SWITCH scenarios across ±8 day production schedule shifts, giving operations managers quantified cost-impact comparisons before committing.
- Built on **Flask + React with MCP servers**, JWT-based RBAC, and CSV-backed operational data stores designed for rapid deployment in manufacturing environments.

### Longevity Intelligence Dashboard
**Analytics & Metrics Design** (GitHub: https://github.com/adithi2905/info-viz-predictive-health-analytics)

- Designed a **systems-driven longevity dashboard** combining patient health data with behavioral, environmental (AQI), population, and healthcare access signals.
- Introduced a **three-layer visualization framework** separating personal choices, environmental factors, and disease severity to explain state-level longevity variation.
- Implemented **DAX-based derived metrics** for survival estimation from incomplete clinical timelines and national/state performance indicators.

### Agentic AI Evaluation Framework
**LLM Systems • Evaluation Infrastructure** *(Indiana University — CSCI-B 659)*

- Designed a **discourse-level evaluation framework** for agentic AI systems, explicitly separating RAG-level retrieval quality from agent-level response correctness to prevent circular evaluation.
- Identified and formalized key failure modes including **masked retrieval regressions** and **silent hallucination repair** - cases where standard evaluators report success while correctness silently degrades.
- Implemented **LLM-as-a-judge pipeline** using frozen, claim-based ground truth independent of retrieval, enabling reliable detection of partial correctness, hallucinations, and omissions.
- Validated on **medical-domain questions**, producing structured JSON evaluation outputs with scores, hallucination flags, and explanations.

### Credify : Reusable Digital Identity Platform
**Systems Architecture & Product Strategy** (GitHub: https://github.com/adithi2905/unified-kyc-system)

- Ideated a **reusable identity and age-verification middleware** addressing the structural failure of cross-platform identity reuse - operators are disincentivized from enabling it because per-check revenue models penalize interoperability.
- Designed **W3C Verifiable Credential-based architecture** with an OIDC bridge allowing platforms to integrate via standard "Verify with Credify" flow without custom identity infrastructure.
- Implementing **Amazon QLDB audit layer** generating tamper-proof verification event logs meeting Utah Social Media Regulation Act and California Age-Appropriate Design Code compliance requirements.
- Drove **B2C → B2B architectural reframing**, focusing on platform operator incentives, compliance budget alignment, and regulatory tailwind as the primary growth vector.
- Recognized and incubated through **Shoemaker Innovation Center, The Mill Accelerator, and IU Innovates**.

### EcoBer : Carbon-Aware Ride-Sharing Backend
**Distributed Backend Engineering** (GitHub: https://github.com/adithi2905/ecober)

- Built a **Spring Boot distributed backend** handling ride requests, geospatial driver matching, and trip lifecycle orchestration at concurrent load.
- Implemented **Redis-based concurrency control, rate limiting, and fault-tolerant state transitions** ensuring correctness under race conditions.
- Integrated **carbon estimation and eco scoring** as first-class system outputs influencing downstream routing decisions.
- Deployed on **AWS with Aurora Serverless**, improving system reliability from ~60% to ~95% under sustained load.

### Graphlix : High-Performance Movie Recommendation System
**Recommender Systems & Evaluation** *(Indiana University — ENGR-E 536)*

- Implemented and benchmarked **Matrix Factorization, LightGCN, and Enhanced NGCF** models for personalized movie recommendations on large-scale graph data.
- Designed **stratified evaluation strategy** balancing active and sparse users to prevent metric inflation from heavy users dominating rankings.
- Enhanced NGCF with **attention mechanisms, layer normalization, and regularization**, achieving stronger NDCG and MAP ranking performance.

## What I'm Building Toward

Production AI/ML systems where **observability, reliability, and architectural clarity** determine whether intelligent systems can operate at scale — not just in demos.

> *The hardest part of building AI systems isn't the model. It's everything around it — the infrastructure, the evaluation, the failure modes, and the incentives that determine whether it actually works in the real world.*
