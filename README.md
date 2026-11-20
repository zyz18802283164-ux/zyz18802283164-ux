<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Cascadia+Code&weight=700&size=17&color=0078D7&center=true&pause=100000&lines=Hi,+I'm+Yaozong+Zheng.+A+Backend+Engineer" alt="Hi"/>
  <p>
    <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="28px" height="28px"/>
    <strong>I'm currently focused on RAG &amp; Multi-Agent systems and open to job opportunities.</strong>
  </p>
  <p><strong>📮 Reach me: <a href="mailto:2363959478@qq.com">2363959478@qq.com</a></strong></p>
  <p>
    <code>🎓 Master's Student</code>
    <code>📍 China</code>
  </p>
</div>
<table>
<tr>
<td valign="top" width="50%">

### 🧭 Work Experience

<strong>CCTC</strong> -- <code>Backend Engineer · AI Application</code> -- <code>2025.9 ~ Present</code>

Responsible for the architecture and development of core AI pipelines on the urban health-check AI platform: RAG retrieval, multi-agent orchestration, streaming interaction, and Java / Python microservice governance.

<!-- 有新的真实工作/实习经历，按上面格式在此追加 -->

</td>
<td valign="top" width="48%">

### 🌟 Skills & Honors

**Backend**

`Java` `Spring Boot` `MyBatis-Plus` `MySQL` `Redis`

**AI / LLM Applications**

`Python` `FastAPI` `RAG` `LangGraph` `Chroma`

**Frontend & DevOps**

`Vue` `Docker` `Linux` `Git`

**🏆 Honors & Certificates / 荣誉证书**

- 📜 Software Designer (Intermediate) / 软件设计师 · 软考中级
- 🎖️ Graduate Academic Scholarship (1st & 2nd Prize) / 研究生学业奖学金 · 一等奖 / 二等奖

> 🚀 Keep exploring LLM applications & Agent engineering

</td>
</tr>
</table>

## 📦 Project Experience

**城市体检 AI 助手与报告自动生成平台 / Urban Health-Check AI Assistant & Report Generation Platform** — A RAG + multi-agent driven long-form report generation system

<code>Spring Boot</code> <code>FastAPI</code> <code>LangGraph</code> <code>Chroma</code> <code>Redis</code> <code>MySQL</code>

- 🎯 **S/T**: Urban health-check data is multi-source and heterogeneous, indicator interpretation heavily relies on domain experts, and manual drafting is slow with unstable quality — the goal was to build an end-to-end automated "data → retrieval → generation → review" report pipeline
- 🏗️ **A · Architecture**: Designed the Java / Python microservice split — Spring Boot handles business, permissions and sessions (15+ business modules, serving both Web and mini-program clients), while FastAPI hosts compute-intensive AI pipelines, independently deployable and scalable
- 🔍 **A · RAG**: Implemented hybrid retrieval — Chroma vector semantic recall + Whoosh BM25 exact match, combined with multi-query generation and reranking to balance recall and precision; built an async Mineru "parse → chunk → embed" pipeline for large-scale document ingestion
- 🤖 **A · Agent**: Orchestrated a five-agent LangGraph state graph (task decomposition → data analysis → indicator interpretation → report writing → quality review & scoring), with a review-rewrite loop, model-tier routing and fallback chains to safeguard long-form report quality
- 📡 **A · Interaction**: Designed an SSE + WebSocket dual-channel streaming protocol with 8 message types (step / thinking / content / review, etc.) for real-time generation feedback
- 🏁 **R**: Delivered full-pipeline automated report generation from multi-source data to final drafts; iterative review-rewrite loops markedly improved drafting efficiency and quality stability <!-- 有真实量化数据（效率提升 X% 等）告诉我，我补进去 -->

**老年人智能疗程用药提醒系统 / Elderly Medication Reminder System** (Independent Project · [elder](https://github.com/zyz18802283164-ux/elder))

<code>Spring Boot</code> <code>MyBatis-Plus</code> <code>MySQL</code> <code>Vue</code> <code>JWT</code>

- Independently designed and implemented 10 business modules — patients, medicines, treatment plans, medication records, etc. — in a front-end / back-end separated architecture
- Covered the full workflow: health records, risk alerts, emergency contacts / SOS, and a statistics dashboard
- JWT-based authentication, unified response wrappers, and a standard Controller → Service → Mapper layered architecture

<!-- 有新的真实项目，按上面格式在此追加 -->
