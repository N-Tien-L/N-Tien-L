<h1 align="center">Hi, I'm Lam Nhat Tien 👋</h1>

<h3 align="center">Software Engineering Student @ PTIT · Backend-focused · Exploring LLM applications</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/tien-lam-946a69371/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:tienlamnhatt@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### 🧭 About Me

- 🎓 Final-year **Software Engineering** student at **PTIT** (Posts and Telecommunications Institute of Technology), Ho Chi Minh City · GPA **3.64/4.0**
- 💻 Growing toward **backend engineering**: mostly **Java and Spring Boot**, with a focus on concurrency, data consistency and access control
- 🤖 Exploring **LLM applications** and retrieval on top of solid backend foundations
- 🌍 One of 10 PTIT students selected for an international industry project at **Howest, Belgium** (grade 17/20)
- 🏆 First Prize, ICPC PTIT HCMC Campus Contest 2025 · TOEIC 920
- 🎯 Looking for a **Software Engineering / Backend internship**

---

### 🚀 Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🐭 <a href="https://github.com/MatteoDiCelmo/CQ_Project_Team_2">CQ – Intelligent IVC Cage Monitoring</a></h4>
      <p><em>Howest University of Applied Sciences · team of 4 · May–Jun 2026 · grade 17/20</em></p>
      <ul>
        <li>Designed a <b>multi-agent LLM reporting pipeline</b>: behavioural and metabolic agents run concurrently via asyncio, then report synthesis and Chinese translation (Groq-hosted Llama 3.3 70B)</li>
        <li>Implemented an <b>async worker</b> for hourly per-mouse anxiety scores with stress alerts and idempotent PostgreSQL upserts</li>
        <li>Developed a report-grounded chat assistant with persisted sessions</li>
      </ul>
      <sub>Python · FastAPI · asyncio · PostgreSQL/TimescaleDB · pytest</sub>
    </td>
    <td width="50%" valign="top">
      <h4>📑 <a href="https://github.com/N-Tien-L/SOPilot">SOPilot V2</a></h4>
      <p><em>Vietnamese/English Q&amp;A over company procedures · personal · in progress</em></p>
      <ul>
        <li>Designed <b>tenant isolation</b> for a Spring Boot API: Google ID-token login, just-in-time workspaces and <b>PostgreSQL Row-Level Security</b></li>
        <li>Designed a Python ingestion and <b>hybrid-retrieval</b> service: Docling parsing with source offsets, structure-aware chunking, a <code>FOR UPDATE SKIP LOCKED</code> job queue, pgvector + BM25 fused by RRF</li>
      </ul>
      <sub>Java · Spring Boot · Python · FastAPI · PostgreSQL (pgvector, RLS) · Docling</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>💬 <a href="https://github.com/N-Tien-L/ChatMee">ChatMee</a> · <a href="https://chat-mee-wine.vercel.app/">live demo</a></h4>
      <p><em>Real-time chat platform · personal · Sep 2025 – present</em></p>
      <ul>
        <li>Designed an atomic <b>Redis Lua presence registry</b> for STOMP sessions: reconnect grace, lease-based cleanup of crashed instances, events only on real state transitions</li>
        <li>Designed <b>capacity-safe room joins</b> on PostgreSQL: a 20-thread test at capacity 10 yields exactly 10 joins</li>
        <li>Designed <b>WebSocket auth</b> with 60 s single-use Redis tokens and a live membership re-check on every outbound frame</li>
      </ul>
      <sub>Spring Boot · OAuth2 · WebSocket/STOMP · Redis · PostgreSQL · JUnit · Testcontainers</sub>
    </td>
    <td width="50%" valign="top">
      <h4>⚖️ Temporal Legal KG &amp; GraphRAG for Vietnamese Law</h4>
      <p><em>Ongoing research · manuscript in preparation (code not public)</em></p>
      <ul>
        <li>Designed a temporal provision-level knowledge graph and a hybrid GraphRAG (dense + BM25 + graph) that excludes repealed or superseded provisions</li>
        <li>Building the graph-construction stage: regex + fine-tuned <b>PhoBERT</b> BIO-tagging cascade for amendment and repeal relations</li>
        <li>Leakage-guarded evaluation harness (fail-closed splits, cluster bootstrap CIs)</li>
      </ul>
      <sub>Python · PyTorch · Hugging Face Transformers · PhoBERT</sub>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack

**Backend**
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
</p>

**Data**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

**Testing & Tools**
<p>
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Testcontainers-2E7D32?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

**AI / NLP**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

---

<p align="center"><em>Thanks for stopping by! Feel free to reach out about backend engineering or internship opportunities.</em></p>
