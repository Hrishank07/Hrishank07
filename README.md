<div align="center">

# Hrishank Chhatbar  
### Software Engineer · Backend, Cloud & Distributed Systems

<img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&size=26&duration=2800&pause=1000&color=8FA392&center=true&vCenter=true&width=700&lines=Backend+%26+Distributed+Systems;Low-Latency+Cloud+Infrastructure;Failure-Aware+System+Design;Practical+AI+Systems" />

*I build systems that stay fast when traffic spikes and failures cascade.*

</div>

---

## About Me

I’m a **backend and cloud-focused software engineer** who enjoys working on systems that sit on **critical paths** — where latency, correctness, and failure isolation actually matter.

At **Amazon Web Services (AWS Lambda)**, I worked on core reliability and traffic-protection mechanisms designed to prevent **platform-wide outages during large-scale surges**, protecting **millions of customer workloads**. I like building systems that fail gracefully, scale predictably, and don’t waste compute just because it’s available.

My interests span **distributed systems, cloud infrastructure, and applied AI**, with a strong bias toward production realism over demos.

- 🎓 M.S. in Engineering Management — USC  
- 🏢 Former SDE Intern — Amazon Web Services (Lambda Frontend Invoke Team)  
- 💡 Interested in: distributed systems, caching, load shedding, AI infrastructure  
- 🌱 Currently exploring: RAG pipelines, semantic caching, LLM optimization  

---

## Core Competencies

**Backend & Data**
- Java, Spring Boot  
- Python  
- Node.js  
- SQL (MySQL, MSSQL)

**Cloud & DevOps**
- AWS (Lambda, DynamoDB, S3, API Gateway)  
- Terraform (Infrastructure as Code)  
- Docker  
- CI/CD (Git, Jenkins)

**Frontend & AI**
- Angular, JavaScript  
- OpenAI, AWS Bedrock  
- HTML, CSS  

---

## Featured Projects

### 🗳️ Hybrid Semantic Acceleration Layer (HSAL)
*High-performance LLM request routing without wasted compute*

**Vision**  
Treat AI infrastructure like infrastructure — deterministic where possible, probabilistic only when necessary.

**What it does**  
HSAL eliminates the *vector processing tax* by intercepting identical and highly similar prompts **before** expensive embedding generation.

**How it works**
- ⚡ Sub-millisecond **L1 hash-based fast path** for identical prompts  
- 🔎 **L2 semantic retrieval** for paraphrased queries  
- 📉 Reduces embedding workload by **30–60%** in high-repeat traffic  
- 🛑 Fails open to preserve availability under partial outages  

> Cache first. Embed only when you must.

---

### 📄 Intelligent Document Q&A Platform (RAG-Based)
*Serverless, source-grounded document search*

**Vision**  
Make large document collections instantly searchable without sacrificing accuracy or traceability.

**What it does**  
A serverless AI-powered platform that lets users upload documents and ask natural-language questions, returning **precise, source-cited answers**.

**How it’s built**  
Fully serverless, event-driven architecture on AWS using **Amazon Bedrock** for RAG, **AWS Lambda** for orchestration, and **Terraform** for automated infrastructure.

---

### 📑 Serverless Resume Intelligence & Optimization API
*Understanding how automated systems read résumés*

**Vision**  
Help job seekers see their résumés the way ATS and screening systems actually do.

**What it does**  
An on-demand REST API that analyzes résumés against job descriptions and provides **ATS-focused feedback** on structure, keywords, and clarity.

**How it’s built**  
Built with **API Gateway and AWS Lambda**, powered by **OpenAI GPT models**, with fully automated deployments via **Terraform**.

---

## 🧠 What I Spend My Time On

Most of my GitHub activity revolves around **building, breaking, and stress-testing systems** rather than polishing UI.

- 🧩 Designing **failure-aware backend components** and load-sensitive logic  
- ⚡ Optimizing hot paths where **microseconds and contention matter**  
- 🛠️ Prototyping infrastructure ideas (caching, routing, orchestration) before they hit production  
- 🤖 Exploring **AI systems as infrastructure**, not demos — cost, latency, and correctness first  
- 🧪 Writing simulations and test harnesses to see how systems behave *when things go wrong*  

If a repo looks quiet, it’s probably because I’m:
> thinking → designing → breaking → fixing → repeating

---
