# Applied AI Engineering Portfolio · Nil Alisson

> 🇺🇸 English · [🇧🇷 Versão em Português](https://github.com/nilalisson14/AIEngineer/blob/main/README.pt.md)

**Applied AI Engineer** with a Requirements Engineering foundation — 9+ years at the intersection of business, technology, and digital products, now applied to building AI systems in regulated domains. I design, build, and evaluate AI agents (RAG, LangChain/LangGraph, MCP), focused on auditability, compliance, and objective quality measurement — not throwaway proof-of-concept.

My edge isn't being the best at pure ML: it's understanding, in practice, what makes an AI system trustworthy enough to run in high-criticality environments (regulated healthcare, energy, public sector). That comes from 9+ years translating ambiguous business rules into testable requirements — the same discipline I now apply to prompts, RAG pipelines, and agent evaluation.

---

## About this repository

Gathers **real projects and anonymized case studies** from my applied AI work, organized by area of expertise. Each project describes context, stack, technical decisions, and outcome.
> **Anonymization note:** cases derived from professional context refer to clients generically (e.g. "health regulatory agency"). Names, credentials, endpoints, and operational data have been removed. The original projects (ReqGuard, RAG Provider Benchmark, hr-policy-agent-mcp) are public, auditable code.

---

## Index by competency

### 🔹 [01 · Generative AI & Agents](https://github.com/nilalisson14/reqguard)
RAG, agent orchestration, and prompt engineering applied to regulated domains.

- **[ReqGuard](https://github.com/nilalisson14/reqguard)** — AI system for requirements analysis and regulatory compliance: RAG, LangChain, LangGraph, ChromaDB, Google Gemini API, RAGAS evaluation, and MCP servers
- **[hr-policy-agent-mcp](https://github.com/nilalisson14/hr-policy-agent-mcp)** — AI agent for HR policy lookup, live in production (API + web demo)
- Conversational agents (Typebot + ChatGPT) — persona, tone, business-rule, and conversation-flow design for customer-service use cases

### 🔹 [02 · AI Evaluation & RAG](https://github.com/nilalisson14/rag-provider-benchmark)
Objective quality measurement — what separates a demo agent from a trustworthy one.

- **[RAG Provider Benchmark](https://github.com/nilalisson14/rag-provider-benchmark)** — comparison between Gemini via Vertex AI and the standalone Gemini API using RAGAS metrics; validates operational stability for zero-budget projects
- Senior-level LLM response evaluation (side-by-side) and structured fact-checking — identifying hallucinations and inconsistencies, documenting error patterns for RLHF (Turing, Outlier AI)

### 🔹 [03 · Regulatory Requirements Engineering](https://github.com/nilalisson14/BusinessAnalyst)
**The foundation everything above rests on.** In regulated domains, the bottleneck for an AI system is almost never the model — it's ambiguity in the requirements it's supposed to satisfy. 9+ years eliciting, specifying, and auditing requirements in environments where errors carry real institutional cost (public health, energy, state tax authorities) is what separates an agent that "works in a demo" from one that passes an audit and reaches production.

- **Discovery and elicitation across multi-stakeholder environments** — 50+ critical regulatory systems in public health (ANVISA), including discovery for the SNCR (National Prescription Control System)
- **Testable, traceable requirements** — user stories with acceptance criteria in BDD/Gherkin and UAT, applied to tax systems (SEFAZ-PB) and corporate energy systems (Petrobras/SIGITEC)
- **End-to-end governance and compliance** — process modeling (BPMN/Bizagi), REST API contracts, and UAT/QA coordination in an LGPD-compliant environment
- **The same discipline applied to AI:** prompt engineering treated as requirements engineering — specifying expected behavior, defining acceptance criteria for agent responses, and maintaining traceability between business rule, prompt, and model output. It's this discipline, not the AI framework itself, that sustains auditability in production
- See the [full Requirements Engineering portfolio](https://github.com/nilalisson14/BusinessAnalyst) for detailed institutional case studies, each with context, scope, and outcome

### 🔹 [04 · Requirements Engineering + GenAI on AWS](https://github.com/nilalisson14/case-ba-re-aws-genai)
Requirements engineering case applied to a serverless AI architecture on AWS.

- **[case-ba-re-aws-genai](https://github.com/nilalisson14/case-ba-re-aws-genai)** — requirements and solution specification for a GenAI system on the AWS stack (Bedrock, Lambda), connecting requirements elicitation to serverless AI architecture

### 🔹 [Own product: AI Agent SaaS](https://github.com/nilalisson14/Professional-AI-Framework)
- **Professional AI Framework** — platform for building AI agents with landing pages (FastAPI, PostgreSQL, ChromaDB, Nginx, Oracle Cloud VPS)

---

## Career summary

| Period    | Role                                                          | Domain                  |
| --------- | --------------------------------------------------------------- | ------------------------ |
| 2025–present | Applied AI Engineer (original projects)                     | RAG, agents, evaluation  |
| 2024–2026 | GenAI applied to Requirements Engineering (regulated health) | Public health oversight  |
| 2024–2026 | GenAI Consultant — prompts, conversational agents, LLM evaluation | Applied AI (freelance) |
| 2021–2024 | Requirements Analyst (energy, tax authority)                 | R&D governance, taxation |
| 2018–2021 | Requirements Analyst → IT Coordinator                        | Education                |

The trajectory shows a transition from requirements engineering in regulated environments to applied AI engineering — carrying over the same discipline of auditability and quality measurement.

---

## Education & certifications

- **M.Sc. in Computer Science** (in progress) — UFPB — research on LLMs applied to Requirements Engineering
- **MBA in IT Governance**
- **B.Sc. in Information Systems** — UFPB
- AWS Cloud Practitioner · Scrum Foundation (SFPC) · GenAI for Startups (AWS Bedrock)

## Technical skills

**Generative AI & Agents**
`LangChain` / `LangGraph` — frameworks for orchestrating LLM calls and building multi-step agents (plan → call tool → execute → validate), instead of a single isolated prompt.
`RAG` (Retrieval-Augmented Generation) — architecture that retrieves relevant information from a knowledge base before generating a response, reducing hallucination and letting the agent answer grounded in real documents (regulations, policies, requirements).
`MCP` (Model Context Protocol) — a standard protocol for connecting an AI agent to external tools and data sources in a secure, reusable way.

**AI APIs**
`OpenAI API` · `Anthropic Claude` · `Google Gemini API` / `Vertex AI` — direct integration with the leading LLM providers, including the enterprise route (Vertex AI), more stable for production environments on a controlled budget.

**AI Evaluation**
`RAGAS` — a framework that objectively measures RAG system quality (answer accuracy, retrieval relevance, faithfulness to context) instead of eyeballing it.
`Side-by-side evaluation` and `structured fact-checking` — systematic comparison of responses across models/versions against quality criteria, used to catch hallucination and inconsistency before production.

**Data & Semantic Search**
`ChromaDB` — a vector database: stores text converted into numerical vectors to enable search by meaning rather than keyword alone (the technical foundation of any RAG system).
`pandas` — the standard Python library for tabular data manipulation and analysis.

**Backend & Integration**
`Python` · `FastAPI` (API framework) · `PostgreSQL` (relational database) · `REST APIs` and `webhooks` (system-to-system integration patterns).

**Cloud & Infrastructure**
`AWS` (Cloud Practitioner certified) · `Google Cloud` (Vertex AI) · `Oracle Cloud` · `Nginx` (web server) · `systemd` (production service management) · `GitHub Actions` (test and deploy automation — CI/CD).

**Requirements & Governance**
Discovery · functional and non-functional requirements · acceptance criteria (BDD/UAT) · compliance and auditability in regulated environments — the discipline that ensures any system above, including AI systems, actually meets what the business needs and holds up under audit.

---

## Contact

🌐 [nilalisson.com.br/portfolio](https://nilalisson.com.br/portfolio) · 💼 [linkedin.com/in/po-alisson](https://linkedin.com/in/po-alisson) · ✉️ <nilalisson@gmail.com>
