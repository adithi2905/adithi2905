# Adithi Varadarajan

Backend and distributed systems engineer with an edge in AI infrastructure. I build production-grade backend systems and when AI is involved, I build the layer that makes it reliable.

> *The hardest part of building AI systems isn't the model. It's everything around it the infrastructure, the evaluation, the failure modes, and the incentives that determine whether it actually works in the real world.*

---

## What I've built

**[LLMWatch](https://github.com/adithi2905/LLMWatch)** LLM observability middleware for Python  
One wrapper call instruments latency, TTFT, cost, and multi-agent metrics across OpenAI, Anthropic, and Groq. Verified against 1,049 real API calls, 486K tokens, $0.125 tracked spend. Avg TTFT 1.0s vs 3.3s total latency streaming TTFT not available out-of-the-box in LangSmith or Helicone. CI passing on Python 3.10/3.11/3.12.

**[SupplySense AI](https://github.com/adithi2905/cummins_xtern_challenge)** Multi-agent supply chain backend, built for Cummins  
Flask REST backend with MCP servers, JWT-based RBAC, and deterministic triage layer separating rule-based API responses from LLM reasoning. What-if simulation endpoints evaluating WAIT, EXPEDITE, and SWITCH scenarios with quantified cost-impact in response payload. Presented at TechPoints Xtern Challenge.

**[EcoBer](https://github.com/adithi2905/ecober)** Carbon-aware ride-sharing backend  
Spring Boot distributed backend with Redis caching as the primary fix for ride state race conditions, enabling consistent trip assignment under concurrent load. Deployed on AWS Aurora Serverless handling geospatial driver matching and trip lifecycle orchestration.

**[Credify](https://github.com/adithi2905/unified-kyc-system)** Age verification middleware  
Reusable identity verification plugin issuing W3C Verifiable Credentials inside existing vendor flows, with Amazon QLDB audit layer for tamper-proof event logging. Incubated at The Mill Accelerator, Shoemaker Innovation Center, and IU Innovates.

**[Graphlix](https://github.com/adithi2905/graphlix)** Movie recommendation API  
Flask REST API serving Enhanced NGCF recommendations user-based collaborative filtering, cold start via reverse embedding mapping, fuzzy title matching. NDCG@10 improved from 0.36 to 0.6 through attention mechanisms and batch normalization.

---

## Stack

**Languages** Python, Java, SQL, JavaScript  
**Backend** Spring Boot, Flask, REST APIs, PostgreSQL, Redis, Kafka, Neo4j, MongoDB  
**Cloud** AWS, Docker, Kubernetes, GitHub Actions, CI/CD  
**AI / Infra** OpenAI, Anthropic, Groq, Prometheus, Grafana, multi-agent systems, MCP, RAG

---

## Experience

3+ years at **Bank of America** as Senior Software Engineer distributed systems, infrastructure automation, 260K+ servers at 99.99% uptime.  
Currently: **M.S. Computer Science** at Indiana University Bloomington (May 2026).

---

*Open to backend, AI infrastructure, and platform engineering roles.*
