<p align="center">
  <h1 align="center">Mohamad Meri</h1>
  <h3 align="center">Software Engineer | Backend & AI Systems Architect</h3>
  <p align="center">
    <em>Building robust and scalable systems, not brittle scripts.</em><br>
    📍 Beirut, Lebanon | 🌍 Open to Global Remote & Relocation
  </p>
</p>

<p align="center">
  <a href="https://mohamadmeri.pages.dev"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/mohamadmeri"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mohamad-meri@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
</p>

<br>

### 👋 About Me
I am a Software Engineer specializing in backend architecture, data engineering, and autonomous AI systems. My work focuses on translating complex business problems into robust technical solutions. I prioritize strict data validation, clear architectural boundaries, and measurable business impact. Whether I am engineering a deterministic AI compiler or building production ETL pipelines that drive executive strategy, my goal is always to write testable and maintainable code.

<br>

### 🛠️ Tech Stack & Tooling

<table align="center">
  <tr>
    <td align="center" width="20%"><b>🧠 Languages</b></td>
    <td align="center" width="80%">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>⚙️ Backend</b></td>
    <td align="center">
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/APIFlask-000000?style=flat-square&logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
      <img src="https://img.shields.io/badge/Pydantic_V2-306998?style=flat-square&logo=pydantic&logoColor=white" />
      <img src="https://img.shields.io/badge/REST_API-000000?style=flat-square&logo=fastapi&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>🤖 AI & Data</b></td>
    <td align="center">
      <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=chainlink&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>🛠️ DevOps</b></td>
    <td align="center">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
      <img src="https://img.shields.io/badge/uv-FF6B6B?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Ruff-FFC107?style=flat-square&logo=ruff&logoColor=black" />
    </td>
  </tr>
</table>

<br>

### 🚀 Featured Engineering Projects

#### 🧠 [Scrygent: Deterministic Data Compiler & Agentic Analytics](https://scrygent.netlify.app/)
*The Problem:* Standard ReAct agents hallucinate on numerical computations and pose severe security risks via unbounded code execution.
* **System Architecture:** Engineered a 2-Pass LLM Compiler that strictly decouples logical reasoning from JSON syntax formatting. The system translates natural language into a strict Pydantic V2 Intermediate Representation (IR). A deterministic Pandas and NumPy backend handles all physical execution. The LLM decides what to compute and the engine decides how.
* **Zero-Knowledge Profiling:** Built a deterministic pre-flight profiler that extracts regex skeletons, monotonic ID flags, and exact categorical matches. This grounds the LLM in ground-truth data without flooding the context window.
* **Hermetic State & Safe Math:** Implemented an immutable JSON-safe state boundary using recursive Pydantic validators to scrub C-types into native Python primitives. Replaced unsafe Python `eval()` with `numexpr` for zero-trust mathematical execution.
* **Self-Healing Execution:** Designed an internal correction chain powered by `difflib`. It traps validation errors, uses fuzzy string matching for high-cardinality data, and feeds actionable tracebacks to an isolated LLM loop to repair payloads mid-flight.
* **Core Stack:** `Python` `LangGraph` `Pydantic V2` `Pandas` `NumPy` `Qdrant` `Streamlit`

#### 🏭 [Resin ETL: Industrial Analytics & Executive BI](https://mohamadmeri.github.io/material-variance-engine/)
*The Problem:* A manufacturing client possessed 8 months of siloed and corrupted operational data with no visibility into material substitution profitability.
* **System Architecture:** Engineered a multi-stage Python ETL pipeline to ingest, normalize, and validate 8 operational workbooks. Diagnosed and patched a silent data corruption bug in Excel formatting alignment that was destroying 1:1 data mapping. 
* **Data Modeling:** Designed 7 canonical summary tables and interactive dashboards to provide self-service analytics for non-technical stakeholders.
* **Metrics:** Analyzed 1,880 substitution events and proved 80.9% of substitutions were cost-saving. Identified a Pareto concentration where just 3 machines drove 92% of machine-attributed cost increases. This completely reframed the client strategy.
* **Core Stack:** `Python` `Pandas` `openpyxl` `Plotly` `Cloudflare Pages`

#### 🏗️ Styx: Enterprise-Grade Periodization Engine *(WIP)*
*The Problem:* Fitness applications typically rely on basic CRUD patterns that fail at scale, lack data integrity, and are difficult to test.
* **System Architecture:** Architecting a strict Hexagonal Architecture using a Service-Repository pattern. Features a Pydantic Firewall for mass-assignment prevention and NIST-aligned security with HaveIBeenPwned k-anonymity checks. 
* **Data Integrity:** Implemented GDPR-compliant soft-delete anonymization to preserve historical analytics while removing PII. Utilized an Extensible Catalog Pattern to seamlessly merge global system defaults with user-generated custom items.
* **Status:** Currently undergoing a major local refactor to the modern Python ecosystem (APIFlask, `uv`, Python 3.13). The modernized architecture will be pushed to my primary GitHub upon completion.
* **Core Stack:** `Python` `APIFlask` `SQLAlchemy 2.0` `Pydantic V2` `Hypothesis` `Pytest`

<br>

### 🎯 Current Engineering Focus
- 🔭 Expanding **Scrygent** with advanced Retrieval-Augmented Generation (RAG) and semantic memory replay using Qdrant.
- 🏗️ Refactoring **Styx** to a modern 2026 Python ecosystem (APIFlask, `uv`, Python 3.13 type parameters).
- 📚 Deepening expertise in distributed tracing (LangSmith) and serverless vector databases for autonomous agent architectures.

<br>
