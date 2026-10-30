<p align="center">
  <img src="assets/banner.svg" alt="Sandeep Kumar — Applied AI Engineer building reliable LLM, agentic AI and ML systems" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sandeep-kumar-7843572aa/"><img src="https://img.shields.io/badge/LinkedIn-Sandeep%20Kumar-0A66C2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="mailto:1517sandeep@gmail.com"><img src="https://img.shields.io/badge/Email-1517sandeep%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20ML%20engineering%20roles-22c55e?style=for-the-badge" alt="Open to AI / ML engineering roles">
</p>

I build AI applications the way I would want to operate them: **plain code where the answer must be exact,
a model only where judgement is needed**, outputs validated against a schema, quality measured on labelled data,
and failures reported explicitly instead of hidden behind a confident answer.

## 🚀 Featured AI & LLM systems

<table>
  <tr>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/vireo-audio-support-intelligence"><img src="assets/card-vireo.svg" alt="vireo-audio-support-intelligence: LLM ticket classifier with a hash-locked gold set, a cheapest-first model ladder and cost gates. 98.3% accuracy on a 120-ticket human-labelled gold set." width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/intelligent-routing"><img src="assets/card-intelligent-routing.svg" alt="intelligent-routing: routes service requests to 7 team queues with TF-IDF and a calibrated SVM, served by FastAPI. 96.8% agreement on a time-based holdout." width="100%"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/CareerPilotAI"><img src="assets/card-careerpilotai.svg" alt="CareerPilotAI: job discovery and matching with hexagonal FastAPI, Temporal workflows and provider-neutral LLM ports. 31 architecture decision records, strict mypy." width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/agentic-research-intelligence"><img src="assets/card-agentic.svg" alt="agentic-research-intelligence: framework-free plan, execute, recover agent with a tool registry and bounded retries. 83 offline tests with a fake LLM and fake search." width="100%"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/Clinical-Lab-Results-Analyzer"><img src="assets/card-clinical-lab.svg" alt="Clinical-Lab-Results-Analyzer: lab-result triage with reference ranges in code, guarded LLM explanations with a safe fallback, and an MCP tool server. Educational, not diagnostic." width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/zycus-ai-engineer-assessment"><img src="assets/card-zycus.svg" alt="zycus-ai-engineer-assessment: ticket triage with knowledge-base retrieval, schema-validated output and citation checks. 34 tests, including the deterministic fallback." width="100%"></a></td>
  </tr>
</table>

<sub>Metrics come from each repository's own README and test suite. vireo and intelligent-routing were evaluated on private assessment data, so those numbers are as reported, not reproducible from a public clone. Clinical-Lab is educational, not diagnostic.</sub>

## ⚙️ Backend & platform engineering

<table>
  <tr>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/api-rate-limiter"><img src="assets/card-api-rate-limiter.svg" alt="api-rate-limiter: multi-tenant rate-limit decisions with an atomic Redis Lua token bucket, hashed API keys and Prometheus metrics." width="100%"></a></td>
    <td width="50%"><a href="https://github.com/SANDEEP-K15/urumi-ai"><img src="assets/card-urumi-ai.svg" alt="urumi-ai: Kubernetes store provisioning via a Fastify API, with a namespace per tenant, Helm charts, quotas and network policies." width="100%"></a></td>
  </tr>
</table>

## 🧭 How I build AI systems

<p align="center">
  <img src="assets/approach.svg" alt="1. Plain code for anything exact. 2. One model call only where judgement helps. 3. Schema validation: reject or retry bad output. 4. Gold-set eval: use the cheapest model that passes. 5. Explicit outcomes: success, partial or failed." width="100%">
</p>

- **Deterministic first.** In vireo the model makes one judgement per ticket; dates, costs and joins are ordinary code with assertions.
- **Validated outputs.** Model responses are parsed into Pydantic schemas and rejected or retried when they do not fit.
- **Measured before rollout.** Models are scored on gold data cheapest-first, and the cheapest one that passes is used.
- **Honest failure states.** Agents and pipelines return `partial` or `failed`, or fall back to rules, rather than inventing an answer.

## 🛠️ Tech I have used in these projects

| | |
|---|---|
| **LLMs & agents** | ![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white) |
| **ML & data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white) ![Temporal](https://img.shields.io/badge/Temporal-000000?style=for-the-badge&logo=temporal&logoColor=white) |
| **Infra & tooling** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) |

## 🔭 Currently

Adding evaluation to CareerPilotAI's matching, and making my main projects reproducible from a clean clone with synthetic data.
