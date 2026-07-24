# Hi, I'm Fahim 

**Full-Stack & AI Engineer** · Founder @ [Innovera IT](https://innoverait.com) · Dhaka, Bangladesh 🇧🇩 · Remote-first

I build **enterprise-grade systems from scratch** — no domain libraries, every hard part hand-implemented and documented. This profile hosts my **28-project portfolio**: distributed systems, ML pipelines, security infrastructure, and Islamic fintech, each with a README that explains the design decisions and the benchmarks behind them.

---

## Rare enterprise systems (start here)

| Project | What it is | The hard part, built from scratch |
|---|---|---|
| [**AuthZ**](https://github.com/mdfahimfaisaltanha/25-authz) | Google Zanzibar-style authorization service | Relationship tuples + recursive graph-walk check engine with userset rewrites — the pattern behind Google Drive & GitHub permissions |
| [**Vault**](https://github.com/mdfahimfaisaltanha/26-vault) | Secrets management platform | Envelope encryption (KEK/DEK, AES-256-GCM) + **Shamir's Secret Sharing over GF(2⁸)** for the seal/unseal ceremony |
| [**DirSync**](https://github.com/mdfahimfaisaltanha/27-dirsync) | SCIM 2.0 identity provisioning server | Full RFC 7643/7644 with zero SCIM libraries; hand-written filter parser (tokenizer + recursive descent → parameterized SQL); Okta & Azure AD PATCH dialects |
| [**ZakatFlow**](https://github.com/mdfahimfaisaltanha/28-zakatflow) | Zakat calculation & distribution platform | Hawl (lunar-year) state machine over a moving nisab threshold; append-only 8-category ledger enforced at the DB layer |

## Infrastructure I built to understand it

[Feature flags & experimentation](https://github.com/mdfahimfaisaltanha/21-flagforge) · [Observability stack](https://github.com/mdfahimfaisaltanha/22-observability) · [Transactional outbox relay](https://github.com/mdfahimfaisaltanha/23-eventmesh) · [Background job platform](https://github.com/mdfahimfaisaltanha/24-jobqueue) · [Distributed task scheduler](https://github.com/mdfahimfaisaltanha/11-task-scheduler)

## AI & ML — with evaluation, not vibes

| Project | Benchmark |
|---|---|
| [**DocMind** — production RAG pipeline](https://github.com/mdfahimfaisaltanha/01-doc-intelligence) | Hybrid retrieval (RRF k=60) + re-ranking, golden eval suite + adversarial refusal probes |
| [**Tripwire** — fraud detection](https://github.com/mdfahimfaisaltanha/14-fraud-detection) | Isolation forest from scratch · precision 87.1% / recall 80.7% / F1 83.8% |
| [**QualityGuard** — manufacturing QC](https://github.com/mdfahimfaisaltanha/19-quality-control) | 50-tree random forest from scratch + SPC charts with Western Electric rules |
| [**StockSense** — demand forecasting](https://github.com/mdfahimfaisaltanha/16-inventory-forecasting) | Holt-Winters from scratch · rolling-origin backtest · fold-4 WAPE 9–12% |
| [**Pulse** — real-time analytics](https://github.com/mdfahimfaisaltanha/04-realtime-analytics) | Exactly-once aggregation · p50 11ms / p95 24ms / p99 41ms @ 100 events/s |

<details>
<summary><b> All 28 projects by category</b></summary>

**Enterprise & security:** AuthZ · Vault · DirSync · ZakatFlow · ClinicOS (RBAC + field-level encryption) · Internal Developer Platform

**Distributed systems & infra:** Pulse · Conveyor · JobQueue · EventMesh · Lumen · FlagForge

**AI / ML:** DocMind · Tripwire · QualityGuard · StockSense · ReviewBot · Support Agent · Multi-Agent Research · Content Moderation · Feedback Analyzer · Recommendations · Voice BI · Video Transcription · ATS Optimizer

**Product platforms:** MeterBill (SaaS billing) · GigLance (marketplace + escrow) · Property Management

</details>

---

## Stack

**Core:** TypeScript · Next.js 14 · Node.js · PostgreSQL (+ pgvector) · Python · Flutter

**Practices:** envelope encryption · Zanzibar-style ReBAC · SCIM 2.0 · idempotent APIs · HMAC webhooks · exactly-once processing · recursive-descent parsers · load testing & backtesting

## Beyond the portfolio

- **Ziviq AI** — multi-tenant white-label AI chatbot SaaS (RAG over pgvector, WhatsApp + Messenger channels, Stripe billing)
- **Motswedi** — two-sided ride-share platform for the Botswana market
- Shariah-compliant products are a specialty — I build systems where the ethics are enforced in the schema, not the marketing

## 📨 Contact

**mdfahimfaisaltanha@gmail.com** · [LinkedIn](https://linkedin.com/in/mdfahimfaisaltanha) · Open to senior remote roles — EdTech, HealthTech, SaaS, Islamic fintech

> *“Indeed, Allah loves that when one of you does a job, he perfects it.”*
