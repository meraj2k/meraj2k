### Meraj Ansari

Backend engineer (Go) at **TestMu AI** — designing event-driven systems, multi-tenant platforms, and LLM-powered backends. ~4 years shipping distributed pipelines at production scale.

---

**Currently building**

- **Event-driven notification & integration platform (Go + Kafka)** — pluggable notifier architecture delivering test and accessibility results to Slack, Jira, GitHub CI, and Azure DevOps. Multi-tenant plugin sharing at the org level, async processing with retries, fault-tolerant at-least-once delivery.
- **Bi-directional CRM data-sync engine (Go)** — Salesforce sync for contacts, leads, accounts, and orgs via cron + event-driven jobs (payment, invoice, trial events), with lead enrichment and custom recovery middleware. Replaced a legacy PHP pipeline.
- **Multimodal AI test-case generator** — ingests docs, audio, and video (S3 → AWS Lambda) through an LLM prompt pipeline that produces structured test cases (title, scenarios, priority) and opens Jira tickets.
- **AI chat-completions with tool-calling + agentic research** — pluggable tool registry over Composio (Gmail, Calendar, Tasks), RAG-style contact search, and multi-step LLM tool-calls that auto-enrich CRM records with resolved entity data.
- **Graph-backed contact platform on Neo4j** — concurrency-safe connection pooling, background health checks, fed by an event-driven contact-lifecycle pipeline.

**Earlier — Woovly (2022–25)**

- Redis caching on order processing → ~40% faster
- Real-time order tracking → ~30% fewer customer-support queries
- Guest checkout + cart improvements → ~20% lower cart abandonment
- CTV content-moderation workflow → ~40% moderation-efficiency gain

**Stack** — Go (primary), Node/TypeScript, Java · Kafka · PostgreSQL, MongoDB, Redis · Neo4j · AWS (Lambda, S3), Docker, Kubernetes

---

Most of my code lives in private work repos. Public side-project work has been intentionally minimal; sanitized architecture writeups are coming next.

---

**Contact** — [meraj.iiits@gmail.com](mailto:meraj.iiits@gmail.com) · [LinkedIn](https://linkedin.com/in/merajansari)
