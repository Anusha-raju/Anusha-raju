<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F3864,100:2D6A5F&height=180&section=header&text=Anusha%20Umashankar&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Applied%20AI%20Engineer%20%C2%B7%20Agents%20%C2%B7%20Retrieval%20%C2%B7%20Evals&descSize=18&descAlignY=58" alt="Anusha Umashankar" />
</p>

<p align="center">
  <a href="https://anusha-umashankar.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2D6A5F&center=true&vCenter=true&width=640&lines=I+build+AI+agents+for+messy+enterprise+data;...and+the+evals+that+keep+them+honest.;Evals+before+features.+A+trace+on+every+run.;Structured+outputs%2C+not+prompt+warnings." alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://anusha-umashankar.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-1F3864?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/anusha-umashankar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:anusha.u.raju@gmail.com"><img src="https://img.shields.io/badge/Email-2D6A5F?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Washington%2C%20DC-4A5568?style=flat-square&logo=googlemaps&logoColor=white" alt="Washington, DC" />
  <img src="https://img.shields.io/badge/Open%20to-Applied%20AI%20roles-3FCF8E?style=flat-square" alt="Open to Applied AI roles" />
</p>

---

### 👋 Hi, I'm Anusha

Three years of NLP and LLM work in production. These days that means **LangGraph agents that call retrieval tools when they need them**, plus the **tracing and eval loop** that tells me a change made things worse before a user does.

My habits: evals before features · a trace on every run · structured outputs instead of prompt warnings · cost and latency on the dashboard from day one.

---

### 🧭 How I build an agent

```mermaid
flowchart LR
    U([User query]) --> A{Agent<br/>LangGraph}
    A -- needs context --> R[(Hybrid retrieval<br/>BM25 + dense)]
    A -- needs fresh facts --> W[Web search tool]
    R --> A
    W --> A
    A --> S[Structured output<br/>schema-validated]
    S --> G{Eval gate<br/>groundedness · tool-call accuracy}
    G -- pass --> O([Answer + citations])
    G -- fail --> A
    A -.-> T[[Trace · cost · latency]]
```

---

### 🚀 Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/theschoolofai/era-v5-lab">ERA V5 Lab · Benchmark decontamination</a></h4>
      Hardened integrity checks for a decontamination pipeline covering <b>126K+ eval items</b> and <b>7.8M n-gram fingerprints</b> across 13 LLM benchmarks. Added a manifest-to-SHA-256 consistency check, a regression test, and 6 missing benchmarks to the registry.
      <br/><br/>
      <img src="https://img.shields.io/badge/LLM%20Evaluation-6A4C93?style=flat-square" /> <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" /> <img src="https://img.shields.io/badge/SHA--256-1C3C3C?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://bridge.arc.gwu.edu/">BRIDGE</a></h4>
      Multi-agent clinical training platform. Each persona is its own <b>LangGraph agent</b> with a dedicated retriever, calling <code>search_case_knowledge</code> and <code>web_search</code> on demand. A <code>ScopeAwareReferral</code> schema makes scope of practice a structured output, not a prompt warning.
      <br/><br/>
      <img src="https://img.shields.io/badge/LangGraph-121212?style=flat-square" /> <img src="https://img.shields.io/badge/Tool--calling%20RAG-2D6A5F?style=flat-square" /> <img src="https://img.shields.io/badge/LLM--as--Judge-4A5568?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Anusha-raju/agentic-rag-support">Support Genie</a></h4>
      Privacy-first, fully offline RAG on <b>Llama 3 via Ollama</b> over a hand-written vector store. No API key and no egress, for runbooks and incident history that can't leave the building.
      <br/><br/>
      <img src="https://img.shields.io/badge/Ollama-111111?style=flat-square" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/Anusha-raju/GearGuidev2">GearGuide</a></h4>
      Graph-grounded RAG for automotive troubleshooting. A <b>Neo4j</b> graph captures part relationships that vector search misses, and <b>hybrid retrieval with re-ranking</b> handles domain terminology for multi-step diagnostic reasoning. Built in <b>48 hours</b> at the DevNetwork AI+ML Hackathon.
      <br/><br/>
      <img src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" /> <img src="https://img.shields.io/badge/Hybrid%20Retrieval-2D6A5F?style=flat-square" /> <img src="https://img.shields.io/badge/LangChain-0A0A0A?style=flat-square" />
    </td>
  </tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

- **[Marketing Incrementality Platform](https://github.com/Anusha-raju/marketing-intelligence-platform)**: causal lift measurement across ~99K customers. Propensity modeling plus IPTW showed the naive campaign lift was overstated by ~2.7×.
- **[Human Activity Recognition](https://github.com/Anusha-raju/Human-Activity-Recognition)**: LRCN-based activity classification from video.
- **[BPE Tokenizer](https://github.com/Anusha-raju/BPE-tokenizer)** · **[Training Loop](https://github.com/Anusha-raju/Training-loop)** · **[Loss Harness](https://github.com/Anusha-raju/loss_harness)**: from-scratch building blocks for LLM training.

</details>

</details>

---

### 💼 Experience

<details open>
<summary><b>Instructional Technologist, AI/ML Infrastructure</b> · GWU Data Science · <i>Aug 2026 – Present</i></summary>
<br/>

- Building an **advising assistant** with hybrid dense + sparse retrieval grounded in program documentation, so students get cited answers instead of generic ones.
- Run the **AWS ML environments** (EC2, S3, IAM, cost controls) for graduate capstone teams; containerized workspaces took setup from days to hours.
- Scope and de-risk applied AI capstones with faculty and industry sponsors.

</details>

<details>
<summary><b>Research Assistant</b> · LAiSER, GWU · <i>Feb 2025 – May 2026</i></summary>
<br/>

- **FAISS-based similarity search** over 10,000+ job descriptions, mapped to the **ESCO** and **O\*NET** skill taxonomies with a Neo4j graph for cross-taxonomy alignment.
- Shipped it as a **multi-tenant API on AWS** (FastAPI, Lambda, S3, EC2) with Docker and GitHub Actions CI/CD: **3× research throughput**, and time-to-demo from weeks to a live public product.
- Presented the architecture to **150+ attendees at Badge Summit 2025**.

</details>

<details>
<summary><b>Machine Learning Engineer</b> · Ideapoke (now Chesz.ai) · <i>May 2022 – Nov 2023</i></summary>
<br/>

- Rebuilt the NER pipeline behind **Signalz**, which turns news, patents and papers into market and technology signals: **+40% extraction accuracy, −60% processing time**.
- Replaced brittle rule-based extraction with **RAG (LangChain + GPT)** producing structured output from large-scale unstructured web data.
- Built a contextual search engine that retrieved on **query intent rather than keyword match**, across 30+ industries.

</details>

---

### 🔧 Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=python,ts,postgres,pytorch,sklearn,fastapi,docker,aws,githubactions,nextjs,react,supabase&perline=12" alt="Core stack" />
</p>

| | |
|---|---|
| **Agents & retrieval** | LangGraph · LangChain · MCP · Hybrid retrieval (BM25 + dense) · Ollama · Neo4j · FAISS · pgvector |
| **Evals & LLMOps** | LangSmith · Langfuse · RAGAS · LLM-as-Judge · Pytest |
| **ML & NLP** | PyTorch · Hugging Face Transformers · scikit-learn · XGBoost · causal inference (IPTW) |

---

### 📊 GitHub activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Anusha-raju&theme=transparent&hide_border=true&ring=2D6A5F&fire=2D6A5F&currStreakLabel=2D6A5F" alt="GitHub streak" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Anusha-raju&bg_color=00000000&color=2D6A5F&line=2D6A5F&point=1F3864&area=true&area_color=2D6A5F&hide_border=true" alt="Contribution graph" />
</p>

---

### 🏅 Recognition & education

- 🎤 **Badge Summit 2025**: presented *"Skills Are the Common Language"* to 150+ attendees.
- 🛠 **DevNetwork AI+ML Hackathon 2025**: GearGuide, graph-powered RAG for automotive troubleshooting, in 48 hours.
- 🌍 **UN Open Source Hackathon 2025** · 🎮 **HoyaHacks 2025** (Microsoft track) · 📊 **World Bank DataDive 2024** with DataKind DC
- 🌟 **Global Leaders Scholarship**, GWU (2024–25)
- 🎓 **M.S. Data Science**, George Washington University (2026, GPA 3.91) · **B.E. Computer Science**, VTU Bengaluru

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2D6A5F,100:1F3864&height=110&section=footer&text=Human,%20not%20a%20bot%20%E2%80%94%20but%20building%20them.&fontSize=18&fontColor=ffffff&fontAlignY=70" alt="Footer" />
</p>
