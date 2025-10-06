# Master-Roadmap

A **single, battle-ready roadmap** you can follow start-to-finish. split it exactly:

* **DSA plan (one place)** — daily/weekly cadence, month-by-month targets.
* **Technology roadmap (sequence-wise, numbered)** — every tech you actually *need*, with **what it is**, **why it matters**, **deliverable(s)** and **practical resources**.
* **Timelines** for every item and exact guidance on when to open-source, apply for internships, and run projects.
* I kept it focused — **core required first**, then **high-value extras** (AI/infra). No fluff.

I also checked current industry signals (popularity and trends) so this list is aligned to what’s being used and hired for today. Key trend summary below (sources included). ([stackoverflow.blog][1])

---

# Executive summary — what to learn (short)

1. **DSA** — do this every day; it’s mandatory for product roles.
2. **Frontend** — HTML, CSS, JavaScript → React → Next.js. (Deliver: polished portfolio + 1 full-stack app)
3. **Backend** — Node.js (JS) → Express / NestJS → databases (Postgres + Mongo) → TypeScript. (Deliver: production-like API)
4. **DevOps basics** — GitHub Actions, Docker, deploy on AWS. (Deliver: CI/CD pipeline + deployed service)
5. **Infra & scale (later)** — Kubernetes, Terraform, monitoring, message queues. (Deliver: microservices on k8s)
6. **AI/ML product skills (edge)** — embeddings, LangChain, vector DBs for RAG. (Deliver: RAG chatbot)
7. **System Design + Core CS** — OS, DB internals, networking, LLD/HLD practice. (Ongoing)
8. **Soft skills** — OSS contributions, internships, mock interviews, resume/blogs.

Trends that justify these priorities: Python & TypeScript growth (AI + safer JS), continued dominance of JS for web, Kubernetes/cloud-native adoption, and fast uptake of vector DBs for RAG apps. ([stackoverflow.blog][1])

---

# Part A — DSA (all-in-one plan)

You said you’ll do DSA “inside-wise” — here’s the compact, no-fluff program.

**Goal:** 12–18 months → be comfortable with medium → hard LeetCode + 500 quality problems over time.

**Daily**

* **60–120 min**: focused practice (one topic per day). Start with arrays/strings → two-pointers → hashmaps → sliding window → stacks/queues → trees → graphs → dp → greedy/heaps → sorting/searching.
* **1 timed LeetCode problem (45–60 min)** 3×/week (simulate interview pressure).

**Weekly**

* **1 mock session** (90–120 min): 2 problems (one medium, one hard) + code review.
* **1 contest** (Codeforces/CodeChef) every 1–2 weeks (optional, huge long-term benefit).

**Monthly targets**

* Month 1–3: Master arrays/strings/hashmaps + 150 easy→medium problems.
* Month 4–9: Trees/graphs + medium problems (200 more).
* Month 10–15: Dynamic programming, advanced graphs, tough mediums/hards (150-200).
* Ongoing: Review patterns, redo mistakes, do timed mocks.

**Resources**

* **GeeksforGeeks** (concepts & your course).
* **LeetCode** (practice + premium patterns if you can).
* **NeetCode / Blind 75** (pattern lists).
* **System design** (see below) — starts after you have backend basics.

**Deliverables (DSA)**

* Completed folders on GitHub with solved problems (well-commented).
* 3 timed mock recordings / transcripts showing improvement.

---

# Part B — Technology roadmap (numbered, sequence-wise)

Start date assumption: **Nov 15, 2025** (matches your plan). For each item: **what**, **why**, **deliverable**, **time estimate**, **resources**.

> NOTE: I mark **(Core)** for must-have before placements, **(High-value)** for important extras, **(Optional/Cert)** for optional but useful.

---

## 1) HTML — (Core) — **2 weeks** 🗸

* **What:** Document structure & semantics (headings, forms, accessibility).
* **Why:** Browser reads HTML first; semantic HTML = better SEO + accessibility + interview basics.
* **Deliverable:** Portfolio pages with semantic structure + an accessible form.
* **Resources:** MDN HTML docs — [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

---

## 2) CSS (Flexbox & Grid, responsive) — (Core) — **2–3 weeks**  🗸

* **What:** Styling & layout (responsive mobile-first design).
* **Why:** Good UI = recruiter’s first impression. Grid/Flex for layouts.
* **Deliverable:** Responsive portfolio (mobile-first), CSS variables, accessible color contrast.
* **Resources:** MDN CSS — [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## 3) JavaScript (ES6+, async) — (Core) — **6–8 weeks**

* **What:** Language of web — closures, event loop, promises, async/await, modules.
* **Why:** Drives both frontend and Node backend. A deep JS understanding prevents bugs later.
* **Deliverable:** 5 micro-tasks (debounce, promise→async refactor, DOM widget, event-loop demo, module bundling).
* **Resources:** MDN JS Guide — [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

---

## 4) Git & GitHub (PR workflow) — (Core) — **1 week**

* **What:** Version control, branches, PRs, GitHub Actions basics.
* **Why:** Required for collaborations, OSS, internships.
* **Deliverable:** Repo with feature branch → PR → merged; basic CI trigger.
* **Resources:** GitHub Learning Lab — [https://github.com/skills/introduction-to-github](https://github.com/skills/introduction-to-github)

---

## 5) Command Line & Linux basics — (Core) — **1–2 weeks**

* **What:** Shell, process management, SSH, basic package management.
* **Why:** Deployments, remote servers, docker, kubectl all assume comfort with CLI.
* **Deliverable:** SSH into an EC2 instance, run your app.

---

## 6) Browser DevTools & Debugging — (Core) — **1 week**

* **What:** DOM inspection, network tab, performance, profiling.
* **Why:** Speed up debugging and front-end performance tuning.
* **Deliverable:** Fix a performance issue (e.g., long paint time) and document root cause.

---

## 7) React (Functional components + hooks) — (Core) — **6–8 weeks**

* **What:** Component-based UI, hooks, state management basics.
* **Why:** Most frontend roles expect React skills; large ecosystem.
* **Deliverable:** React SPA of one project (connect to your API).
* **Resources:** Your Udemy React courses (Maximilian/ZTM), official React docs.

---

## 8) Next.js (Routing, SSR/SSG) — (Core) — **4 weeks**

* **What:** Framework for production React apps — file-based routing, SSR, server functions.
* **Why:** Production-ready frontends, good for SEO and performance. Many product roles prefer Next.js.
* **Deliverable:** Deploy portfolio or project on Vercel/Next with SSR pages.
* **Resources:** Next.js docs, your Next.js Udemy course.

---

## 9) Node.js (runtime) — (Core) — **4–6 weeks**

* **What:** JS runtime outside browser — async I/O, event loop.
* **Why:** Backend for full-stack and many microservices. Learn request lifecycle, streams, performance pitfalls.
* **Deliverable:** Basic REST API (users/products, auth).
* **Resources:** ZTM Node course (you own), Jonas, Node.js docs.

---

## 10) Express.js / Backend patterns — (Core) — **3–4 weeks**

* **What:** Routing, middleware, validation, error handling.
* **Why:** Build maintainable APIs; standard in many codebases.
* **Deliverable:** Structured API with validation, middleware, logging.

---

## 11) Databases — Postgres (SQL) — (Core) — **3–4 weeks**

* **What:** Relational DB – transactions, joins, indexing.
* **Why:** For financial/transactional data, ACID guarantees. Most serious systems use Postgres.
* **Deliverable:** Orders/payments microservice with migrations + sample queries.
* **Resources:** Postgres docs, Prisma (below).

---

## 12) Databases — MongoDB (NoSQL) — (Core) — **2–3 weeks**

* **What:** Document DB (JSON-like). Flexible schema for catalogs, product data.
* **Why:** Fast prototyping & commonly used with Node.
* **Deliverable:** Product catalog with indexes & aggregation pipeline.
* **Resources:** Maximilian MongoDB course, MongoDB docs.

---

## 13) ORM / DB tools — Prisma (for Postgres) & Mongoose (Mongo) — (2 weeks)

* **What:** Type-safe DB client (Prisma) and Mongo ODM (Mongoose).
* **Why:** Faster dev & fewer SQL mistakes; Prisma integrates well with TypeScript.
* **Deliverable:** Prisma schema + migrations + queries.

---

## 14) TypeScript (strict) — (Core) — **4–6 weeks**

* **What:** Typed superset of JS, interfaces, generics, strict mode.
* **Why:** Type-safety at scale, required by many companies. **Important rule:** learn Node in JS first, then convert to TS.
* **Deliverable:** Convert one Node project to TS strict (no `any`).
* **Resources:** TypeScript handbook (tsconfig strict docs).

---

## 15) Testing (Jest + Supertest + End-to-End) — (Core) — **3–4 weeks**

* **What:** Unit tests, integration tests, e2e (Playwright/Cypress).
* **Why:** Production code must be testable; interviews look at testing knowledge.
* **Deliverable:** CI running tests with coverage thresholds.

---

## 16) Docker & Docker Compose — (Core) — **2–3 weeks**

* **What:** Containerize apps and local multi-service stacks.
* **Why:** Makes deployments predictable; industry standard.
* **Deliverable:** Multi-stage Dockerfile + docker-compose for API + Postgres + Redis.

---

## 17) Redis (cache, sessions) & Background Jobs (BullMQ) — (High-value) — **2–3 weeks**

* **What:** In-memory store + job queue for async jobs.
* **Why:** Improve latency, scale background processing (emails, image processing).
* **Deliverable:** Implement caching & a job queue for email sending.

---

## 18) CI/CD — GitHub Actions (or GitLab CI) — (Core) — **2 weeks**

* **What:** Automate tests, builds, deployments.
* **Why:** Real-world engineering expects automated pipelines.
* **Deliverable:** Pipeline: tests → build → push Docker image → deploy to staging.

---

## 19) Cloud basics — AWS Free Tier (S3, EC2, RDS) — (Core) — **4 weeks**

* **What:** Storage, compute, managed DBs.
* **Why:** Deploy production apps and understand infra bills & IAM.
* **Deliverable:** Deploy a small service on EC2 / use S3 for file storage.

---

## 20) System Design (LLD & HLD) — (Core; ongoing) — **6–12 months ongoing**

* **What:** Low-level: class designs; High-level: architecture for scale (caching, DB sharding, load balancing).
* **Why:** Essential in senior interviews for 20+ LPA roles.
* **Deliverable:** Design docs for URL shortener, chat system, e-commerce architecture.
* **Resources:** Gaurav Sen (YouTube), *Designing Data-Intensive Applications*.

---

## 21) Kubernetes (k8s) — (High-value) — **6–8 weeks**

* **What:** Container orchestration (pods, services, ingress, HPA).
* **Why:** Required for infra-heavy roles and real microservice deployments.
* **Deliverable:** Run your microservices on minikube + deploy to EKS/GKE.
* **Resources:** Kubernetes docs, CNCF materials. (Cloud Native adoption is high.) ([CNCF][2])

---

## 22) Terraform (IaC) — (High-value) — **2–3 weeks**

* **What:** Infrastructure as code for reproducible infra.
* **Why:** Automates infra provisioning (S3, RDS, clusters).
* **Deliverable:** Terraform to provision S3 + RDS + EKS.

---

## 23) Observability & Monitoring — (High-value) — **3–4 weeks**

* **What:** Prometheus (metrics) + Grafana (dashboards) + OpenTelemetry/Jaeger (tracing).
* **Why:** For production reliability and debugging latency issues.
* **Deliverable:** p50/p95 metrics dashboard + traces for slow endpoints.

---

## 24) Message Queues / Streaming — Kafka or RabbitMQ — (High-value) — **3–4 weeks**

* **What:** Decouple systems using async events.
* **Why:** Real distributed systems use event-driven flow.
* **Deliverable:** Order placed → event → analytics consumer pipeline running.

---

## 25) Vector Databases & RAG toolchain (LangChain, pgvector, Pinecone) — (High-value for AI product roles) — **4–8 weeks**

* **What:** Vector DBs store embeddings for semantic search; LangChain orchestrates LLM chains.
* **Why:** RAG chatbots and LLM products require vector search; adoption is growing fast. ([IBM][3])
* **Deliverable:** RAG demo: embeddings pipeline → vector store → retrieval + LLM answer.
* **Resources:** LangChain docs, pgvector docs, Pinecone docs.

---

## 26) Security Basics (OWASP Top 10, JWT, auth best practices) — (Core) — **2 weeks**

* **What:** XSS, CSRF, SQLi, secure auth flows.
* **Why:** Everyone must know secure-by-default patterns.
* **Deliverable:** Hardened API with input validation, rate-limiting, helmet, secure cookies.

---

## 27) Performance & Costs — (Operational) — **ongoing**

* **What:** Profiling, caching layers, infra cost awareness.
* **Why:** Interviewers like numbers (p95 latency, cost per request).
* **Deliverable:** Documentation with RPS & cost for your flagship project.

---

## 28) Soft skills / Career (ongoing)

* **What:** Resume, LinkedIn, technical blog posts (3), targeted applications, alumni networking.
* **When:** Start in parallel from Month 3; intensify before placement season.
* **Deliverable:** 3 technical blog posts + polished resume + 10 mock interviews.

---

# Prioritization: what to learn first (short)

1. HTML → CSS → JS (ES6) → Git → React → Node (JS) → Postgres/Mongo → TypeScript → Docker → Tests → Deploy to AWS. (All **Core**.)
2. After core: Kubernetes, Terraform, Redis, Kafka, Observability. (Add **High-value** afterward.)
3. AI features (LangChain, vector DBs) — start after you can deploy and run infra reliably (useful as differentiator for 20+ LPA).

---

# Timeline (high-level, start Nov 15, 2025)

* **Nov 15 → Feb 2026 (3.5 months):** Foundations — HTML/CSS/JS/React basics/Git + DSA 60–90 min/day. Portfolio + 1 full-stack mini app.
* **Mar → Jun 2026 (4 months):** Backend fundamentals — Node (JS), Express, MongoDB, Postgres+Prisma; start internships applications (Feb–Mar window). Begin OSS contributions mid-2026.
* **Jul → Dec 2026 (6 months):** Productionize — TypeScript conversion, testing, Docker, Redis, CI/CD, AWS deploy. Start hackathons Apr 2026 onward.
* **Jan → Jun 2027 (6 months):** Infra & scale — k8s, Terraform, observability, message queues.
* **Jul 2027 → Jun 2028 (12 months):** Flagship projects (E-Commerce microservices + RAG chatbot), heavy system design, mock interviews, targeted job applications.
* **Jul → Nov 2028:** Final hiring push / placement season.

(Adjust pace if you’re faster/slower — but keep DSA ongoing.)

---

# When to open-source, internships, hackathons (exact)

* **Start OSS:** **Mid-2026** (after Node + Git foundations). Begin with docs/tests PRs → feature PRs by Q4 2026.
* **Apply internships:** **Start Feb–Mar 2026** for Summer 2026. Keep applying rolling through 2027.
* **Hackathons:** **From Apr 2026** once you have 1 full-stack app; aim for 3+ events in 2026 (good wins + network).
* **Flagship projects for resume:** Start building end of **2026** and through **2027**.

---

# Deliverable list you must show publicly (minimum)

1. **Portfolio site** (live) — home, projects, contact.
2. **GitHub** with 3 main repos: front-end app, backend API, infrastructure (Docker + Terraform).
3. **Deployed staging URL** (AWS/Vercel) for at least one project.
4. **TypeScript-converted API** in strict mode.
5. **CI** that runs tests on PRs.
6. **Microservices on k8s** (demo or local + doc).
7. **RAG demo** (hosted or video demo).
8. **3 technical blog posts** describing architecture + decisions + metrics.

---

# Practical study resources (quick list by tech)

* **HTML/CSS/JS:** MDN Web Docs.
* **React/Next.js:** Official docs + your Udemy React & Next.js courses.
* **Node/Express:** ZTM Node course, Jonas Schmedtmann.
* **MongoDB:** Maximilian course; Mongo docs.
* **Postgres/Prisma:** Prisma docs + Postgres docs.
* **TypeScript:** TypeScript handbook + strict tsconfig guides.
* **Docker:** Docker docs (multi-stage builds).
* **Kubernetes:** k8s docs + minikube tutorials.
* **CI/CD:** GitHub Actions docs.
* **DSA:** GeeksforGeeks (course you’re on) + LeetCode + NeetCode.
* **System Design:** Gaurav Sen (YouTube) + *Designing Data-Intensive Applications*.
* **LangChain / Vector DB:** LangChain docs + pgvector / Pinecone docs.
  (If you want, I can paste a one-line link set per tech.)

---

# Final blunt advice — what I’ll not sugarcoat

* **Do DSA daily**. Great projects + zero DSA = no invite to most product interviews.
* **Don’t learn TypeScript first.** Learn Node in JS → convert to TS. You’ve already got that in your earlier plan — keep it.
* **Don’t spread yourself too thin early.** Focus: Frontend + Backend + 1 deployed project. Add infra after you can deploy and maintain a service.
* **Use internships & OSS as proof.** Real experience beats certificates. Apply early and often.

---

[1]: https://stackoverflow.blog/2025/01/01/developers-want-more-more-more-the-2024-results-from-stack-overflow-s-annual-developer-survey/?utm_source=chatgpt.com "the 2024 results from Stack Overflow's Annual Developer ..."
[2]: https://www.cncf.io/wp-content/uploads/2025/04/cncf_annual_survey24_031225a.pdf?utm_source=chatgpt.com "Cloud Native 2024"
[3]: https://www.ibm.com/think/topics/vector-database?utm_source=chatgpt.com "What Is A Vector Database?"
