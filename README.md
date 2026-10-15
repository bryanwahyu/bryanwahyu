# Bryan Wahyu

**Backend Engineer · Go · Distributed Systems · Game Server Architecture**

I build backend systems from scratch — game servers, security automation tools, and platforms for social impact. Currently focused on real-time multiplayer infrastructure, AI orchestration, and accessibility tech in Indonesia.

---

### What I Work On

🎮 **Game Backend Engineering** — Custom Go backends for multiplayer games (MMORPG, card game), real-time state sync via Nakama & WebSocket, Redis resilience patterns, IAP validation pipelines

🏗️ **System Architecture** — Domain-Driven Design, Circuit Breaker, SAGA patterns, event-driven microservices, distributed data stores (Cassandra/ScyllaDB, Redis, PostgreSQL)

🔒 **Security Automation** — DevSecOps tooling with Trivy, Nuclei, Gitleaks, ZAP — orchestrated scanning pipelines in Go

♿ **Accessibility Tech** — Building [disabilitasku.id](https://disabilitasku.id), a platform for people with disabilities in Indonesia, powered by AI

---

### Tech Stack

```
Languages    Go · TypeScript/Node.js · Python · PHP
Infra        Docker · AWS (ECR, ECS) · Kubernetes · NATS JetStream · CI/CD (GameCI, GitHub Actions)
Data         PostgreSQL · Redis · Cassandra/ScyllaDB · MySQL
Game         Nakama · WebSocket · Unity (client integration)
Patterns     DDD · CQRS · Circuit Breaker · SAGA · Event Sourcing
```

---

### Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**automaton-sec**](https://github.com/bryanwahyu/automaton-sec) | Security scanning platform: Trivy, Nuclei, Gitleaks, ZAP, SQLMap, plus AI analysis of findings | Go, gRPC, Docker |
| [**mini-siem-api**](https://github.com/bryanwahyu/mini-siem-api) | Threat detection engine for brute force, SQLi and XSS, with automatic firewall blocking | Go |
| [**worker-siem**](https://github.com/bryanwahyu/worker-siem) | Log-shipping worker for mini-siem-api: tails logs, normalizes events, at-least-once delivery through a persistent spool | Go |
| [**emailblast**](https://github.com/bryanwahyu/emailblast) | Resumable bulk email sender with a bounded worker pool, rate limiting, retry and checkpoint resume. Benchmarked at 1M recipients | Go, SMTP, SES |
| [**flip-style-transfer-engine**](https://github.com/bryanwahyu/flip-style-transfer-engine) | Idempotent interbank transfer service: SAGA orchestration, double-entry ledger, transactional outbox, circuit breaker | Go, PostgreSQL, NATS JetStream, Redis |
| [**wealth-advisor**](https://github.com/bryanwahyu/wealth-advisor) | Multi-agent wealth advisor: anomaly detection, prioritized recommendations, human review, long-term memory | Python, SQLite/ScyllaDB |
| [**js-data-entry**](https://github.com/bryanwahyu/js-data-entry) | DDD-architected data ingestion service with clean layer separation | Node.js, Cassandra, Docker |
| [**app_disabilitas_isyarat_ai**](https://github.com/bryanwahyu/app_disabilitas_isyarat_ai) | Sign language recognition (BISINDO/SIBI) for deaf users | Python, MediaPipe, TensorFlow |
| [**app_disabilitas_mata_ai**](https://github.com/bryanwahyu/app_disabilitas_mata_ai) | AI-powered accessibility app for visually impaired users | AI, Mobile |
| [**tap-to-talk**](https://github.com/bryanwahyu/tap-to-talk) | Free, offline-capable tap-to-talk board for non-verbal people | TypeScript |

---

### Background

- Built custom Go game backends from scratch (no frameworks) for an Android MMORPG and a Gwent-style card game
- Migrated production systems from Laravel to Go at scale
- Designed take-home assessments and hiring pipelines for backend engineering roles
- Shipped sprint demos across Nakama game backend, AI orchestration, and WebSocket services

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bryanwahyu&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/bryan-wahyu-krishnaputra/">LinkedIn</a> · 
  <a href="https://disabilitasku.id">disabilitasku.id</a>
</p>
