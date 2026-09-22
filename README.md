# Hi, I'm Ademola Adedoyin 👋

**Software Engineer · Backend & Distributed Systems · Fintech**

I build APIs and applications with a focus on data integrity, asynchronous processing, and recovery when things fail. My projects explore the details behind reliable systems: tenant isolation, balanced ledgers, idempotent requests, durable queues, and observable delivery workflows.

[LinkedIn](https://www.linkedin.com/in/sina-ademola-38635a162/) · [Explore my repositories](https://github.com/AdemolaAdedoyin?tab=repositories)

## Selected engineering projects

### [ExpenseFlow](https://github.com/AdemolaAdedoyin/expenseflow)
**Multi-tenant expense management and approvals**

Policy-driven Employee → Manager → Finance workflows, capability-based authorization, PostgreSQL row-level security, OIDC SSO, private receipt storage, and asynchronous notifications. Idempotency keys and optimistic locking protect state-changing operations.

`NestJS` · `TypeScript` · `React` · `PostgreSQL` · `Redis / BullMQ` · `Amazon S3 / SES`

### [Fintech Transaction Platform](https://github.com/AdemolaAdedoyin/fintech)
**Wallets, transfers, and double-entry ledger accounting**

Immutable ledger postings, integer money amounts, database-enforced balancing, concurrent transfer protection, and compensating reversals. Includes a transactional outbox, signed webhooks, mock funding, and an opt-in Paystack hosted-checkout adapter.

`NestJS` · `TypeScript` · `PostgreSQL` · `Prisma` · `Redis / BullMQ`

### [Webhook Relay](https://github.com/AdemolaAdedoyin/webhook-relay)
**Signed event delivery with a React operations dashboard**

Durable event fan-out, retries, crash recovery, per-subscription throughput controls, and bounded manual replay. Scoped API keys, encrypted signing secrets, destination validation, and retained audit history support the delivery lifecycle.

`Node.js / Express` · `TypeScript` · `React` · `PostgreSQL` · `Redis / BullMQ`

### [Taskflow](https://github.com/AdemolaAdedoyin/taskflow)
**Durable job scheduling and queue execution**

One-off and recurring jobs with PostgreSQL as the source of truth and Redis as a rebuildable execution layer. Includes execution leases, stale-worker recovery, distributed handler limits, signed completion callbacks, and an OpenAPI/Swagger interface.

`Node.js / Express` · `TypeScript` · `PostgreSQL` · `Redis / BullMQ` · `Prometheus metrics`

### [LLM Gateway](https://github.com/AdemolaAdedoyin/llm-gateway)
**A unified API for multiple model providers**

Logical model routing, retryable-failure fallback, response caching, per-key rate limits, and usage tracking behind a shared provider interface. Cost estimates currently use illustrative pricing; this is an infrastructure project, not a billing service.

`Node.js / Express` · `TypeScript` · `PostgreSQL` · `Redis`

## Interactive projects

| Project | What to explore | Demo |
| --- | --- | --- |
| [SupportDesk](https://github.com/AdemolaAdedoyin/CS-Messaging-Web-App) | Vue 3 support inbox, customer portal, priority/status workflows, and a Firebase-backed realtime mode alongside a zero-setup demo. | [Open SupportDesk](https://cs-messaging-web-app-tan.vercel.app/) |
| [20 Questions](https://github.com/AdemolaAdedoyin/20questions) | Local two-player guessing game with privacy handoffs, round history, persistence, and responsive UI. | [Play](https://20questions-ten.vercel.app/) |

Backend projects include local setup instructions and document their operational limits. Public deployment and external-provider acceptance are separate milestones; repository readiness does not imply a live production service.

## How I approach engineering

- **Correctness at the data boundary:** constraints, transactions, ownership checks, and explicit state transitions.
- **Recovery as part of the design:** durable intent, idempotency, retries, leases, and audit history.
- **Security beyond the UI:** scoped access, tenant isolation, secret handling, and safe outbound requests.
- **Verification and operations:** automated tests, CI, health checks, structured logs, and practical runbooks.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Backend | TypeScript, JavaScript, Node.js, NestJS, Express |
| Data and messaging | PostgreSQL, MySQL, Redis, Prisma, BullMQ, Kafka, RabbitMQ |
| Frontend | React, Vue.js |
| Cloud and delivery | AWS, Docker, Kubernetes, GitHub Actions |
| Testing and contracts | Vitest, Playwright, OpenAPI / Swagger |

My [portfolio website](https://github.com/AdemolaAdedoyin/portfolio) is also in progress. Earlier transaction-service experiments live in [RiseBeta](https://github.com/AdemolaAdedoyin/riseBeta); the current financial-systems work is in [Fintech](https://github.com/AdemolaAdedoyin/fintech).

---

I care about software that is understandable, testable, and designed to hold up beyond the happy path.
