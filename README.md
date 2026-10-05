<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,35:1e3a8a,70:2563eb,100:10b981&height=220&section=header&text=Sajjarao%20Pavan%20Krishna&fontSize=42&fontColor=ffffff&desc=AI%20Engineer%20%7C%20Multi--Agent%20Orchestration%20%E2%80%A2%20Production%20RAG%20%E2%80%A2%20Cognitive%20Systems&descFontSize=16&descAlignY=68&animation=fadeIn" alt="Header Banner" width="100%" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/sajjaraopavankrishna"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pavankrishna048@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Pavan048"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

### 👨‍💻 Who I Am

I am an **AI Engineer (SDE 1)** at **Exto** in Bengaluru, architecting and shipping production-grade **multi-agent systems**, **adaptive RAG pipelines**, and **self-improving conversational agents** for multi-tenant enterprise products.

> 💡 *Note: Most of my day-to-day engineering and production commits live in private enterprise repositories at Exto. This personal GitHub space highlights my open-source cognitive architectures, production RAG frameworks, and multi-agent systems.*

---

### 🧠 Core Engineering Focus

- 🤖 **Multi-Agent Orchestration & ReAct Patterns**: Decomposing complex, multi-step queries into targeted subtasks routed across specialist agent nodes (retrieval, summarization, extraction) with shared state checkpointing via **LangGraph**.
- 🔌 **Model Context Protocol (MCP) & Tool Extensibility**: Standardizing tool execution, dynamic function calling, and external API integration across agents without hardcoding brittle glue logic into the core agent loop.
- 🔄 **Production RAG & Hybrid Retrieval**: Engineering high-precision retrieval engines combining dense semantic search + sparse BM25 (BGE-M3) fused through **Reciprocal Rank Fusion (RRF, k=60)**, cross-encoder rerankers, and Corrective RAG (CRAG) quality gating.
- 📑 **Hierarchical Context Management**: Implementing small-to-large chunk expansion—indexing pinpoint 512-token chunks for vector accuracy, but dynamically injecting full parent sections into generation context to eliminate semantic cliffing.
- 💾 **Two-Tier Cognitive Agent Memory**: Designing persistent memory layers pairing fast in-memory session caching (**Redis**) with long-term episodic vector storage (**Qdrant**) so agents retain context across sessions and self-improve from feedback.
- 🛡️ **Evals, Guardrails & Observability**: Building rigorous evaluation harnesses to measure query agent accuracy, relevance, and hallucinations, alongside per-stage latency tracing with **Opik**.
- ⚡ **Production Backend & SSE Streaming**: Writing high-throughput REST and streaming services in **Python**, **Go**, and **FastAPI** with token budgeting, chunk deduplication, and multi-tenant isolation.

---

### 🛠️ Technical Arsenal

<table>
  <tr>
    <td width="24%" valign="top"><strong>Agentic AI & Orchestration</strong></td>
    <td>
      <img src="https://img.shields.io/badge/LangGraph-State_Machines-FF6F00?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
      <img src="https://img.shields.io/badge/LangChain-Orchestration-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
      <img src="https://img.shields.io/badge/MCP-Model_Context_Protocol-8A2BE2?style=flat-square" alt="MCP" />
      <img src="https://img.shields.io/badge/ReAct-Multi--Agent_Pattern-purple?style=flat-square" alt="ReAct" />
      <img src="https://img.shields.io/badge/Agent_Memory-Short_%26_Long_Term-blueviolet?style=flat-square" alt="Memory" />
      <img src="https://img.shields.io/badge/Self--Improving_Agents-Production-indigo?style=flat-square" alt="Self-Improving" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>RAG & Retrieval</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Hybrid_Search-Dense_%2B_Sparse_%2B_RRF-2563EB?style=flat-square" alt="Hybrid Search" />
      <img src="https://img.shields.io/badge/CRAG-Corrective_RAG-blue?style=flat-square" alt="CRAG" />
      <img src="https://img.shields.io/badge/Reranking-BGE_Cross--Encoder-orange?style=flat-square" alt="Reranker" />
      <img src="https://img.shields.io/badge/Semantic_Caching-Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Semantic Caching" />
      <img src="https://img.shields.io/badge/Docling-Multimodal_Parser-6366F1?style=flat-square&logo=ibm&logoColor=white" alt="Docling" />
      <img src="https://img.shields.io/badge/Hierarchical_Chunking-Small_to_Large-10B981?style=flat-square" alt="Hierarchical Chunking" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>LLM Frameworks & Evals</strong></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI_SDK-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
      <img src="https://img.shields.io/badge/Google_Gemini_SDK-4285F4?style=flat-square&logo=google&logoColor=white" alt="Gemini" />
      <img src="https://img.shields.io/badge/LiteLLM-Universal_Gateway-black?style=flat-square" alt="LiteLLM" />
      <img src="https://img.shields.io/badge/Opik-LLM_Tracing-teal?style=flat-square" alt="Opik" />
      <img src="https://img.shields.io/badge/Guardrails_%26_Evals-Hallucination_Checks-green?style=flat-square" alt="Guardrails" />
      <img src="https://img.shields.io/badge/Streaming-SSE-009688?style=flat-square" alt="SSE" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Databases & Vectors</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Qdrant-Vector_Database-DC2626?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant" />
      <img src="https://img.shields.io/badge/Redis-In--Memory_Store-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      <img src="https://img.shields.io/badge/MongoDB-Document_Store-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      <img src="https://img.shields.io/badge/PostgreSQL-Relational_DB-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Backend & Systems</strong></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
      <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
      <img src="https://img.shields.io/badge/REST_APIs-005571?style=flat-square" alt="REST" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>DevOps & Tooling</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
      <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" alt="VS Code" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
    </td>
  </tr>
</table>

---

### 🚀 Featured Production Architecture

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Pavan048/CITE-RAG">📚 CITE-RAG</a></h3>
      <p>A production-grade RAG platform built for zero-hallucination citation enforcement and multi-document reasoning.</p>
      <ul>
        <li><strong>LangGraph Multi-Hop Loop:</strong> Iterative sub-query decomposition, sufficiency grading, and dynamic follow-up reformulation.</li>
        <li><strong>Two-Stage Hybrid Search:</strong> Dense + Sparse (BGE-M3) fused via RRF (k=60), backed by Cross-Encoder reranking.</li>
        <li><strong>Hierarchical Chunking:</strong> Small 512-token search units expanded to full parent sections for generator context.</li>
        <li><strong>Enforced Citations:</strong> Sentence-level <code>[doc:page:chunk]</code> tokens verified against actual context; unverified claims are dropped.</li>
        <li><strong>Zero-Retention BYOK:</strong> Request-scoped keys residing strictly in RAM.</li>
      </ul>
      <p><em>Tech: Python, FastAPI, LangGraph, Qdrant, MongoDB, Docling, React 19</em></p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 Multi-Agent Research Assistant</h3>
      <p>An enterprise ReAct-pattern multi-agent orchestration system decomposing broad inquiries across specialist sub-agents.</p>
      <ul>
        <li><strong>Orchestrator-Worker Architecture:</strong> Decomposes complex prompts into retrieval, summarization, and web-search subtasks.</li>
        <li><strong>Dual-Layer Memory:</strong> Session-level short-term context (Redis) + long-term episodic retrieval (Qdrant).</li>
        <li><strong>LangGraph State Checkpointing:</strong> Resilient state persistence across asynchronous human-in-the-loop cycles.</li>
        <li><strong>MCP Extensibility:</strong> Model Context Protocol tool interfaces allowing seamless integration of new tool capabilities.</li>
      </ul>
      <p><em>Tech: Python, LangGraph, LangChain, Qdrant, Redis, FastAPI, MCP</em></p>
    </td>
  </tr>
</table>

---

### 📬 Connect & Collaborate

I'm always keen to exchange notes with engineers building in the agentic AI, multi-agent orchestration, and enterprise RAG spaces:

- 💼 **LinkedIn**: [linkedin.com/in/sajjaraopavankrishna](https://linkedin.com/in/sajjaraopavankrishna)
- 📧 **Email**: [pavankrishna048@gmail.com](mailto:pavankrishna048@gmail.com)
- 📍 **Location**: Bengaluru, Karnataka, India
