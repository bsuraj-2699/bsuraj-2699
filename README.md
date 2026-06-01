# Suraj Bhonkar

**AI Engineer — LLM systems, multi-agent pipelines, RAG architectures.**

I ship production AI products end-to-end. Independent builder based in Navi Mumbai. Currently certified through IIT Hyderabad in AI & Emerging Technologies and Vanderbilt's Prompt Engineering Specialisation.

---

### Selected work

**[ALPHA](https://github.com/bsuraj-2699/ALPHA)** — Multi-agent financial analysis system for Indian equities (IIT Hyderabad capstone).
A 7-node LangGraph pipeline: parse → context build → 5 parallel analysts (Fundamental, Technical, Sentiment, Macro, Risk) → Bull/Bear debate → Judge → Decision. Full analysis in under 40 seconds. Up to 70% directional accuracy on Nifty 50 top-10 signals. RAG via Qdrant + BM25 hybrid retrieval. Real-time data from Upstox, Yahoo, Screener.in, NSE, and GDELT.
FastAPI · LangGraph · GPT-4o · Qdrant · PostgreSQL · Redis · Next.js · Docker
[Live demo →](https://alpha-gamma-umber.vercel.app)

**[quest-evaluator](https://github.com/bsuraj-2699/quest-evaluator)** — Zero-intervention AI hiring pipeline.
Google Forms → polled every 60s → AI evaluates across 7 weighted dimensions → results written to Sheets and live dashboard. 8-second turnaround per candidate, roughly 112× faster than manual review. Auto-extracts GitHub READMEs and unzips Drive submissions to inspect 8 key files. Supports OpenAI, Anthropic, Gemini, Mistral, and Groq.
[Live demo →](https://quest-evaluator.vercel.app)

**[taskme](https://github.com/bsuraj-2699/taskme)** — Production task management platform for small teams (branded *Zapp*).
Reflex frontend, FastAPI backend with JWT auth, PostgreSQL with Alembic, APScheduler for EOD reports and stale-task follow-ups. Fully Dockerized with CEO and employee dashboards.

**[jobfit-agent](https://github.com/bsuraj-2699/jobfit-agent)** — Resume-to-JD fit scoring with skill-gap analysis. Under 10 seconds per evaluation. Python · Streamlit · GPT-4o.

### Stack

**AI/ML** — LangGraph · LangChain · RAG · Multi-agent orchestration · Prompt engineering · LLM evaluation
**LLM providers** — OpenAI · Anthropic · Gemini · Groq (LLaMA-3.3-70B) · Mistral
**Backend** — Python · FastAPI · Node.js · PostgreSQL · Redis · Qdrant
**Frontend & infra** — Next.js · Streamlit · Reflex · Docker · Render · Vercel · Railway

### Background

Finance roots — PG Diploma in Global Financial Markets (BSE Institute), internship at Indian Clearing Corporation on collateral optimisation and SEBI compliance. Previously evaluated LLM outputs at Outlier.ai, documenting hallucination patterns and behavioural failure modes across model iterations. That structured-thinking background is what makes ALPHA's rule-engine-meets-LLM design work.

### Contact

[LinkedIn](https://www.linkedin.com/in/surajbhonkar) · bhonkarsuraj99@gmail.com
