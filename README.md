# 👋 Hi, I'm Vijay Yadav — Full Stack Data & AI Engineer

🎯 I build secure, intelligent data systems and platforms that help people succeed  
🚀 Founder of [StudentSucceed](https://studentsucceed.com) — AI-powered career platform for university students  
🧠 Creator of [localmem](https://localmem.org) — open-source, local-first memory for AI agents (MCP-native, Apache-2.0)  
🔧 Active OSS contributor to [AltimateAI/altimate-code](https://github.com/AltimateAI/altimate-code)  
🎥 I also run [vjsnapp.com](https://vjsnapp.com), my photography & video passion

---

## 🛠️ What I'm Building

### [StudentSucceed](https://studentsucceed.com) — AI Career Platform
Full-stack SaaS platform helping university students find jobs, prepare for interviews, and manage their career journey. Solo-built from scratch — backend, frontend, data pipelines, infrastructure.

**Highlights:**
- **44x search optimization** — Job search from 2.4s → 55ms via PostgreSQL TSVECTOR + query restructuring
- **Async resume pipeline** — 6.1s parse with Gemini structured output, non-blocking uploads
- **Agentic data pipeline** — Medallion architecture collecting from 7+ ATS providers (Ashby, Lever, Greenhouse, Adzuna, USAJobs, Muse, RemoteOK)
- **Credit-based billing** — Stripe integration with atomic credit transactions, tier-based access control
- **Voice AI interviews** — Real-time WebSocket interview practice with Deepgram + LLM scoring
- **Full CI/CD** — GitHub Actions for staging/production deploys, automated migrations

**Stack:** Python · FastAPI · Next.js · PostgreSQL · AWS ECS/Fargate · Stripe · Gemini · Deepgram

---

### [localmem](https://localmem.org) — Open-Source Memory for AI Agents
The memory layer that follows you across every AI tool (Claude Code, Cursor, Cline, Windsurf, Claude Desktop). Open-source (Apache-2.0), local-first, and shipped as a single static Rust binary. Your memory is one plain-text file you own, with zero content telemetry.

**Highlights:**
- **75% on LongMemEval** — a 500-question long-term-memory benchmark, via a two-stage hybrid retriever (BM25 + vector search, reranked by a local cross-encoder)
- **Recomputable trust** — an append-only event log is the source of truth; `localmem replay` rebuilds every derived store from that one file
- **Bitemporal memory** — answers "what did I believe on date X" and resolves conflicting facts by when they were true, not by ingest order
- **Local intelligence** — an async worker distills each memory into a typed knowledge graph with a local LLM, off the write path
- **MCP-native** — works with every MCP-compatible client; one-command install via `curl` or `npx`

**Stack:** Rust · DuckDB · LanceDB · Tantivy · ONNX · MCP · TypeScript  
[Website](https://localmem.org) · [GitHub](https://github.com/VJ-yadav/localmem-community) · [npm](https://www.npmjs.com/package/localmem-mcp)

---

### OSS Contributions — [AltimateAI/altimate-code](https://github.com/AltimateAI/altimate-code)

Active contributor to Altimate's open-source data tool. **10 PRs** (1 merged, 9 in review):

| PR | Description |
|----|-------------|
| [#649](https://github.com/AltimateAI/altimate-code/pull/649) | feat: Databricks AI Gateway as LLM provider |
| [#622](https://github.com/AltimateAI/altimate-code/pull/622) | feat: Native GitLab MR review integration ✅ merged |
| [#621](https://github.com/AltimateAI/altimate-code/pull/621) | fix: Accept `mcpServers` as alias for `mcp` in config |
| [#599](https://github.com/AltimateAI/altimate-code/pull/599) | fix: ClickHouse driver review findings |
| [#597](https://github.com/AltimateAI/altimate-code/pull/597) | fix: URL-encode special characters in connection string passwords |
| [#596](https://github.com/AltimateAI/altimate-code/pull/596) | fix: Pagination support for recap trace list |
| [#550](https://github.com/AltimateAI/altimate-code/pull/550) | fix: Pass warehouse dialect to altimate-core tools |
| [#548](https://github.com/AltimateAI/altimate-code/pull/548) | fix: Re-trace system prompt on agent switch |
| [#547](https://github.com/AltimateAI/altimate-code/pull/547) | fix: Update remaining opencode references in CLI |
| [#432](https://github.com/AltimateAI/altimate-code/pull/432) | fix: Migrate string interpolation to parameterized query binds |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VJ-yadav&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VJ-yadav&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=VJ-yadav&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 🧠 Tech Stack

**Languages & Frameworks**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Data & AI**  
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat-square&logo=snowflake)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apache-airflow)
![Gemini](https://img.shields.io/badge/-Gemini-886FBF?style=flat-square&logo=google&logoColor=white)

**Infrastructure**  
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Stripe](https://img.shields.io/badge/-Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)

---

## 💼 Experience

**🚀 Founder & Full Stack Engineer** — [StudentSucceed](https://studentsucceed.com) _(2024–Present)_  
Building an AI-powered career platform for university students. Solo architect of the entire stack — backend services, React frontend, data pipelines, cloud infrastructure, and billing.

**🎓 Student Success Analyst** — Bentley University _(2024–Present)_  
Built FinAid dashboards, cohort models, and retention metrics. Led masking + access control of clinical & referral data.

**☁️ Lead Data Engineer** — Healthcare Cloud  
Built scalable pipelines with GCP, PySpark, Airflow, BigQuery.

---

## 📦 Featured Projects

| Project | Description |
|---------|-------------|
| 🧠 [localmem](https://localmem.org) | Open-source local-first memory for AI agents — MCP-native, Rust, 75% on LongMemEval |
| 🎓 [StudentSucceed](https://studentsucceed.com) | AI career platform — jobs, interviews, resume parsing, credit billing |
| 🔧 [altimate-code contributions](https://github.com/AltimateAI/altimate-code/pulls?q=author%3AVJ-yadav) | 10 PRs: Databricks provider, GitLab integration, SQL injection fixes |
| 🎬 [filmtrends-fullstack](https://github.com/VJ-yadav/filmtrends-fullstack) | Lambda + S3 video intelligence app |
| 🧠 [sqldatawarehouse](https://github.com/VJ-yadav/sqldatawarehouse) | dbt-powered Snowflake warehouse |
| 🌐 [AWS Data Engineering](https://github.com/VJ-yadav/AWS_Data_Engineering_P1) | End-to-end AWS data engineering project |

---

## 🌐 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vjyadav)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vjyadav193@gmail.com)
[![Website](https://img.shields.io/badge/-vjsnapp.com-000000?style=flat-square&logo=safari&logoColor=white)](https://vjsnapp.com)
