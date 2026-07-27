<div align="center">
  <h1>Mohamad Meri</h1>
  <h3>Backend & Data Engineer | Python Architecture, AI Agents, and ETL Pipelines</h3>
  <p>📍 Currently based in Beirut, Lebanon • Open to relocation.</p>
  
  <a href="https://linkedin.com/in/mohamadmeri">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://mohamadmeri.pages.dev">
    <img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  &nbsp;
  <a href="mailto:mohamad-meri@outlook.com">
    <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email"/>
  </a>
</div>

---

### 👨‍💻 About Me

Software Engineer with ~4 years of professional experience focusing on backend development, data engineering, and autonomous AI agents. I build cleanly designed, production grade systems instead of quick scripts. 

My technical approach relies on strict boundaries, data accuracy, and deterministic execution. Whether I am designing a multi stage LLM compiler pipeline that guarantees zero math errors, or architecting a Flask backend with Hexagonal Architecture and property based testing, I prioritize maintainability and business impact. I enjoy taking complex, messy data systems and turning them into reliable software solutions.

---

### 🛠️ Tech Stack Grid

<table>
  <tr>
    <td valign="top" width="25%" align="center">
      <b>Languages</b><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/><br/><br/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/><br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/><br/><br/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"/>
    </td>
    <td valign="top" width="25%" align="center">
      <b>Frameworks</b><br/><br/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/><br/><br/>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/><br/><br/>
      <img src="https://img.shields.io/badge/Pydantic_V2-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic"/><br/><br/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
    </td>
    <td valign="top" width="25%" align="center">
      <b>Cloud & Databases</b><br/><br/>
      <img src="https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/><br/><br/>
      <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare"/><br/><br/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS"/><br/><br/>
      <img src="https://img.shields.io/badge/Qdrant-DC382D?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant"/>
    </td>
    <td valign="top" width="25%" align="center">
      <b>Tools & DevOps</b><br/><br/>
      <img src="https://img.shields.io/badge/uv-DE5DD9?style=flat-square&logo=uv&logoColor=white" alt="uv"/><br/><br/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions"/><br/><br/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/><br/><br/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
    </td>
  </tr>
</table>

---

### 🚀 Featured Projects

<table>
  <tr>
    <td>
      <a href="https://github.com/mohamadmeri/scrygent"><b>🔹 Scrygent</b></a> &nbsp; <img alt="Status" src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square">
      <br/><br/>
      <b>The Problem:</b> Standard LLM agents use unrestricted Python code generation for data analysis. This causes math errors and severe security risks.<br/><br/>
      <b>Architecture & Challenges:</b> Built a 2 Pass LLM Compiler Pipeline that separates LLM reasoning from JSON syntax formatting. It translates natural language into a strict Pydantic Intermediate Representation (IR), making the LLM act only as a logic planner. A deterministic Pandas and NumPy backend handles all the actual execution. This design cut API token usage by over 50%. I also added dynamic LLM routing to send complex reasoning to large 120B/70B models and strict JSON formatting to smaller 8B models.<br/><br/>
      <b>Core Stack:</b> Python, LangGraph, Pydantic V2, Pandas, NumPy, LangSmith.
    </td>
  </tr>
  <tr><td><br/></td></tr>
  <tr>
    <td>
      <a href="https://github.com/mohamadmeri/resin-etl"><b>🔹 Resin ETL</b></a> &nbsp; <img alt="Status" src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square">
      <br/><br/>
      <b>The Problem:</b> A plastics manufacturer had 8 months of messy Excel workbooks tracking material substitutions, with no way to see if the process was profitable or losing money.<br/><br/>
      <b>Architecture & Challenges:</b> Built a multi stage Python ETL pipeline that fixed a critical data bug where Excel formatting broke the alignment between substitution logs and blend data. Consolidated 8 monthly workbooks into 7 standard summary tables and deployed 7 interactive Plotly dashboards to Cloudflare Pages.<br/><br/>
      <b>Metrics:</b> Analyzed 1,880 substitution events, proving an 80.9% cost saving success rate. Found that machines 18, 84, and 38 caused 92% of machine attributed cost increases.<br/><br/>
      <b>Core Stack:</b> Python, Pandas, NumPy, Plotly, Cloudflare Pages.
    </td>
  </tr>
  <tr><td><br/></td></tr>
  <tr>
    <td>
      <a href="https://github.com/mohamadmeri/styx"><b>🔹 Styx</b></a> &nbsp; <img alt="Status" src="https://img.shields.io/badge/Status-Local_Refactor_WIP-orange?style=flat-square">
      <br/><br/>
      <blockquote>Note: Styx is currently undergoing a major local refactor to Hexagonal Architecture. The GitHub repo may not show the latest code temporarily.</blockquote><br/>
      <b>The Problem:</b> Fitness apps struggle to balance global default data with user custom data without causing database issues or compromising integrity.<br/><br/>
      <b>Architecture & Challenges:</b> Built a workout periodization engine using Hexagonal (Clean) Architecture and strict boundary enforcement. Created an "Extensible Catalog Pattern" using optimized OR queries and Composite Unique Constraints to merge global defaults with private user items in one database hit. Secured the API boundary with a "Pydantic Firewall" to prevent mass assignment, NIST compliant password hashing, and GDPR compliant account deletion.<br/><br/>
      <b>Core Stack:</b> Python 3.13, APIFlask, SQLAlchemy 2.0, Pydantic V2, uv, Alembic.
    </td>
  </tr>
</table>

---

### 📊 Dynamic Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohamadmeri&show_icons=true&theme=vue-dark&hide_border=true&count_private=true&include_all_commits=true" alt="Mohamad's GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamadmeri&layout=compact&theme=vue-dark&hide_border=true&langs_count=8&count_private=true" alt="Top Languages" />
</div>
