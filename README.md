# Adithi Varadarajan

Backend / Platform Engineer • AI Systems • Product-Oriented Problem Solving

---

## About
Backend and platform engineer with **3+ years of experience** building and evolving complex systems across enterprise and early-stage project environments. My work spans **distributed systems, backend architecture, analytics, and product reframing**, often in contexts where constraints and not ideal inputs shape the solution.

I’m particularly interested in **making complex domains interpretable and scalable**, whether through system design, derived metrics, evaluation frameworks, or incentive-aware architectures.

---

## Core Tech Stack (Backend / Platform)

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
</p>

---

## Analytics & AI (Applied, Evaluation-Focused)

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Recommender%20Systems-444444?style=flat"/>
  <img src="https://img.shields.io/badge/Ranking%20Metrics-555555?style=flat"/>
  <img src="https://img.shields.io/badge/System%20Evaluation-666666?style=flat"/>
</p>

**Focus Areas**
- Feature engineering & derived metrics  
- Ranking and relevance evaluation (NDCG, MAP)  
- System-level AI evaluation (not prompt-only metrics)  
- Interpretability-first analytics & dashboards  

---

## Projects

### Credify — Reusable Digital Identity Platform (B2B) 
**Ideator | Systems Architecture & Product Strategy** (GitHub: https://github.com/adithi2905/unified-kyc-system)

- Ideated a **reusable identity and age-verification platform** addressing why identity verification fails to scale across vendors.
- Designed **vendor-integrated verification APIs**, secure hashing pipelines, and **audit-first workflows** aligned with compliance and trust needs.
- Drove a **B2C → B2B architectural reframing**, focusing on enterprise incentives, integration friction, and repeat-verification economics.
- Recognized and incubated through the Shoemaker Innovation Center, The Mill Accelerator, and IU Innovates.
- Wrote a system-level analysis on identity adoption failures:
- <a href src="https://medium.com/@rememberaddy2905/why-reusable-identity-hasnt-scaled-and-what-could-change-that-1ba480e5cb91"/>
  *Why Reusable Identity Hasn’t Scaled — and What Could Change That* (Medium).
  
---

### EcoBer — Carbon-Aware Ride-Sharing Backend
**Backend / Platform Engineering**  (GitHub: https://github.com/adithi2905/ecober)

- Built a **Spring Boot backend** for ride requests, geospatial driver matching, and trip lifecycle orchestration.
- Implemented **Redis-based concurrency control, rate limiting, and fault-tolerant state transitions**.
- Integrated **carbon estimation and eco scoring** as system outputs influencing downstream decisions.
- Deployed on **AWS with Aurora Serverless**, improving reliability from **~60% → ~95% under load**.

---

### Longevity Intelligence Dashboard — U.S. Life Expectancy
**Analytics, Metrics Design & Visualization**  (GitHub: https://github.com/adithi2905/info-viz-predictive-health-analytics)

- Conceptualized a **systems-driven longevity dashboard** combining patient health data with **behavioral, environmental (AQI), population, and healthcare access context**.
- Introduced a **three-layer visualization framework** (personal choices, environment & population, disease severity) to explain longevity variation across states and years.
- Designed **derived longevity / survival metrics** from incomplete clinical timelines and implemented **DAX measures** for national averages and state-level performance indicators.
- Framed prediction as a **design extension**, prioritizing interpretability and transparent assumptions over model complexity.

---

### Graphlix — Movie Recommendation System (Associated with Indiana University Bloomington | Course ENGR-E 536 |  HIGH PERF GRAPH ANALYTICS )
**Recommender Systems & Evaluation** (Link: https://github.com/adithi2905/Graphlix)

- Implemented and compared **Matrix Factorization, LightGCN, and Enhanced NGCF** models for personalized movie recommendations.
- Designed a **fair evaluation strategy** using stratified user sampling to balance active and sparse users.
- Evaluated models using **NDCG and MAP**, focusing on ranking quality rather than raw accuracy.
- Enhanced NGCF with **attention, normalization, and regularization**, achieving stronger ranking performance and powering a prototype recommendation app.

---

## Agentic AI Evaluation Framework  (Associated with Indiana University | Course CSCI-B 659 | TOPICS ARTIFICIAL INTELLIGENCE KNOWLEDGE GRAPHS, LARGE LANGUAGE MODELS )
**Discourse-Level Evaluation • LLM-as-a-Judge • Governance-Aware Design** 

- Designed a **discourse-level evaluation framework** for agentic AI systems, explicitly separating **RAG-level retrieval quality** from **agent-level response correctness**.
- Identified key failure modes of FAQ/RAG-based evaluators, including **circular evaluation**, **masked retrieval regressions**, and **silent hallucination repair**.
- Implemented an **LLM-as-a-judge approach** using **frozen, claim-based ground truth** independent of retrieval, enabling detection of **partial correctness, hallucinations, and omissions**.
- Produced **structured JSON evaluation outputs** (scores, hallucination flags, explanations) and validated the approach on **medical-domain questions**, demonstrating reliable differentiation between correct, partially correct, and hallucinated responses.
  
---

## What I’m Interested In
Building **backend platforms and AI-enabled systems** where architecture, metrics, and incentives determine whether products scale responsibly in the real world.

---

> *I’m most excited by problems where the hard part isn’t implementation alone, but deciding what should exist, why, and how it can realistically work under constraints.*
