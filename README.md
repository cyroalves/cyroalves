# Cyro Alves

**Software Engineer** — full-stack product, data platform, and applied LLMs.
Espírito Santo, Brazil · open to remote

### About Me

Software engineer with around six years of experience in **Python** and **TypeScript**. For the last four I have been at **Play9**, a SaaS platform for influencer campaign management, billing and media data. I was part of the team behind **Playnest** — an application with roughly 100k users — working end to end there: data model and API, interface, third-party integrations, and the pipelines behind them.

**Most of my work lives in private repositories,** so the repository list here is much shorter than the work behind it. What that work looks like in practice:

- **End to end by default.** I design the schema, write the API, build the screen, and make sure the data arriving on both sides is trustworthy.
- **Data platform.** Airflow and dbt on BigQuery over GCP: a layered architecture (landing → trusted → refined → DW), idempotent `MERGE` upserts, SCD Type 2 state history, partitioning and clustering.
- **Production changes under a protocol.** Backfills and migrations with a dry-run, a scoped blast radius, before/after snapshots, and a second run to prove idempotency.
- **Integrations that survive the other side being down.** OAuth 1.0 TBA and 2.0, pagination, exponential backoff, rate limiting, and a transactional ledger for idempotent synchronization with asynchronous retry.
- **Applied LLMs, with a spine.** Versioned system prompts, explicit token budgeting, interchangeable model backends. And when an LLM does not pay off, I say so — for a PDF parser I measured OCR against an LLM and shipped deterministic extraction instead: no cost per document, auditable output.
- **Coding agents used structurally.** Skills, rules and subagents versioned in the production repository, and spec-driven development with PRDs as the input to the work.

I studied Physics at UFES before moving into software, which is probably why I would rather settle a question with a measurement than with an opinion.

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python&logoColor=3776AB)&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-05122A?style=flat&logo=typescript&logoColor=3178C6)&nbsp;
![SQL](https://img.shields.io/badge/-SQL-05122A?style=flat&logo=postgresql&logoColor=4479A1)&nbsp;
![Go](https://img.shields.io/badge/-Go-05122A?style=flat&logo=go&logoColor=00ADD8)&nbsp;
![Rust](https://img.shields.io/badge/-Rust-05122A?style=flat&logo=rust&logoColor=DEA584)

**Back-end and APIs**

![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=nodedotjs&logoColor=5FA04E)&nbsp;
![GraphQL](https://img.shields.io/badge/-GraphQL-05122A?style=flat&logo=graphql&logoColor=E10098)&nbsp;
![Apollo Server](https://img.shields.io/badge/-Apollo%20Server-05122A?style=flat&logo=apollographql&logoColor=white)&nbsp;
![TypeORM](https://img.shields.io/badge/-TypeORM-05122A?style=flat&logo=typeorm&logoColor=FE0803)&nbsp;
![Express](https://img.shields.io/badge/-Express-05122A?style=flat&logo=express&logoColor=white)&nbsp;
![Flask](https://img.shields.io/badge/-Flask-05122A?style=flat&logo=flask&logoColor=white)&nbsp;
![Redis](https://img.shields.io/badge/-Redis-05122A?style=flat&logo=redis&logoColor=FF4438)

**Front-end**

![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react&logoColor=61DAFB)&nbsp;
![Next.js](https://img.shields.io/badge/-Next.js-05122A?style=flat&logo=nextdotjs&logoColor=white)&nbsp;
![styled-components](https://img.shields.io/badge/-styled--components-05122A?style=flat&logo=styledcomponents&logoColor=DB7093)&nbsp;
![React Query](https://img.shields.io/badge/-React%20Query-05122A?style=flat&logo=reactquery&logoColor=FF4154)&nbsp;
![Zod](https://img.shields.io/badge/-Zod-05122A?style=flat&logo=zod&logoColor=3E67B1)&nbsp;
![Radix UI](https://img.shields.io/badge/-Radix%20UI-05122A?style=flat&logo=radixui&logoColor=white)

**Data and warehouse**

![BigQuery](https://img.shields.io/badge/-BigQuery-05122A?style=flat&logo=googlebigquery&logoColor=669DF6)&nbsp;
![dbt](https://img.shields.io/badge/-dbt-05122A?style=flat&logoColor=FF694B)&nbsp;
![Apache Airflow](https://img.shields.io/badge/-Apache%20Airflow-05122A?style=flat&logo=apacheairflow&logoColor=017CEE)&nbsp;
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql&logoColor=4169E1)&nbsp;
![MySQL](https://img.shields.io/badge/-MySQL-05122A?style=flat&logo=mysql&logoColor=4479A1)&nbsp;
![Firestore](https://img.shields.io/badge/-Firestore-05122A?style=flat&logo=firebase&logoColor=FFCA28)&nbsp;
![pandas](https://img.shields.io/badge/-pandas-05122A?style=flat&logo=pandas&logoColor=white)

**Cloud and DevOps**

![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-05122A?style=flat&logo=googlecloud&logoColor=4285F4)&nbsp;
![Terraform](https://img.shields.io/badge/-Terraform-05122A?style=flat&logo=terraform&logoColor=844FBA)&nbsp;
![Docker](https://img.shields.io/badge/-Docker-05122A?style=flat&logo=docker&logoColor=2496ED)&nbsp;
![Kubernetes](https://img.shields.io/badge/-Kubernetes-05122A?style=flat&logo=kubernetes&logoColor=326CE5)&nbsp;
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-05122A?style=flat&logo=githubactions&logoColor=2088FF)&nbsp;
![Linux](https://img.shields.io/badge/-Linux-05122A?style=flat&logo=linux&logoColor=FCC624)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git&logoColor=F05032)

**Applied AI and tooling**

![Claude Code](https://img.shields.io/badge/-Claude%20Code-05122A?style=flat&logo=claude&logoColor=D97757)&nbsp;
![Ollama](https://img.shields.io/badge/-Ollama-05122A?style=flat&logo=ollama&logoColor=white)&nbsp;
![whisper.cpp](https://img.shields.io/badge/-whisper.cpp-05122A?style=flat&logoColor=white)&nbsp;
![FFmpeg](https://img.shields.io/badge/-FFmpeg-05122A?style=flat&logo=ffmpeg&logoColor=388E3C)&nbsp;
![LangGraph](https://img.shields.io/badge/-LangGraph-05122A?style=flat&logo=langgraph&logoColor=1C3C3C)&nbsp;
![MCP](https://img.shields.io/badge/-MCP-05122A?style=flat&logo=modelcontextprotocol&logoColor=white)&nbsp;
![NumPy](https://img.shields.io/badge/-NumPy-05122A?style=flat&logo=numpy&logoColor=4DABCF)

**Testing and quality**

![pytest](https://img.shields.io/badge/-pytest-05122A?style=flat&logo=pytest&logoColor=0A9EDC)&nbsp;
![Jest](https://img.shields.io/badge/-Jest-05122A?style=flat&logo=jest&logoColor=C21325)&nbsp;
![Ruff](https://img.shields.io/badge/-Ruff-05122A?style=flat&logo=ruff&logoColor=D7FF64)&nbsp;
![ESLint](https://img.shields.io/badge/-ESLint-05122A?style=flat&logo=eslint&logoColor=4B32C3)

### Projects

#### [`ask-dont-search`](https://github.com/cyroalves/ask-dont-search) · hybrid retrieval, tool calling and a corrective agent

*When the answer is a number in a table, don't search text for it — ask the source.*

Question answering over 5,993 IBGE press releases (2004–2026) and five official SIDRA statistical series, running entirely on local models — `bge-m3` for embeddings, `gemma3:4b` for generation, both on Ollama, no API keys. Built to answer one question: when does retrieval actually help, and when is it the wrong instrument?

- **The finding is a negative one, and that is the point.** On a corpus spanning 22 years, the best retrieval mode surfaces a relevant document for 48% of the questions and the generated answer states the right value for 13% — "what was the IPCA in August?" matches twenty Augusts about equally well. The disambiguating information is a *year*, which belongs in a query, not in a similarity score. Routing those questions to the statistical API instead takes value accuracy from 0.13 to 0.97, at a third of the tokens.
- **Retrieval written out rather than imported.** Okapi BM25 and reciprocal rank fusion in readable code. RRF was chosen over a weighted score blend because cosine and BM25 live on incomparable scales: fusing *ranks* needs no normalisation and no weight to tune. LangGraph is used only where the control flow genuinely branches and loops.
- **Results reported against myself.** Hybrid fusion *lowers* ranking quality on this corpus (MRR 0.36 → 0.28) and that row stays in the table. The LLM reranker wins on all three measures at 8× the latency, listed with its parse-failure count so a reranker that silently no-ops cannot look like the row above it.
- **The evaluation set is derived, not hand-written.** Questions come from one template per series, correct values from whatever SIDRA returns, and gold documents from a mechanical, boundary-aware join on product id and release window — so the numbers describe the system rather than the author's memory of the corpus.
- **Deterministic where it counts.** Period resolution returns `None` instead of inventing a period, and every number in an answer must appear in the context it was given before the answer is released — which catches the failure an LLM judge is worst at: a plausible figure recalled from model weights.
- 33 tests with faked embedding and chat backends, so CI needs neither a GPU nor network access.

#### [`ata`](https://github.com/cyroalves/ai_talk) · meeting to document, offline

A tool I built and use daily: a single **Go** binary orchestrating **ffmpeg**, **Whisper** (whisper.cpp) and an **LLM**. It records a meeting, transcribes it entirely on the local machine — the audio never leaves it, an LGPD requirement of the use case — and generates three document types: meeting minutes, technical specification, and requirements gathering.

    record → ffmpeg → whisper.cpp (offline) → LLM (swappable) → document

- **One system prompt per document type, versioned in a file,** iterable without recompiling, plus a domain glossary injected as context so the model can separate signal from noise.
- **Multiple backends behind a single interface:** a local model (Ollama, gemma3) or a headless CLI, swapped by flag without touching the caller.
- **Explicit token budgeting.** It estimates transcript plus prompt against an output reserve sized from the real documents, and fails with a clear error when the input does not fit the context window, instead of letting the model truncate silently.
- **A real failure diagnosed.** On a 58-minute meeting the transcript collapsed into repetition from the halfway point: the decoder was feeding its own error back as context for the next window. Isolating the decoding windows restored full coverage.
- **Build versus buy, decided with numbers.** A study over a measured corpus — 18 meetings, 34 documents, 11.6 hours of audio — with a cost calculator and explicit per-model assumptions. Token cost turned out to be noise; the real decision was audio privacy and engineering hours.

#### [`load-balancer`](https://github.com/cyroalves/load-balancer) · layer-7 HTTP load balancer in Go

No external dependencies. Pluggable strategies — round-robin, least-connections and ip-hash — with active and passive health checking, automatic failover with safe request-body retry, and per-backend metrics.

### Currently Deepening

![Vector databases](https://img.shields.io/badge/-Vector%20databases-05122A?style=flat)&nbsp;
![Cross-encoder reranking](https://img.shields.io/badge/-Cross--encoder%20reranking-05122A?style=flat)&nbsp;
![FastAPI](https://img.shields.io/badge/-FastAPI-05122A?style=flat&logo=fastapi&logoColor=009688)

### Connect with Me

<a href="https://linkedin.com/in/cyro-alves-4292761aa"><img src="https://img.shields.io/badge/-Cyro%20Alves-05122A?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D"/></a>
<a href="mailto:cyro.alveslima@gmail.com"><img src="https://img.shields.io/badge/-cyro.alveslima@gmail.com-05122A?style=flat&logo=gmail&logoColor=EA4335"/></a>

Portuguese (native) · English (advanced)
