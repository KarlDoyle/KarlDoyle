# Karl Doyle

**Engineering Leader · Hands-on Product Engineer · Developer Experience · Applied AI**

I build and scale engineering teams, then stay close enough to the work to help ship the systems those teams need. My work sits at the intersection of product engineering, delivery reliability, developer experience and practical AI.

Over 14+ years in technology, including six years in engineering management, I have led product, web and full-stack teams; improved customer-facing performance; simplified cross-functional processes; and built tools that help engineering organisations understand and improve how work flows.

📍 Dublin · UK right to work · Open to hands-on engineering, technical leadership and engineering management roles across Europe and the UK. Also open to consulting and collaboration.  
🔗 [LinkedIn](https://linkedin.com/in/karldoyle-em)

## What I bring

I am most useful where engineering needs to connect clearly to customers, commercial outcomes and sustainable delivery.

- **Built and developed engineering teams:** grew multiple teams from small founding groups into larger, sustainable organisations; hired and onboarded nine engineers in one half-year and developed an engineer into an Engineering Manager.
- **Improved customer-facing performance:** led work on a high-traffic customer journey, reducing p95 latency by roughly 75% and monthly server errors by roughly 90%.
- **Simplified a complex cross-functional process:** reduced engineering effort by 57% and shortened the end-to-end finance process by two days.
- **Increased confidence in revenue-critical systems:** expanded automated testing to 25 business cases covering almost half of monthly revenue, unlocking 80+ testing hours each month.

## How I work

I favour small, testable systems with clear ownership, honest measurement and deliberate trade-offs.

- **Start with the workflow problem,** not the technology.
- **Make the first useful version simple:** local-first where appropriate, few dependencies, clear setup, and observable behaviour.
- **Use metrics to support improvement,** not individual surveillance; team-level signals, transparent proxies and human judgement come first.
- **Use AI as an engineering multiplier:** AI accelerates implementation and exploration, while humans own problem definition, architecture, review, security and release decisions.
- **Make quality visible:** tests, fixtures, CI, reproducible demos and documentation that describes current behaviour and limitations.

## Selected work

### [Baseline — engineering delivery health](https://github.com/KarlDoyle/delivery-health-kit)

A local-first engineering-health toolkit that brings delivery, reliability and effectiveness signals into team-level reports.

It combines GitHub, PagerDuty, Sentry and Prometheus data with deterministic metric calculations, reproducible fixtures and Markdown, Slack or Google Sheets output. It is designed to support improvement conversations—not rank individuals.

**Demonstrates:** engineering metrics, DORA/DX Core 4 thinking, adapter architecture, data provenance, testing, CI/CD and responsible measurement.

### [Quarry — local-first codebase retrieval](https://github.com/KarlDoyle/quarry)

A retrieval engine that indexes a codebase locally, combines semantic and keyword search, and grounds answers in cited source files.

It uses SQLite, SQLite FTS5, `sqlite-vec`, local Transformers.js embeddings and Reciprocal Rank Fusion. Local Ollama is the default analysis provider; hosted models are explicit opt-in rather than the default.

**Demonstrates:** applied AI, hybrid retrieval, grounded generation, local-first privacy, evaluation honesty and developer-tool product design.

### [PR Latency Reporter — review-flow analytics](https://github.com/KarlDoyle/pr-latency-reporter)

A self-hosted Python CLI that turns GitHub pull-request review activity into weekly and monthly reports, backed by local SQLite storage.

It measures business-hours review latency, supports resumable collection, and produces Markdown reports with optional Slack delivery. It is intentionally framed as a process signal rather than an individual-performance rating.

**Demonstrates:** engineering analytics, practical Python engineering, data pipelines, privacy-conscious metrics and operational simplicity.

### [PR Watch — proactive review-queue alerting](https://github.com/KarlDoyle/pr-watch)

A zero-runtime-dependency tool that helps on-call engineers keep team review queues moving.

It tracks business-hours waiting time for requested reviews, posts low-noise Slack digests and breach alerts, resolves the current PagerDuty on-call, and includes an optional event-driven GitHub App path.

**Demonstrates:** operational tooling, alert design, business-hours logic, state management, rate-limit handling, testing and developer-experience thinking.

### [Sprint Report Generator — transparent sprint reporting](https://github.com/KarlDoyle/sprint_report_generator)

A reusable Jira CLI that separates work planned at sprint start from work added mid-sprint.

It uses Jira changelog history to determine sprint membership, produces transparent sprint metrics, supports multi-team rollups, and includes an undeployed Forge panel scaffold.

**Demonstrates:** product abstraction, workflow automation, Jira integration, metric design and clear data-handling boundaries.

### [Councillor Tool — civic product](https://github.com/KarlDoyle/councillor-tool)

A live, privacy-conscious tool that helps Dublin residents find their local councillors and draft a well-framed email.

It has no accounts, backend or tracking; uses official open data; validates links through a scheduled GitHub Action; and keeps last-good data if an upstream source fails.

**Demonstrates:** end-to-end product delivery, public-interest design, open data, maintainability and zero-backend architecture.

## Applied AI approach

I build AI systems that are useful because they are grounded, testable and appropriately constrained.

- **Ground answers in evidence:** retrieval-backed answers and file citations rather than unsupported model output.
- **Keep sensitive work local by default:** local embeddings, local inference and explicit opt-in for hosted providers.
- **Separate deterministic logic from model reasoning:** calculations, rules and reporting remain code; AI assists where judgement and language matter.
- **Evaluate honestly:** distinguish smoke tests from representative benchmarks and state limitations clearly.
- **Keep humans accountable:** AI can draft, search, summarise and review; humans decide what ships.

## Currently exploring

- Local-first AI developer workflows and model-agnostic tooling.
- Retrieval quality, grounded analysis and evaluation for codebases.
- Engineering-health signals that improve team outcomes without becoming surveillance.
- Developer experience, delivery reliability and practical observability.

## Let’s connect

I am open to senior engineering, engineering management and leadership roles, as well as consulting or collaboration on developer tools, engineering effectiveness and applied AI.

🔗 [LinkedIn](https://linkedin.com/in/karldoyle-em)  
🐙 [GitHub](https://github.com/KarlDoyle)

