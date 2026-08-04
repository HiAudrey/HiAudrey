# Hi, I'm Weimeng 

**Applied AI Engineer** building production LLM systems — from domain research through deployment.
🌐 [EudaimonAI.org](https://eudaimonai.org) 

---

## 🛠 Tech Stack

- **Core Languages** — Python · TypeScript · SQL
- **LLM Systems** — OpenAI · Gemini · Groq · LangChain · RAG with pgvector · Prompt Engineering · LLM-as-Judge Evaluation · Multi-Model Orchestration
- **Backend & Infra** — Node.js · FastAPI · Next.js · Supabase (Postgres + pgvector + Auth) · Vercel
- **Data & Modeling Foundations** — Pandas · NumPy · Scikit-learn · XGBoost · PostgreSQL · Feature Engineering · Time Series
- **Tools** — Git · Cursor · Claude Code

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

## 📌 Selected Work

**[Eudaimon](https://eudaimonai.org)** — Production LLM application, live in 18+ countries
Solo-built AI system combining RAG with pgvector, multi-model fallback (OpenAI → six Gemini variants → Groq), rolling long-term memory compression, LLM-as-judge eval harness with synthetic personas, and bilingual (EN/ZH) safety-signal routing. Full stack: Next.js · TypeScript · Supabase · Vercel.

*Core code is in a private repo; happy to walk through architecture in conversation.*
