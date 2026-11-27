<div align="center">

# Hi, I'm Spandan 👋

### AI/ML Engineer • GenAI & LLM Systems Builder

**RAG Pipelines · Multi-Agent Systems · LangGraph/LangChain · FastAPI · Local LLMs**

[![Email](https://img.shields.io/badge/Email-spandan4844%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:spandan4844@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Spandan%20Nagale-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/spandan-nagale-5a38a3290/)
[![Portfolio](https://img.shields.io/badge/Portfolio-spandan--nagale.vercel.app-C9A227?style=for-the-badge&logo=vercel&logoColor=white)](https://spandan-nagale.vercel.app/)

</div>

---

## 🧠 About Me

- 🎓 **B.Tech IT (AI/ML)** graduate — Dr. Babasaheb Ambedkar Technological University (DBATU)
- 💼 **ML Developer Intern @ Qriocity Ventures** — shipped **8 GenAI/ML systems** in 5 months
- 🔭 **Currently building:** **[Task-Agent](https://github.com/SpandanNagale/Task-Agent)** — a general "any task in, verified result out" agent that measures how far **local models + good orchestration** get on a 12 GB consumer GPU
- 💼 **Open to:** **AI/ML Engineer** and **GenAI/LLM Engineer** roles (freelance too)
- ⚡ I build **local-first, production-grade AI systems** — from a GPT pretrained from scratch to guarded SQL agents and eval harnesses
- 📏 Lately obsessed with **measurement**: eval harnesses, LLM-as-judge calibration, confidence intervals, and honest negative results

---

## 🚀 Flagship Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| **[QueryPilot](https://github.com/SpandanNagale/QueryPilot)** · [🔴 Live](https://query-pilot-nine.vercel.app/) | **Conversational text-to-SQL agent with hard guardrails** — every query is validated by **sqlglot AST inspection**, live schema checks, and a row-impact ceiling; writes show an FK-cascade-aware preview and run **only after you confirm**. Analytics mode streams summaries + charts. **60/60 eval accuracy.** | LangGraph · Ollama · FastAPI · SQLite · Vercel/Render |
| **[Task-Agent](https://github.com/SpandanNagale/Task-Agent)** 🚧 | Plan → act → observe → replan agent: a planner spawns parallel sub-agents, every capability is an **MCP tool**, code sandbox as universal fallback, and **a human approves every side effect**. Skills, memory, local knowledge, and web UI done; local benchmarks next. | MCP · Ollama · Python · uv |
| **[DataSleuth](https://github.com/SpandanNagale/DataSleuth)** | **Multi-agent autonomous data analyst** — Profiler → Hypothesis → Coder → **Critic** → Visualizer → Report, where the Critic **rejects hallucinated or statistically invalid conclusions**. Interactive trace viewer. Fully local. | LangGraph · Ollama · FastAPI · SSE |
| **[MarathiGPT](https://github.com/SpandanNagale/Marathi-GPT)** | **GPT pretrained from scratch** for Marathi — custom 32k SentencePiece tokenizer **4.8× more efficient than GPT-4's on Marathi**; full corpus → tokenizer → training → eval pipeline on a single RTX 5070. | PyTorch · SentencePiece |
| **[Self-Healing Hybrid RAG](https://github.com/SpandanNagale/Self-Healing-RAG)** | Hybrid RAG that **detects its own retrieval failures and recovers** — dense + BM25 (RRF), reranking, and a LangGraph loop that grades, retries, and verifies answers before responding. | LangGraph · FastAPI · RAGAS |
| **[Veritas](https://github.com/SpandanNagale/Veritas)** | Self-hosted **GraphRAG** — ChromaDB vector search seeds a **Neo4j knowledge-graph traversal**, and every answer shows the exact subgraph it walked. Runs fully offline. | Neo4j · ChromaDB · Ollama · Docker |

### 📏 LLM Evaluation & Developer Tooling

| Project | What it does | Stack |
|---------|-------------|-------|
| **[Assay](https://github.com/SpandanNagale/Assay)** | **Eval harness for LLM/agent features** — answers *did it pass, did it regress beyond noise, and can you trust the grader?* Async chunked runs with cost controls. | Next.js 15 · Supabase · Upstash · Drizzle |
| **[ContextLens](https://github.com/SpandanNagale/Context_lense)** | **Context-strategy benchmark for code LLMs** — strategy × model × token budget, AST-generated ground truth, **mean ± 95% CI**, and a quality/tokens/latency/cost Pareto frontier. | Next.js 15 · TypeScript |
| **[Keel](https://github.com/SpandanNagale/Keel)** | **Prompt compiler for coding agents** — interrogates a vague idea, flags contradictions and infeasible combos, and is explicit about which decisions were yours vs. its own. | Streamlit · Groq / Ollama / Claude |
| **[Plumb](https://github.com/SpandanNagale/Plumb)** | `repo-agent` CLI — tiered repo inspection (git → tooling → model judgment), fixes in an **isolated worktree verified by your own test suite**, pushes only after approval. | Python · git worktrees |
| **[CrewAI Research Pipeline](https://github.com/SpandanNagale/Crewai-Research-pipeline)** | Planner → Researcher → Writer → Critic research API with SSE streaming and an **automated eval scorer** for citation, coverage, and clarity. | CrewAI · FastAPI · Gemma |

### 🔬 Applied ML

| Project | What it does | Stack |
|---------|-------------|-------|
| **[DocIntel](https://github.com/SpandanNagale/DocIntel)** | Document intelligence for **Indian financial documents** (GST invoices, bank statements) — Donut OCR-free extraction, synthetic data generation, fraud/anomaly detection, **~683ms p50 serving**. | Donut · LightGBM · FastAPI |
| **[Sieve](https://github.com/SpandanNagale/Sieve)** | Two-stage **invoice anomaly detector** — Isolation Forest + LOF + seasonal residuals feeding a **weakly-supervised LightGBM** classifier, with hand-labelling app and SHAP. | scikit-learn · LightGBM · Streamlit |
| **[Gauge](https://github.com/SpandanNagale/Gauge)** | Does adding optical bands to **SAR** improve change detection under a fixed labelling budget? Bootstrap CIs, F1-vs-labels curves — and an honest write-up of a **negative result** and its caveats. | PyTorch · Remote sensing |

<details>
<summary><b>More projects</b></summary>

- **[ARIA](https://github.com/SpandanNagale/ARIA)** — fully local JARVIS-style voice assistant: wake word, GPU STT, Ollama tool-calling, PC control, memory, web search
- **[ML-Agent](https://github.com/SpandanNagale/ML-Agent)** — 9-agent system that builds, trains, and self-heals ML pipelines from one problem statement
- **[Study Assistant](https://github.com/SpandanNagale/Study_assistant)** — AI study suite: PDF QA, quizzes, SM-2 spaced-repetition flashcards, multi-provider fallback
- **[Research Copilot](https://github.com/SpandanNagale/Research-Copilot)** — fetches ArXiv papers, summarizes and clusters them, chat over the corpus with grounded RAG
- **[Life OS](https://github.com/SpandanNagale/Personal-Tracker)** — local-first life dashboard with a data-grounded AI coach and gamification

</details>

---

## 🛠️ Tech Stack

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**GenAI / Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-191919?style=flat-square&logo=anthropic&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=flat-square&logoColor=black)

**Retrieval & Data**

![ChromaDB](https://img.shields.io/badge/ChromaDB-6c3fc5?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Spandan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=SpandanNagale&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A1628&title_color=C9A227&icon_color=C9A227)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SpandanNagale&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A1628&title_color=C9A227)

![GitHub Streak](https://streak-stats.demolab.com?user=SpandanNagale&theme=tokyonight&hide_border=true&background=0A1628&ring=C9A227&fire=C9A227&currStreakLabel=C9A227)

</div>

---

## 🎯 What I Bring

- **End-to-end ownership** — from tokenizer design and model pretraining to FastAPI serving and Docker deployment
- **Evaluation-first mindset** — built my own eval harness (Assay) and context benchmark (ContextLens); 95% CIs, grader trust checks, and publishing negative results
- **Local-first engineering** — everything runs on consumer hardware (RTX 5070) with Ollama, no API dependency
- **Production instincts** — deterministic guardrails over prompts (AST validation, confirm-before-write), human approval gates, SSE streaming, live deployments

---

<div align="center">

**💬 Open to AI/ML & GenAI/LLM Engineer roles — let's build something.**

[![Email](https://img.shields.io/badge/Say%20Hello-spandan4844%40gmail.com-C9A227?style=for-the-badge)](mailto:spandan4844@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=SpandanNagale&color=C9A227&style=flat-square)

</div>
