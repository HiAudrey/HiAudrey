# Hi, I'm Weimeng 

**Applied AI Engineer** building production LLM systems — from domain research through deployment.

I'm the founder and solo engineer of [**EudaimonAI**](https://eudaimonai.org), a 501(c)(3) nonprofit running a live AI product in 18+ countries with 1,000+ users and 200+ MAU — architecture, RAG, multi-model orchestration, eval infrastructure, and production ops, all owned by one person. Zero funding, zero marketing spend.

Before AI, I spent **8 years embedded in a fintech risk team** building credit models on 2M+ daily transactions. That work taught me something that matters as much for LLMs as for credit models: *the domain matters as much as the model, data quality decides output, and the engineer who understands both is the one who ships systems that get trusted.*

I hold a M.S. in Data Analytics Engineering from Northeastern University (GPA 3.83).

📬 [LinkedIn](https://linkedin.com/in/weimengduan) · 🌐 [EudaimonAI.org](https://eudaimonai.org) · ✉️ duan.weimeng0@gmail.com

---

## 🛠 Tech Stack

**Core Languages** — Python · TypeScript · SQL
**LLM Systems** — OpenAI · Gemini · Groq · LangChain · RAG with pgvector · Prompt Engineering · LLM-as-Judge Evaluation · Multi-Model Orchestration
**Backend & Infra** — Node.js · FastAPI · Next.js · Supabase (Postgres + pgvector + Auth) · Vercel
**Data & Modeling Foundations** — Pandas · NumPy · Scikit-learn · XGBoost · PostgreSQL · Feature Engineering · Time Series
**Tools** — Git · Cursor · Claude Code

---

## 🧠 How I Build AI Systems

I approach AI development as a **system design problem**, not a model problem.

**1. Problem framing first.** I start by identifying decision points under uncertainty — where users struggle with interpretation, ambiguity, or conflicting signals. The goal is to improve human judgment and clarity, not to maximize raw model output.

**2. Systems over models.** Instead of relying on a single LLM call, I design multi-step systems:
- Structured input and context capture
- Retrieval (RAG) for grounding
- LLM reasoning with versioned, eval-tested prompts
- Structured outputs with schema validation and typed fallbacks
- Multi-model fallback routing for reliability

**3. Eval-first development.** I built an LLM-as-judge regression harness with domain-informed synthetic personas before the product had a marketing page. Every prompt change is validated against the eval suite before deploy.

**4. Production iteration loops.** Real metrics (MAU, retention, session depth) drive the roadmap. Prompts get rewritten based on user signals, not opinions. Ships weekly against real data.

---

## 📊 Prior Life: Fintech Risk & Predictive Modeling

Before AI, 8 years at a consumer lending platform processing 2M+ daily transactions.

- **Credit Risk Modeling** — Built scoring and risk assessment models (logistic regression, random forest, XGBoost) used in live production loan decisions. Feature engineering pipelines over raw transactional and behavioral data, with emphasis on interpretability for regulatory and business stakeholders.
- **Vendor Data Evaluation** — Designed a data-provider quality scoring system from scratch; ran downstream intervention tests to measure real model impact. Cut external data spend while improving reliability.
- **Model Evaluation** — ROC/AUC · Precision-Recall · KS Statistic · Cross-Validation · Feature Importance

---

## 📌 Selected Work

**[EudaimonAI](https://eudaimonai.org)** — Production LLM application, live in 18+ countries
Solo-built AI system combining RAG with pgvector, multi-model fallback (OpenAI → six Gemini variants → Groq), rolling long-term memory compression, LLM-as-judge eval harness with synthetic personas, and bilingual (EN/ZH) safety-signal routing. Full stack: Next.js · TypeScript · Supabase · Vercel.

*Core code is in a private repo for IP reasons; happy to walk through architecture in conversation.*
