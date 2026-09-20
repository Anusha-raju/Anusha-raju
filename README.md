# Hi, I'm Anusha 👋

🚀 **AI Engineer | Agentic RAG · LLM Evaluation · LLMOps**

I build AI agents for messy enterprise data and the evals that keep them honest.

Three years of NLP and LLM work in production. These days that means **LangGraph agents that call retrieval tools when they need them**, plus the **tracing and eval loop** that tells me a change made things worse before a user does. My habits: evals before features, a trace on every run, structured outputs instead of prompt warnings, and cost and latency on the dashboard from day one.

---

## 🔧 Tech & Tools

### Languages & Data
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### Agents & Retrieval
![LangGraph](https://img.shields.io/badge/LangGraph-121212?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0A0A0A?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-1E1E1E?style=for-the-badge&logoColor=white)
![Hybrid Retrieval](https://img.shields.io/badge/Hybrid_Retrieval-2D6A5F?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-111111?style=for-the-badge&logoColor=white)

### Evals & LLMOps
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-6A4C93?style=for-the-badge&logoColor=white)
![LLM-as-Judge](https://img.shields.io/badge/LLM--as--Judge-4A5568?style=for-the-badge&logoColor=white)

### ML & NLP
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logoColor=white)

### APIs, Deployment & Infra
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

### Databases & Retrieval Stores
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

## 💼 Experience

**Instructional Technologist - AI/ML Infrastructure, GWU Data Science** *(Aug 2026 – Present)*
- Building a **Advising assistant** with hybrid dense + sparse retrieval grounded in program documentation, so students get cited answers instead of generic ones.
- Run the **AWS ML environments** (EC2, S3, IAM, cost controls) for graduate capstone teams; containerized workspaces took setup from days to hours.
- Scope and de-risk applied AI capstones with faculty and industry sponsors.

**Research Assistant - LAiSER, GWU** *(Feb 2025 – May 2026)*
- **FAISS-based similarity search** over 10,000+ job descriptions, mapped to the **ESCO** and **O\*NET** skill taxonomies with a Neo4j graph for cross-taxonomy alignment.
- Shipped it as a **multi-tenant API on AWS** (FastAPI, Lambda, S3, EC2) with Docker and GitHub Actions CI/CD, **3× research throughput**, time-to-demo from weeks to a live public product.
- Presented the architecture to **150+ attendees at Badge Summit 2025**.

**Machine Learning Engineer - Ideapoke (now Chesz.ai)** *(May 2022 – Nov 2023)*
- Rebuilt the NER pipeline behind **Signalz**, which turns news, patents and papers into market and technology signals: **+40% extraction accuracy, −60% processing time**.
- Replaced brittle rule-based extraction with **RAG (LangChain + GPT)** producing structured output from large-scale unstructured web data.
- Built a contextual search engine that retrieved on **query intent rather than keyword match**, across 30+ industries.

---

## 🚀 Projects

- **[BRIDGE](https://github.com/Anusha-raju/spring-2026-group1.git)** →  Moved agents from **prompt stuffing to tool-driven RAG**: each clinical persona is its own agent with a dedicated retriever, calling `search_case_knowledge` and `web_search` on demand.
Made **scope of practice a schema, not a prompt warning** a `ScopeAwareReferral` structured output makes each agent reason about what it's qualified to answer and refer out.
Built the release gate: **groundedness and faithfulness scoring, tool-call accuracy, trajectory evals with an LLM judge**.
- **[Support Genie - Privacy-First RAG Assistant](https://github.com/Anusha-raju/agentic-rag-support.git)** → Fully offline RAG on **Llama 3 (Ollama)** over a hand-written vector store. No API key, no egress for runbooks and incident history that can't leave the building.
- **[Marketing Incrementality Platform](https://github.com/Anusha-raju/marketing-intelligence-platform.git)** → Causal lift measurement across ~99K customers: propensity modeling, A/B evaluation and **IPTW**, which showed the naive campaign lift was overstated by **~2.7×**.
- **[GearGuide](https://github.com/Anusha-raju/GearGuidev2.git)** → Graph-grounded RAG with Neo4j, hybrid retrieval and re-ranking for multi-step diagnostic reasoning.
- **[Human Activity Recognition](https://github.com/Anusha-raju/Human-Activity-Recognition.git)** → LRCN-based activity classification from video.

---

## 🔬 Research & Hackathons

- 🎤 **Badge Summit 2025** - presented *"Skills Are the Common Language"* to 150+ attendees.
- 🛠 **GearGuide (DevNetwork AI+ML Hackathon 2025)** - graph-powered RAG for automotive troubleshooting, built in 48 hours.
- 🌍 **UN Open Source Hackathon 2025** - geospatial analysis of hazards affecting children.
- 🎮 **HoyaHacks 2025 (Microsoft track)** - real-time coding game for classrooms.
- 📊 **World Bank DataDive 2024** - jobs and firm productivity analysis with DataKind DC.

---

## 📚 Education

🎓 **M.S. Data Science** - George Washington University *(2026, GPA 3.91/4.0)*

🎓 **B.E. Computer Science & Engineering** - VTU, Bengaluru

---

## 🏆 Achievements

- 🌟 **Global Leaders Scholarship Award** (2024-25), GWU.
- 🌟 Consistent 3.9+ GPA across the M.S. Data Science program.
- 🌟 Open-source LAiSER extract-module used by workforce researchers beyond GWU.

---

## 📫 Connect with Me

🌐 [Portfolio](https://anusha-umashankar.vercel.app/) •
💼 [LinkedIn](https://linkedin.com/in/anusha-umashankar) •
📧 [Email](mailto:anusha.u.raju@gmail.com) •
💻 [GitHub](https://github.com/Anusha-raju)

✨ *"Human, not a bot - but building them."*
