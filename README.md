<div align="center">

# Dheeraj Sutram

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Software+Engineer+%7C+Systems+%26+Quant;B.Tech+Information+Technology+%40+VIT+Vellore;Lead+Patent+Co-Inventor+%7C+Neuro-Symbolic+AI;WorldQuant+BRAIN+Gold+Quant)](https://git.io/typing-svg)

<p align="center">
  <a href="https://portfoliowebsite-puce-seven.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Site-111111?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/dheeraj-sutram1"><img src="https://img.shields.io/badge/LinkedIn-dheeraj--sutram1-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/DheerajS-DM"><img src="https://img.shields.io/badge/GitHub-DheerajS--DM-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="mailto:dheeraj22may@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

</div>

---

### About

Undergraduate in Information Technology at VIT Vellore ('28). My work focuses on systems programming, quantitative modeling, and neuro-symbolic verification.

---

### Experience

#### SignSetu — QA / SDET Intern
*May 2026 – September 2026 | Remote*
- Diagnosed uncancelled Promise leaks causing Over-The-Air (OTA) update failures on slow networks; resolved race conditions between the JavaScript thread and native background schedulers.
- Audited entitlement logic and payment migrations; added webhook idempotency guards and schema validation to eliminate duplicate ledger writes.
- Traced circular authentication redirect loops to stale client-side cache state; identified and resolved an email auto-linking issue in auth middleware.
- Restructured MongoDB progress tracking queries to use bounded array patterns, eliminating non-atomic read-modify-write conflicts and preventing document size limit overflow.
- Designed a 2-agent automated end-to-end testing harness using Playwright and Maestro with structured Markdown handoffs for CI/CD pipelines.

#### Infotact Solutions — Full-Stack Web Development Intern
*May 2025 – August 2025 | Remote*
- Built modular front-end components in React with client-side form validation.
- Designed MongoDB schemas and implemented Mongoose models; developed RESTful API routes in Node.js and Express.
- Optimized query performance through compound indexing and response caching.

---

### Patents & Research

#### Assertion-Level Handwritten Proof Verification Engine
*Indian Patent Application No: 202641043577 (Published, VIT / UCSD Ref) | Lead Co-Inventor*
- Neuro-symbolic engine combining DenseNet-121 OCR and ViT-Base layout parsing with formal theorem provers (Z3 SMT solver and Lean 4).
- Verifies step-by-step deductive correctness across handwritten mathematical assertions in real-time, distinguishing proof-by-contradiction hypotheses from arithmetic errors.
- [Repository](https://github.com/DheerajS-DM/Assertion-level-Handwriting-Proof-Verification-Engine)

---

### Selected Projects

#### [BrainQuant Generator](https://github.com/DheerajS-DM/alpha-generator)
*Python, Polars, C/C++, FastAPI*
- Formula discovery, AST transpilation, and vectorized backtesting engine for quantitative trading alphas.
- Translates symbolic formula trees into vectorized Polars expressions (`pl.Expr`) and dynamic C JIT routines.
- Multi-threaded Parquet ingestion pipeline pulling historical OHLCV data for 500+ equities with a flat sub-1.2 GB RSS footprint.

#### [PromptGuard](https://github.com/DheerajS-DM/PromptGuard-Formal-Security-Engine)
*Rust, Tauri v2, React 19*
- Input security harness using deterministic DFA state automata to audit and sanitize prompt inputs before dispatch to LLMs.
- Native cross-platform desktop UI built with Tauri v2, React 19, and Tailwind CSS.

#### [Checkpoint-Based Process Recovery Engine](https://github.com/DheerajS-DM/os-process-checkpoint)
*C, Linux*
- Userspace fault-tolerant execution engine with incremental memory page snapshotting.
- Tracks dirty memory pages by intercepting write faults using `mprotect` and `SIGSEGV` handlers.
- Implemented the Dynamic Priority Circulation Round-Robin (DPC-RR) CPU scheduler with lockless POSIX shared-memory telemetry.

#### [Cloud AI Collaboration Platform](https://github.com/DheerajS-DM/cloud-AI-colllab-platform)
*FastAPI, Kubernetes, Kafka, Next.js, pycrdt*
- Collaborative editing platform using zero-lock CRDT synchronization (`pycrdt`) to merge concurrent edits deterministically.
- Auto-provisions ephemeral vLLM GPU nodes via Karpenter with 30-second post-session termination.
- Distributed telemetry pipeline built with Apache Kafka, streaming server-sent events to Next.js.

#### [Game Latency Router](https://github.com/DheerajS-DM/ML-based-latency-router)
*Python, FastAPI, Scikit-Learn, Node.js, Docker, WebSockets*
- Edge matchmaking proxy dynamically clustering real-time latency vectors to assign players to optimal nodes across AWS, GCP, and Azure.

---

### Technical Skills

- **Languages:** Python, C++, C, Rust, Java, JavaScript, TypeScript, SQL
- **Systems & Cloud:** Linux (cgroups v2), Docker, Kubernetes, Apache Kafka, Redis, PostgreSQL, MongoDB, FastAPI, Node.js
- **Tools & Frameworks:** React, Next.js, Tauri, Git, Playwright, Maestro, Pytest, Z3 SMT Solver, Polars, NumPy, Pandas

---

### Education & Honors

- **B.Tech in Information Technology**, Vellore Institute of Technology (2024 – 2028)
- **WorldQuant BRAIN Gold Certificate** — Ranked top 10,000 out of 170,000+ participants globally
- **McKinsey Forward Program** — Selected participant (2026)
- **State-Level Gold Medallist**, Archery (2024)
