<!-- Profile README for Akshraj Chavda -->

<h1 align="center">Hi 👋, I'm Akshraj Chavda</h1>
<h3 align="center">Software Engineer | Backend Systems · AI Agents · Developer Infrastructure</h3>

<p align="center">
  I build production-oriented backend systems, agentic workflows, and security-data integrations.
  My work spans Python, Go, distributed processing, retrieval systems, and open-source engineering.
</p>

<p align="center">
  <a href="https://linkedin.com/in/akshraj-chavda">LinkedIn</a> ·
  <a href="mailto:akshrajchavda1520@gmail.com">Email</a> ·
  <a href="https://github.com/akshraj-05">GitHub</a> ·
  <a href="https://www.leetcode.com/akshraj_05">LeetCode</a>
</p>

---

## Open-Source Contributions — 18 Merged PRs

<p>
  <strong>18 merged pull requests</strong> across four Elastic open-source repositories:
  <strong>12 Integrations · 4 Elasticsearch · 1 Kibana · 1 Workflows</strong>
</p>

Primary author of the **IBM QRadar**, **IRONSCALES**, and **BeyondTrust EPM** integrations, plus the **Google Threat Intelligence (GTI) connector** and related workflows.

<details>
<summary><strong>Elastic Integrations — 12 merged PRs</strong></summary>

1. [#20566 — Set X-FP headers for Flashpoint HTTP requests](https://github.com/elastic/integrations/pull/20566)
2. [#20465 — Add Google Threat Intelligence vulnerability data stream](https://github.com/elastic/integrations/pull/20465)
3. [#20010 — Initial release of BeyondTrust EPM](https://github.com/elastic/integrations/pull/20010)
4. [#19465 — Improve BeyondTrust EPM Audit configuration and tests](https://github.com/elastic/integrations/pull/19465)
5. [#18707 — Add BeyondTrust EPM Event data stream](https://github.com/elastic/integrations/pull/18707)
6. [#18635 — Add BeyondTrust EPM Audit data stream](https://github.com/elastic/integrations/pull/18635)
7. [#18097 — Add Forescout Host data stream](https://github.com/elastic/integrations/pull/18097)
8. [#16741 — Add Flashpoint Vulnerability data stream](https://github.com/elastic/integrations/pull/16741)
9. [#16726 — Add Flashpoint Indicator data stream](https://github.com/elastic/integrations/pull/16726)
10. [#16714 — Add Flashpoint Alert data stream](https://github.com/elastic/integrations/pull/16714)
11. [#15982 — Initial release of IRONSCALES integration](https://github.com/elastic/integrations/pull/15982)
12. [#15302 — Initial release of IBM QRadar](https://github.com/elastic/integrations/pull/15302)

</details>

<details>
<summary><strong>Elasticsearch — 4 merged PRs</strong></summary>

1. [#138094 — Fix IRONSCALES ILM policy delete step](https://github.com/elastic/elasticsearch/pull/138094)
2. [#138485 — Backport fix to 9.2](https://github.com/elastic/elasticsearch/pull/138485)
3. [#138486 — Backport fix to 9.1](https://github.com/elastic/elasticsearch/pull/138486)
4. [#138487 — Backport fix to 8.19](https://github.com/elastic/elasticsearch/pull/138487)

</details>

<details>
<summary><strong>Kibana — 1 merged PR</strong></summary>

- [#285533 — Add Google Threat Intelligence connector](https://github.com/elastic/kibana/pull/285533)

</details>

<details>
<summary><strong>Elastic Workflows — 1 merged PR</strong></summary>

- [#60 — Add Google Threat Intelligence workflows](https://github.com/elastic/workflows/pull/60)

</details>

*The three Elasticsearch backports are separate merged pull requests and are counted individually.*

---

## About Me

- 💼 Software Engineer at **Crest Data**, working on backend platforms, AI-assisted engineering workflows, and security-data integrations.
- 🔭 Building **agentic systems**, retrieval services, and reliable data-ingestion pipelines.
- 🌱 Focused on **backend engineering, distributed systems, LLM evaluation, and AI infrastructure**.
- 🤝 Interested in backend, open-source, developer-tooling, and AI infrastructure projects.
- 🧠 Problem-solving: **1,000+ LeetCode problems**, including 175 Hard problems.
- 📍 Ahmedabad, Gujarat, India.

## Highlights

- Primary author of **three Elastic integrations**: IBM QRadar, IRONSCALES, and BeyondTrust EPM.
- Contributed a fix to **Elasticsearch core**, backported to three releases.
- Built a raw-log onboarding pipeline used for **200+ vendors**, reducing onboarding turnaround from 5 days to 10 minutes.
- Built an agentic TDD-generation workflow that reduced turnaround from 3 days to 5 minutes.
- Developed a five-agent code-generation framework that reduced Elastic package authoring from 4 days to 15 minutes across 12 packages.

## Experience

### Software Engineer · Crest Data
*December 2023 – Present | Ahmedabad, India*

- Shipped **18 merged PRs across four Elastic repositories**: Integrations, Elasticsearch, Kibana, and Workflows.
- Worked end-to-end on a multi-agent orchestration platform using **FastAPI, PostgreSQL, and Temporal**, spanning workflow, context-retrieval, and ingestion services; authored its HLD/LLD designs.
- Developed a **LangGraph + Gemini** agent that generates Technical Design Documents from schemas retrieved through MCP tool servers, reducing turnaround from 3 days to 5 minutes.
- Built a raw-log onboarding pipeline that infers event schemas across JSON/NDJSON, CSV, TSV, key-value, and syslog formats. It became the onboarding path for 200+ vendors and reduced turnaround from 5 days to 10 minutes.
- Designed an unsupervised log classifier that groups unlabeled logs by field structure so one representative sample per group reaches the LLM for event-type identification.
- Authored five agents—supervisor, analyzer, generator, reviewer, and tester—for an internal code-generation framework, reducing Elastic package authoring from 4 days to 15 minutes across 12 packages.

## Selected Projects

### [Tool Router — Routing-as-a-Service for Large Tool Catalogs](https://github.com/akshraj-05/tool-router)
**Python · FastAPI · MCP · Gemini · Docker**

- Built a retrieval layer that narrows a 64-tool agent catalog into a minimal, ordered tool plan.
- Combines local **TF-IDF + BM25 retrieval**, a confidence gate, and an LLM-based ordering step.
- Reported selection accuracy improved from 24% to 90%, with 98% fewer prompt tokens. The no-LLM path reached 83% in held-out testing.

### [HirePilot AI — AI Hiring Platform](https://github.com/akshraj-05/hirepilot-ai)
**Python · FastAPI · LangChain · OpenAI · PostgreSQL · Docker**

- Built a deployed hiring platform that bulk-ingests resumes, evaluates candidates against a job description, surfaces skill gaps, and supports candidate self-booking for interviews.
- Uses three agents for analysis, decision support, and insight generation, with separated data access and LLM chains.
- Recruiters confirm AI rejection recommendations before they take effect.

### [GoLang Kafka Streamline — Concurrency in Action](https://github.com/akshraj-05/GoLang-Kafka-Streamline-Concurrency-in-Action)
**Go · Kafka · MongoDB · Docker · YAML**

- Implemented a fault-tolerant ingestion pipeline with a Kafka producer and concurrent Go consumer.
- Uses goroutines, channels, and contexts, with message validation before persistence to MongoDB.

### AnonNote — Securely Encrypted Secrets with OAuth 2.0
**Node.js · Express · OAuth 2.0 · bcrypt · Express-session · EJS**

- An earlier project listed on my LinkedIn profile: a web application for sharing anonymous secrets.
- Implemented Google OAuth 2.0 authentication, bcrypt password hashing, and session-based login caching.

## Technical Skills

| Area | Technologies |
|---|---|
| Languages | Python, Go, JavaScript, C++, SQL |
| Backend | FastAPI, Node.js, Express, REST APIs, PostgreSQL, Temporal |
| AI & Agentic Systems | LangChain, LangGraph, MCP, RAG, tool calling, Gemini, OpenAI, Claude |
| Search & Data | Elasticsearch, Kibana, Logstash, embeddings, TF-IDF, BM25 |
| Distributed Systems | Kafka, workflow orchestration, event ingestion, concurrency |
| Cloud & Infrastructure | Docker, AWS (S3, SQS) |
| Engineering | HLD/LLD, evaluation harnesses, API design, Git/GitHub |

## Problem Solving

- **1,000+** LeetCode problems solved, including **175 Hard**.
- **339+** active days on LeetCode in the past year (as stated in my resume).
- **CodeChef:** 3-Star, rating 1748.
- **HackerRank:** 5-Star in C, C++, and SQL.

## Connect

<p align="left">
  <a href="https://linkedin.com/in/akshraj-chavda" target="_blank">LinkedIn</a> ·
  <a href="https://github.com/akshraj-05" target="_blank">GitHub</a> ·
  <a href="https://www.leetcode.com/akshraj_05" target="_blank">LeetCode</a> ·
  <a href="mailto:akshrajchavda1520@gmail.com">Email</a>
</p>

---

## GitHub Activity & Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=akshraj-05&show_icons=true&hide_border=true" alt="Akshraj's GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akshraj-05&layout=compact&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=akshraj-05&hide_border=true" alt="GitHub contribution streak" />
</p>

<p align="center">
  <img height="190em" src="https://leetcard.jacoblin.cool/akshraj_05?theme=light&font=Karma&ext=contest" alt="Akshraj's LeetCode statistics" />
</p>
