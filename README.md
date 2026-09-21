# Cyro Alves

**Software Engineer** · full-stack product, data platform, and applied LLMs.
Espírito Santo, Brazil · open to remote

### About Me

Software engineer with around six years of experience in Python and TypeScript, after a Physics degree at UFES. For the last four I have been at **Play9**, a SaaS platform in the creator economy: campaigns, billing and media data. I was part of the team behind **Playnest**, its app with roughly 100k users, working end to end there: data model and API, interface, third-party integrations, and the pipelines behind them. These days I work directly with clients, turning their demands into product on our internal platform.

**Most of my work lives in private repositories,** so the repository list here is much shorter than the work behind it. Most of it is the data platform: Airflow and dbt on BigQuery over GCP, layered from landing through trusted and refined to the warehouse, loaded by idempotent `MERGE` upserts with SCD Type 2 history. Backfills and migrations run under a protocol there: a dry run, a scoped blast radius, before and after snapshots, and a second run to prove idempotency. The integrations are written for the other side being down, with OAuth 1.0 TBA and 2.0, exponential backoff, and a transactional ledger for idempotent synchronization with asynchronous retry.

Not every problem there wanted a model. For a curation PDF parser I measured OCR against an LLM and shipped deterministic extraction instead, on data-protection and cost grounds. The agents I do run are versioned like code: skills, rules and subagents in the production repository, with PRDs and architecture documents as the input to the work.

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=python&logoColor=3776AB)&nbsp;
![TypeScript](https://img.shields.io/badge/-TypeScript-05122A?style=flat&logo=typescript&logoColor=3178C6)&nbsp;
![SQL](https://img.shields.io/badge/-SQL-05122A?style=flat&logo=postgresql&logoColor=4479A1)&nbsp;
![Go](https://img.shields.io/badge/-Go-05122A?style=flat&logo=go&logoColor=00ADD8)&nbsp;
![Java](https://img.shields.io/badge/-Java-05122A?style=flat&logo=openjdk&logoColor=white)

**Back-end and APIs**

![Node.js](https://img.shields.io/badge/-Node.js-05122A?style=flat&logo=nodedotjs&logoColor=5FA04E)&nbsp;
![GraphQL](https://img.shields.io/badge/-GraphQL-05122A?style=flat&logo=graphql&logoColor=E10098)&nbsp;
![Apollo Server](https://img.shields.io/badge/-Apollo%20Server-05122A?style=flat&logo=apollographql&logoColor=white)&nbsp;
![TypeORM](https://img.shields.io/badge/-TypeORM-05122A?style=flat&logo=typeorm&logoColor=FE0803)&nbsp;
![Hibernate](https://img.shields.io/badge/-Hibernate-05122A?style=flat&logo=hibernate&logoColor=59666C)&nbsp;
![Express](https://img.shields.io/badge/-Express-05122A?style=flat&logo=express&logoColor=white)&nbsp;
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-05122A?style=flat&logo=springboot&logoColor=6DB33F)&nbsp;
![Flask](https://img.shields.io/badge/-Flask-05122A?style=flat&logo=flask&logoColor=white)&nbsp;
![Redis](https://img.shields.io/badge/-Redis-05122A?style=flat&logo=redis&logoColor=FF4438)

**Front-end**

![React](https://img.shields.io/badge/-React-05122A?style=flat&logo=react&logoColor=61DAFB)&nbsp;
![Next.js](https://img.shields.io/badge/-Next.js-05122A?style=flat&logo=nextdotjs&logoColor=white)&nbsp;
![styled-components](https://img.shields.io/badge/-styled--components-05122A?style=flat&logo=styledcomponents&logoColor=DB7093)&nbsp;
![React Query](https://img.shields.io/badge/-React%20Query-05122A?style=flat&logo=reactquery&logoColor=FF4154)&nbsp;
![Zod](https://img.shields.io/badge/-Zod-05122A?style=flat&logo=zod&logoColor=3E67B1)&nbsp;
![Radix UI](https://img.shields.io/badge/-Radix%20UI-05122A?style=flat&logo=radixui&logoColor=white)

**Messaging and streaming**

![Apache Kafka](https://img.shields.io/badge/-Apache%20Kafka-05122A?style=flat&logo=apachekafka&logoColor=white)&nbsp;
![Pub/Sub](https://img.shields.io/badge/-Pub%2FSub-05122A?style=flat&logo=googlecloud&logoColor=4285F4)

**Data and warehouse**

![BigQuery](https://img.shields.io/badge/-BigQuery-05122A?style=flat&logo=googlebigquery&logoColor=669DF6)&nbsp;
![dbt](https://img.shields.io/badge/-dbt-05122A?style=flat&logoColor=FF694B)&nbsp;
![Apache Airflow](https://img.shields.io/badge/-Apache%20Airflow-05122A?style=flat&logo=apacheairflow&logoColor=017CEE)&nbsp;
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-05122A?style=flat&logo=postgresql&logoColor=4169E1)&nbsp;
![Flyway](https://img.shields.io/badge/-Flyway-05122A?style=flat&logo=flyway&logoColor=CC0200)&nbsp;
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
![Testcontainers](https://img.shields.io/badge/-Testcontainers-05122A?style=flat&logo=testcontainers&logoColor=291A3D)&nbsp;
![Ruff](https://img.shields.io/badge/-Ruff-05122A?style=flat&logo=ruff&logoColor=D7FF64)&nbsp;
![ESLint](https://img.shields.io/badge/-ESLint-05122A?style=flat&logo=eslint&logoColor=4B32C3)

### Projects

#### [`farmacia-cidada`](https://github.com/cyroalves/farmacia-cidada) · hexagonal dispensing system for a municipal public pharmacy

*Most of the wait at the counter is separation work happening while you stand in front of the attendant. Move it off that moment and the queue stops being a queue.*

Written from my own experience as a patient at the Farmácia Cidadã in my city: you leave home without knowing whether the medicine is there, and the hours in line are prescription checking and shelf picking done with you standing there. Here the citizen checks stock without logging in, requests through the app authenticated with gov.br, the stock is reserved at that instant, the pharmacy separates asynchronously, and the person only travels once notified — then presents a pickup code. Go 1.23, Postgres, Kafka on KRaft, GORM, four direct dependencies.

- **Reserving is not dispensing, and the stock row carries both numbers.** `Quantidade` is what is physically on the shelf, `Reservado` is what already has an owner, and every delivery decision reads the difference. A batch with 100 units and 100 reserved has stock and zero availability. The public lookup returns that difference too — publishing the physical number would send someone across town for a box that is already spoken for, which is the wasted trip the project exists to prevent.
- **FEFO, not FIFO.** A batch received yesterday can expire before one received last year, because expiry follows manufacturing and not delivery. Dispatching by arrival order is how public money rots on a shelf. The allocation is a pure function: it decides which batches to draw from and mutates nothing, so the rule is tested without infrastructure and the debit stays inside the transaction.
- **Three barriers against overselling, because the first two only cover code that goes through them.** The entity refuses to go negative, `SELECT ... FOR UPDATE` serialises concurrent transactions, and a `CHECK` constraint catches the manual `UPDATE` and the path nobody thought of. The `ORDER BY` does double duty — it is the FEFO order *and* the lock order, and the deterministic tiebreak by id is what stops two transactions from taking the same rows in opposite sequences. An integration test runs 20 simultaneous dispensations against 10 units and asserts exactly 10 deliveries and a final balance of zero.
- **The dual-write has no ordering that works, so the event is written in the same transaction as the fact.** Commit then publish loses the event when the process dies between the two; publish then commit announces a dispensation that was rolled back. The event goes to an outbox table inside the transaction and a separate relay publishes it, `FOR UPDATE SKIP LOCKED` so replicas do not collide. Kafka can be down for an hour while dispensations keep happening.
- **That buys at-least-once, and the consumers pay for it in two different currencies.** One inserts the event id into a dedup table in the same transaction as its state change, so a redelivery violates the primary key and rolls the whole thing back — the constraint is the guarantee, not the `if` in front of it. The other needs no table at all: the request's state machine already refuses `pronta → pronta`, and when the domain answers the question, the table is ceremony.
- **The dependency rule is enforced, not promised.** GORM lives only in the persistence adapter, behind explicit mappers, and the transaction travels in the `context` so no port signature ever mentions `*gorm.DB`. A test parses the imports of the domain and application layers and fails the build on `gorm.io`, `net/http` or `database/sql`. A README can claim a hexagon; a test makes it true.
- **A real failure diagnosed, of a kind Go compiles in silence.** A query constructor took a repository as a parameter and never assigned it to the struct — a missing field in a composite literal is not an error — so it surfaced as a nil-pointer panic on the first request to that endpoint. The fix was one line; the regression test now walks every query through its own port, so the next forgotten dependency fails in CI instead of in a handler.
- **gov.br as the citizen's door, honestly scoped.** Real integration requires official credentialing a personal project cannot obtain, so the adapter is a generic OIDC client — endpoints and the CPF claim come from configuration, never hardcoded — shipped against a local simulated provider so the flow actually runs end to end: Authorization Code with PKCE, and RS256 verification against the JWKS using nothing but the standard library, checking `alg`, `iss`, `aud`, `exp` and `nonce` before a single claim is trusted.
- 51 tests. 43 run against in-memory adapters in milliseconds with no Docker, which is only possible because the use cases depend on interfaces; 8 sit behind an `integration` tag for what a map cannot honestly imitate — row locks, check constraints, real rollback. SQLite was deliberately not used: it has no `SELECT ... FOR UPDATE`, so those tests would pass while exercising nothing.

#### [`java-spring-kafka`](https://github.com/cyroalves/java-spring-kafka) · event-driven order pipeline on Spring Boot 4, Kafka 4 and Postgres

*Every guarantee is demonstrable by one command and covered by a test against a real broker and a real database.*

An HTTP API publishes orders to `orders.v1`. Four consumer groups read from the topics: one validates, one issues invoices to `invoices.v1` under a transaction, and two project the same events into Postgres, with a dead letter queue behind all of them. Java 21, Kafka 4 on KRaft, Postgres 17, JPA and Hibernate, Flyway, Testcontainers.

- **Ordering where it matters.** The customer id is the record key, so every order from one customer lands on one partition and keeps its sequence. `make burst` publishes nine orders across three customers and shows the split.
- **Retry that distinguishes causes.** Exponential backoff at 500ms, 1s, 2s, 4s for transient failures. A permanent data defect skips the backoff and goes straight to the dead letter queue, because retrying a malformed order changes nothing. `make flaky` recovers on the third attempt, `make boom` exhausts the backoff, `make invalid` never retries.
- **Backoff kept deliberately short.** While a record backs off, the container pauses the consumer and seeks back to the failed offset, so the whole partition stalls. A generous backoff on a Kafka consumer is downtime dressed as resilience.
- **Read-process-write transactions.** A separate transactional producer with a stable `transactional.id`, so a restart fences the zombie instance instead of letting it commit behind its replacement. `setCommitRecovered(true)` commits the dead letter publish and the offset advance together, which is what stops a poison record from reappearing on every restart. `make peek` compares `read_committed` against `read_uncommitted` on the same topic.
- **That transaction also leaks, and the read model is what made it visible.** An aborted invoice run writes five invoices to the log across its five attempts. Four stay invisible under `read_committed` — and the fifth commits alongside the dead letter, because the recovery transaction carries whatever the listener produced on that last pass. One row reaches the database. The first version of the test asserted zero and failed; it now pins the real number. A side effect that must not survive a failure belongs after the part that fails, not before it.
- **The dead letter destination is declared, not inferred.** The framework default suffix changed between spring-kafka 3.x and 4.x, and an implicit destination only reveals itself as wrong in production, as a producer stuck on `UNKNOWN_TOPIC_OR_PARTITION`.
- **A read model, and the database is not the source of truth.** Two consumer groups of their own project the events into `orders` and `invoices`, so the system can answer *this order* and *how much has this customer had approved* — questions a partitioned log answers by replaying a partition and SQL answers with an indexed `sum`. The tables are disposable: drop them, reset that group's offset, and the projection rebuilds from the topic. Nothing is written to the database on the HTTP path; the `POST` still publishes and returns 202, so a `GET` right after it can legitimately return 404.
- **Idempotency belongs to the constraint, not to the `if` in front of it.** A commit in Postgres and a commit of the Kafka offset are two transactions and nothing joins them, so a crash between them redelivers the message. The `exists` check before the insert is an optimisation; the `UNIQUE` on the event's natural key is the guarantee, and the violation is handled as *already processed* rather than as an error. There is no foreign key between invoices and orders, either: the two groups are independent, so an invoice can be written before the order that produced it, and a constraint there would turn an ordinary race into a failure. Schema changes go through Flyway with `ddl-auto: validate`, never through Hibernate.

#### [`ask-dont-search`](https://github.com/cyroalves/ask-dont-search) · hybrid retrieval, tool calling and a corrective agent

*When the answer is a number in a table, don't search text for it. Ask the source.*

Question answering over 5,993 IBGE press releases (2004 to 2026) and five official SIDRA statistical series, running entirely on local models: `bge-m3` for embeddings, `gemma3:4b` for generation, both on Ollama, no API keys. Built to answer one question, which is when retrieval actually helps and when it is the wrong instrument.

- **The finding is a negative one, and that is the point.** On a corpus spanning 22 years, the best retrieval mode surfaces a relevant document for 48% of the questions and the generated answer states the right value for 13%. "What was the IPCA in August?" matches twenty Augusts about equally well. The disambiguating information is a *year*, which belongs in a query, not in a similarity score. Routing those questions to the statistical API instead takes value accuracy from 0.13 to 0.97, at a third of the tokens.
- **Retrieval written out rather than imported.** Okapi BM25 and reciprocal rank fusion in readable code. RRF was chosen over a weighted score blend because cosine and BM25 live on incomparable scales: fusing *ranks* needs no normalisation and no weight to tune. LangGraph is used only where the control flow genuinely branches and loops.
- **Results reported against myself.** Hybrid fusion *lowers* ranking quality on this corpus (MRR 0.36 to 0.28) and that row stays in the table. The LLM reranker wins on all three measures at 8x the latency, listed with its parse-failure count so a reranker that silently no-ops cannot look like the row above it.
- **The evaluation set is derived, not hand-written.** Questions come from one template per series, correct values from whatever SIDRA returns, and gold documents from a mechanical, boundary-aware join on product id and release window, so the numbers describe the system rather than the author's memory of the corpus.
- **Deterministic where it counts.** Period resolution returns `None` instead of inventing a period, and every number in an answer must appear in the context it was given before the answer is released. That catches the failure an LLM judge is worst at: a plausible figure recalled from model weights.
- 33 tests with faked embedding and chat backends, so CI needs neither a GPU nor network access.

#### [`ata`](https://github.com/cyroalves/ai_talk) · meeting to document, offline

A tool I built and use daily: a single **Go** binary orchestrating **ffmpeg**, **Whisper** (whisper.cpp) and an **LLM**. It records a meeting, transcribes it entirely on the local machine, and generates three document types: meeting minutes, technical specification, and requirements gathering. The audio never leaves the machine, which was the LGPD requirement of the use case.

    record → ffmpeg → whisper.cpp (offline) → LLM (swappable) → document

- **One system prompt per document type, versioned in a file,** iterable without recompiling, plus a domain glossary injected as context so the model can separate signal from noise.
- **Multiple backends behind a single interface:** a local model (Ollama, gemma3) or a headless CLI, swapped by flag without touching the caller.
- **Explicit token budgeting.** It estimates transcript plus prompt against an output reserve sized from the real documents, and fails with a clear error when the input does not fit the context window, instead of letting the model truncate silently.
- **A real failure diagnosed.** On a 58-minute meeting the transcript collapsed into repetition from the halfway point: the decoder was feeding its own error back as context for the next window. Isolating the decoding windows restored full coverage.
- **Build versus buy, decided with numbers.** A study over a measured corpus of 18 meetings, 34 documents and 11.6 hours of audio, with a cost calculator and explicit per-model assumptions. Token cost turned out to be noise. The real decision was audio privacy and engineering hours.

#### [`load-balancer`](https://github.com/cyroalves/load-balancer) · layer-7 HTTP load balancer in Go

No external dependencies. Pluggable strategies, round-robin, least-connections and ip-hash, with active and passive health checking, automatic failover with safe request-body retry, and per-backend metrics.

### Connect with Me

<a href="https://linkedin.com/in/cyro-alves-4292761aa"><img src="https://img.shields.io/badge/-Cyro%20Alves-05122A?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjUgMHoiLz48L3N2Zz4%3D"/></a>
<a href="mailto:cyro.alveslima@gmail.com"><img src="https://img.shields.io/badge/-cyro.alveslima@gmail.com-05122A?style=flat&logo=gmail&logoColor=EA4335"/></a>

Portuguese (native) · English (advanced)
