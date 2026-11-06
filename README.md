# Hi, I'm Francisco Vasconcelos 👋

**Backend Engineer · PHP/Laravel, PostgreSQL & Applied AI (LLM agents, RAG) · Fintech · WhatsApp Cloud API**

I build and own production backend systems for a consumer-lending platform at **DiiMO Technologies**: loan lifecycle, payments, disbursements, collections, customer onboarding, and an AI assistant that serves customers over WhatsApp. Before that, I reverse-engineered web applications to build integrations at **Knot** (New York, remote).

## 🛠️ What I build

- **Applied AI**: multi-agent LLM assistant on the Laravel AI SDK (Gemini, AWS Bedrock failover), native sub-agents, typed session state, RAG with pgvector, anti-hallucination guards, and live model evals.
- **AI image & document processing**: payment receipts and ID documents read through OCR and validated by LLM agents before they reach accounting.
- **Official WhatsApp Business Cloud API (Meta)**: conversation inbox with AI ↔ human handoff, agent assignment, approved templates, and media messages.
- **Financial integrity**: idempotent disbursements with payment providers, race-condition fixes, payment reversals, daily-interest accrual.
- **Performance & security**: PostgreSQL tuning with `EXPLAIN ANALYZE` and targeted indexes (seconds → milliseconds); IDOR and tenant-isolation fixes; PII-redacted structured logging.

## 🚀 Featured project

**[llm-receipt-guard](https://github.com/Frankva12/llm-receipt-guard)** — extract payment-receipt data with an LLM and refuse to trust it until deterministic guardrails agree. Structured outputs with Claude, provider failover, grounding checks against the source text, offline and live evals, FastAPI, CI. A public, synthetic-data version of a pattern I run in production.

## ⚙️ How I work

- Background processing with queues, scheduled jobs, and idempotent commands
- REST APIs documented with OpenAPI/Swagger
- Shipping through GitLab CI pipelines with automated quality gates (Pest, PHPStan, Pint) in Docker-based environments
- User experience first: clear admin interfaces in Filament v4/Livewire and actionable messages for customers
- AI-assisted engineering with Claude Code, Kiro, Cursor, and GitHub Copilot, while I own the design, review every change, and back it with tests

## 💻 Tech stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Filament](https://img.shields.io/badge/Filament-FDAE4B?style=for-the-badge&logoColor=black)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge&logo=livewire&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp%20Cloud%20API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![ClickUp](https://img.shields.io/badge/ClickUp-7B68EE?style=for-the-badge&logo=clickup&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

## 🌐 Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/frankva12/)
[![GitLab](https://img.shields.io/badge/GitLab-FC6D26?logo=gitlab&logoColor=white)](https://gitlab.com/Frankva12)
[![X](https://img.shields.io/badge/X-black?logo=x&logoColor=white)](https://x.com/Frank_va12)

## 📊 GitHub stats

![](https://github-readme-streak-stats.herokuapp.com/?user=Frankva12&theme=dark&hide_border=false)

*Open to remote Backend or AI Engineer roles.*
