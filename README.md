## Sandeep Kumar

**Applied AI Engineer building reliable LLM, agentic AI, and ML systems.**
Final-year B.Tech in Mathematics & Computing at IIIT Bhagalpur, India.

I build AI applications the way I would want to operate them: plain code where the answer must be exact,
a model only where judgement is needed, outputs validated against a schema, quality measured on labelled data,
and failures reported explicitly instead of hidden behind a confident answer.

### Featured work

| Project | What it does | How it is verified |
|---|---|---|
| [**vireo-audio-support-intelligence**](https://github.com/SANDEEP-K15/vireo-audio-support-intelligence) | Weekly support digest. An LLM assigns each ticket one of 26 issue themes; cleaning, repeat-contact detection, costs and the leaderboard are deterministic pandas. Anthropic and Gemini behind one interface, with a cheapest-first model ladder and a cost gate on the historical backfill. | Gold set of 120 human-labelled tickets, locked by SHA-256: 98.3% accuracy for the selected model at about $0.00036 per ticket (repo report, private assessment data). Offline test suite with providers faked. |
| [**intelligent-routing**](https://github.com/SANDEEP-K15/intelligent-routing) | Routes service requests to one of seven team queues with TF-IDF features and a calibrated linear SVM, served through FastAPI with plain-language reasons. | Time-based validation: 96.8% agreement with the existing bot's labels on the latest quarter (repo report, private data). The README also shows why that target matches the team that finally resolved a request only about 77% of the time. CI on Python 3.11–3.13. |
| [**CareerPilotAI**](https://github.com/SANDEEP-K15/CareerPilotAI) | Job discovery and matching platform in a hexagonal architecture: FastAPI, async SQLAlchemy, Alembic, Temporal workflows, provider-neutral ports for job sources and LLMs, deterministic + semantic match scoring, approval-gated actions. | 31 architecture decision records, strict mypy, an architecture-boundary test, unit/contract/integration tests against Postgres in CI. Work in progress: the HTTP API has no deployed entry point yet. |
| [**agentic-research-intelligence**](https://github.com/SANDEEP-K15/agentic-research-intelligence) | Research agent written without an agent framework: goal analysis, planning, a tool registry, bounded retries, evidence selection and a structured report that ends as `success`, `partial` or `failed`. | Offline test suite with a fake LLM and fake search, including retry limits, non-retryable errors and empty-search handling. Example runs include a failed and a partial result. |
| [**Clinical-Lab-Results-Analyzer**](https://github.com/SANDEEP-K15/Clinical-Lab-Results-Analyzer) | Lab-result triage: reference-range classification in code, LLM explanations under a safety-constrained prompt with a fallback, and an MCP server exposing the lab tools. Educational, not diagnostic. | Backend test suite (pytest). |

### How I approach AI systems

- **Deterministic first.** In vireo the model makes one judgement per ticket; dates, costs and joins are ordinary code with assertions.
- **Validated outputs.** Model responses are parsed into Pydantic schemas and rejected or retried when they do not fit.
- **Measured before rollout.** Models are scored on gold data cheapest-first, and the cheapest one that passes is used.
- **Honest failure states.** Agents and pipelines return `partial` or `failed`, or fall back to rules, rather than inventing an answer.

### Also built

- **[api-rate-limiter](https://github.com/SANDEEP-K15/api-rate-limiter)**: multi-tenant rate-limit decision service with an atomic Redis Lua token bucket, hashed API keys and Prometheus metrics.
- **[urumi-ai](https://github.com/SANDEEP-K15/urumi-ai)**: Kubernetes store provisioning with namespace-per-tenant isolation, Helm charts, quotas and network policies.
- **[zycus-ai-engineer-assessment](https://github.com/SANDEEP-K15/zycus-ai-engineer-assessment)**: ticket triage with knowledge-base retrieval, schema-validated Gemini output and citation checks.

### Tools I have used in these projects

Python · FastAPI · Pydantic · scikit-learn · pandas · SQLAlchemy · Alembic · PostgreSQL · Redis · Temporal ·
Anthropic and Gemini APIs · Qdrant · MCP · Docker · Kubernetes · Helm · TypeScript · Next.js · GitHub Actions

### Currently

Adding evaluation to CareerPilotAI's matching, and making my main projects reproducible from a clean clone with synthetic data.

### Contact

[LinkedIn](https://www.linkedin.com/in/sandeep-kumar-7843572aa/) · [Email](mailto:1517sandeep@gmail.com)
