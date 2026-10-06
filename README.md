# Arlen Rios

**CTO, entrepreneur, and hands-on engineer.** 8+ years leading engineering teams and shipping production systems in FinTech and other heavily regulated domains, including credit scoring, lending, payments, KYC/AML and safety intelligence.

Based in Stockholm. Leader *and* IC. I architect, I review, I ship code.

---

## A note on this profile

I've been a **CTO and entrepreneur for 8+ years**, mostly in FinTech and heavily regulated domains. Most of my commits from 2014 to 2024 live on company GitHub accounts at **Kreditz**, **Fakturabörsen**, and other orgs where I led engineering or was principal engineer. The contribution graph here is the public-facing slice of a much longer track record. If you're here to evaluate how I work, the public repos below and the career notes are the better signal, and I'm happy to walk through private work under NDA.

---

## Career

**Serial entrepreneur and CTO.** 8+ years, 4 CTO roles across Swedish FinTech in credit scoring, lending, payments and M&A. Domains where compliance, data integrity, and uptime aren't optional.

- **[Kreditz](https://kreditz.com)**, co-founder and CTO. Built from scratch the tech stack and team behind a ~€7M ARR credit scoring platform used by banks and lenders across the EU. Regulated data flows, KYC/AML, PSD2 integrations, SOC-friendly infra.
- **Fakturabörsen**. Built and led the acquisition of a FinTech.
- **Multiple earlier CTO / principal-engineer roles** across credit scoring, lending, and payments infra.

**How I operate:** I hire and lead engineering teams, set architectural direction, and stay hands-on in the code. I review PRs, write migrations, unblock juniors, and ship features the same week. Most effective when I can both shape the strategy *and* the implementation.

**Tech breadth across roles:** .NET · Go · TypeScript · React · Python · AI/ML · cloud infrastructure · payments · credit scoring · KYC/AML pipelines.

---

## Currently building

In parallel: my own commercial platform (SafePlace), two public open-source projects, and **consulting engagements where I lead AI orchestration and engineering teams**, typically stepping in as fractional CTO / technical lead to set architecture, build the team's AI workflows, and stay hands-on enough to unblock anyone on any layer of the stack.

### 🛡️ SafePlace (private, commercial)

A real-time safety intelligence platform for Sweden.

- Ingests data from 6+ Swedish government APIs (Polisen, SMHI, Trafikverket, Krisinformation, Kolada/BRÅ, SCB) plus 25 news RSS feeds.
- Enriches events with AI-extracted precise locations (Claude Haiku) and matches them to news coverage across 21 regional feeds.
- Produces per-address safety scores with confidence, explainability, and trend data, aggregated across 290 Swedish municipalities.
- Medallion architecture (Bronze → Silver → Gold), immutable raw layers, PostGIS spatial queries, Cloud Run in `europe-north1`.

### 🤖 [dev-agents](https://github.com/Arlencho/dev-agents) (public)

Multi-agent AI orchestration framework. 12 specialist role definitions (backend, frontend, DB, devops, security-reviewer, etc.), wave-based parallel execution, provider-agnostic design. Claude Code today; OpenAI / Cursor / Grok on the roadmap.

**Real use:** I used a custom analytics agent built on this framework to audit a production data platform. First pass scored it **34/100** and identified 10 specific gaps. After three waves of parallel agent work, the re-score was **83.5/100**, catching problems a human review would have missed.

### 📦 [llm-providers](https://github.com/Arlencho/llm-providers) (public)

Small, provider-agnostic Go client: Anthropic Claude + any OpenAI-compatible endpoint (Qwen/DashScope, Azure, Groq, Together, OpenRouter) behind one interface. No SDK bloat, no lock-in, swap providers with one env var. Extracted from SafePlace's ingestion pipeline.

---

## What I reach for

**Backend:** Go · .NET · PostgreSQL · PostGIS · Redis · pgx  
**Frontend:** Next.js · React · TypeScript · MapLibre · Chart.js  
**Infra:** Cloud Run · Docker · GitHub Actions · Cloud SQL · GCP · AWS  
**AI:** Claude · OpenAI · Azure OpenAI · Groq · Together · OpenRouter · Qwen · provider-agnostic interfaces · agentic orchestration  
**Data:** Bronze/Silver/Gold medallion architecture · immutable raw layers · spatial queries

## What I care about

- **Clean data pipelines.** Raw data is never modified. Aggregations are reproducible. Explainability at the gold layer.
- **Shipping production-grade code fast.** Migrations that run both ways. Structured logging. Health checks. Tests.
- **Orchestrating AI agents to do real engineering work**, not just autocomplete. Parallel waves, explicit boundaries, measurable outcomes.
- **Senior-engineer craft.** Root-cause fixes over patches. Simplicity over cleverness. Honesty about trade-offs.

---

## Let's talk

Open to interesting conversations about data platforms, AI tooling, FinTech infrastructure, and shipping.

- **GitHub:** [@Arlencho](https://github.com/Arlencho)
- **LinkedIn:** [arlen-rios](https://www.linkedin.com/in/arlen-rios-43619175/)
