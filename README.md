# Mohd. Hussain Ansari

**Software Development Engineer 2 · Back-end Engineering**

Real-time systems, payments, and the boring parts of money.

Mumbai, India · 4+ years · open to Mumbai or remote
[Portfolio](https://mohd-hussain-ansari.vercel.app) · [LinkedIn](https://www.linkedin.com/in/mohd-hussain-ansari) · [mohd.hussainansari19@gmail.com](mailto:mohd.hussainansari19@gmail.com)

---

## What I work on

I build back-end systems in Node.js, NestJS and TypeScript, and my work tends to land where correctness matters more than throughput — payment and subscription lifecycles, wallet and ledger mechanics, and idempotency at the boundaries where money changes state. A duplicate charge is not a performance problem you can tune away later.

The other half is real-time infrastructure: Socket.IO over Redis Pub/Sub, fanned out across multiple servers so a message raised on one instance reaches sockets connected to any other. That currently carries 3,000+ concurrent connections for messaging, presence and live notifications.

I also take on the migration and performance work nobody volunteers for — moving 800+ sellers with zero data loss, reworking schema and indexing across 2.7 million records, and instrumenting things properly first so the wins are measured rather than guessed at.

---

## Selected work

Architecture write-ups for each of these live on my [portfolio](https://mohd-hussain-ansari.vercel.app), with diagrams and the decisions behind them.

**[Creator Subscription & Wallet Platform](https://mohd-hussain-ansari.vercel.app/work/subscription-wallet-platform)** — INK IN CAPS
NestJS monorepo: five deployable apps, seven shared libs, MongoDB, Redis, BullMQ. Unified checkout across five payment providers behind signature-verified idempotent webhooks, a multi-recipient transaction ledger, and a two-bucket wallet separating spendable balance from escrowed creator earnings.
`3,000+ concurrent connections` · `~$462K/mo across ~7,700 transactions` · `30K+ users` · `−75% feed load time`

**[Multi-Tenant Seller Marketplace](https://mohd-hussain-ansari.vercel.app/work/seller-marketplace)** — Brownliving @ AppOctet
NestJS · MySQL · TypeORM. Seller operations, order management and Shopify sync, with a staged dump table as the idempotency boundary and carriers modelled as data rather than branches. OpenTelemetry into Signoz made the latency work measurable.
`800+ sellers migrated, zero data loss` · `2.7M records re-indexed` · `−25% query latency`

**[Events & Booking Platform](https://mohd-hussain-ansari.vercel.app/work/events-booking)** — PlayAce @ AppOctet
Express · MongoDB, serving a web client, a React Native app and an admin surface. Razorpay payouts and refunds, Onfido KYC driven by webhooks rather than polling, and operational alerts routed into Slack instead of a dashboard nobody checks.
`−40% admin response time` · `5 notification channels` · `3 clients from one backend`

**[ONDC Logistics Network Integration](https://mohd-hussain-ansari.vercel.app/work/ondc-logistics)** — AppOctet
NestJS · MySQL implementing India's Open Network for Digital Commerce protocol: pre-order, post-order, grievance (IGM) and reconciliation (RSP) domains behind cryptographic signature verification, with an adapter layer translating between the protocol and the carrier's existing API.
`certified with 5+ partner organisations` · `16 protocol services across 4 domains`

**[Offline-First Rider App](https://mohd-hussain-ansari.vercel.app/work/rider-delivery-app)** — AppOctet
React Native for delivery riders working without reliable connectivity. SQLite is the on-device source of truth rather than a cache, and a sync engine routes each shipment by type crossed with outcome — because a failed pickup and a failed delivery settle differently.
`a full shift capturable offline` · `4 flows / 8 settlement routes` · `4 locales`

---

## Stack

**Languages** — TypeScript, JavaScript (ES6+), Java

**Runtime & frameworks** — Node.js, NestJS, Express.js, React Native

**Data** — MongoDB, MySQL, PostgreSQL, Redis, Mongoose, TypeORM, Prisma, SQLite

**Async & real-time** — BullMQ, Redis Pub/Sub, Socket.IO, WebSockets, Agenda, delayed jobs, retry strategies

**Architecture** — REST APIs, webhooks & signature validation, event-driven systems, idempotency & retries, wallet & ledger design, subscription lifecycle, RBAC / CASL policies

**Cloud & infra** — AWS EC2, ALB, Route 53, Lambda, SES, SQS, S3, CloudFront, Docker, Git

**Integrations** — Razorpay, Cashfree, Centrobill, Shopify, Onfido, Delhivery, Shiprocket, ONDC, Firebase, WhatsApp API, Slack

**Testing & observability** — Jest, Supertest, OpenTelemetry, Signoz, New Relic, Winston, Pino, Swagger

**AI-assisted development** — Claude, GitHub Copilot, ChatGPT

---

## Impact

- `3,000+` concurrent WebSocket connections across multiple servers
- `~$462K` in monthly transaction value, across `~7,700` transactions
- `30K+` users served by payment-gateway workflows
- `800+` sellers migrated with zero data loss
- `2.7M` records re-indexed; `25%` query-latency improvement
- `75%` faster home feed, transferring `~90%` less data
- Led a `10`-member cross-functional team of back-end and QA engineers
- Stakeholder and demo work with founders and clients across London, Dubai and Canada
- **Star Performer — 2024 & 2025**, AppOctet Technologies
- **ONDC network certification** with 5+ partner organisations

---

## Public code

Most of my production work from the last four years sits behind NDAs, so it isn't here. The architecture write-ups on my [portfolio](https://mohd-hussain-ansari.vercel.app) are the honest substitute — real systems, described in enough detail to be useful, without naming what I can't name.

What is public:

- **[Expense-Tracker-Backend](https://github.com/Mohd-Hussain-Ansari/Expense-Tracker-Backend)** — TypeScript · Express · MongoDB. JWT auth, Zod validation, transaction filtering, soft deletes, Swagger docs and test coverage. The closest public sample to how I actually write back-end code.
- **[Human-Activity-Recognizer](https://github.com/Mohd-Hussain-Ansari/Human-Activity-Recognizer)** — ML classification in a Jupyter notebook.

University coursework, kept for the record rather than as a work sample:

- **[Compiler](https://github.com/Mohd-Hussain-Ansari/Compiler)** — NFA/DFA and core automata theory in Java.
- **[Android-Chess-Game](https://github.com/Mohd-Hussain-Ansari/Android-Chess-Game-public)** — two-player chess, Firebase online mode and SQLite offline mode, with undo/redo.

---

## Education & certifications

**B.Sc. Computer Science** — Ismail Yusuf College, University of Mumbai (2019 – 2022) · **First Rank**

- Generative AI Mastermind — OutSkill
- Problem Solving (Basic) — HackerRank
- Algorithm Essentials — HackerRank
- AI Tools Workshop — Be10x

---

## Contact

Open to back-end engineering roles, consulting, and interesting product conversations.

[Portfolio](https://mohd-hussain-ansari.vercel.app) · [LinkedIn](https://www.linkedin.com/in/mohd-hussain-ansari) · [mohd.hussainansari19@gmail.com](mailto:mohd.hussainansari19@gmail.com)
