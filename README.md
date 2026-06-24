<h1 align="center">Yash Karecha</h1>

<p align="center">
  <strong>AI/ML Systems Engineer</strong><br/>
  <em>High-Performance Inference • Distributed Agentic Pipelines • Systems Programming</em><br/>
  Bengaluru, IN
</p>

<p align="center">
  <a href="https://linkedin.com/in/yash-karecha">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:yash.karecha@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/coeusyk">
    <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

---

## ⚡ Engineering Focus

* **Inference Optimization:** Architecting high-throughput, low-latency LLM serving layers utilizing vLLM, PagedAttention, and custom quantization strategies.
* **Agentic Workflows & RAG:** Building production-grade Model Context Protocol (MCP) servers, multi-agent orchestrations, and context-aware local retrieval systems.
* **Performance Systems:** Developing low-level state representations (Bitboards) and parallelized search algorithms in Java and Rust.

---

## 🔨 Featured Systems & Architecture

| Project | Core Architecture & Capabilities | Engineering Decisions & Impact |
|:---|:---|:---|
| [**Vex (Chess Engine)**](https://github.com/coeusyk/chess-engine) | Modular bitboard engine using Alpha-Beta search, Lazy SMP parallelization, and Syzygy tablebase integration (~2000 Elo). | Optimized evaluation via **Adam-based Texel tuning** over 820 parameters across 725k positions. Achieved a statistically significant **$+185.7 \pm 54.2$ Elo gain** validated via Sequential Probability Ratio Testing (SPRT). |
| [**inference-x**](https://github.com/coeusyk/inference-x) | Self-hosted, vLLM-backed inference server with an OpenAI-compatible API, model registry, SSE streaming, and a Textual TUI. | Selected **vLLM over native Hugging Face Transformers** to leverage PagedAttention, significantly improving memory efficiency and generation throughput during concurrent streaming. |
| [**personal-notes-assistant**](https://github.com/coeusyk/personal-notes-assistant) | Local-first, MCP-compliant RAG server indexing markdown knowledge bases into Milvus with pluggable LLM backends and live FS watching. | Implemented the **Model Context Protocol (MCP)** architecture to turn a local vector database into an autonomous tool accessible by Claude Desktop. |
| [**OpenCast**](https://github.com/coeusyk/opencast) | High-throughput data pipeline orchestrating ARIMA/Holt-Winters time-series forecasting over 498 ECO opening codes. | Built a hybrid stack: a **multi-threaded Rust fetcher** for maximum throughput against the Lichess API paired with a **Python/statsmodels engine** for statistical forecasting. |
| [**chronicle-n8n**](https://github.com/coeusyk/chronicle-n8n) | Private, automated RSS ingestion and summarization engine streaming to a self-cleaning Notion data warehouse. | Orchestrated a zero-ingress cost, fully local pipeline by embedding **Ollama (llama3)** inside an asynchronous workflow to maintain total data privacy. |

---

## 🧰 Tech Stack

### 💻 Systems & Languages
`Python` • `Java` • `Rust` • `TypeScript` • `JavaScript` • `SQL` • `HTML/CSS`

### 🧠 LLM Infrastructure & Agentic Frameworks
`vLLM` • `LangGraph` • `CrewAI` • `Model Context Protocol (MCP)` • `LlamaIndex` • `OpenAI Agents SDK` • `LangChain` • `Ollama`

### 📊 Machine Learning & Data Engineering
`PyTorch` • `TensorFlow` • `scikit-learn` • `pandas` • `NumPy` • `statsmodels` • `Milvus` • `ChromaDB` • `MongoDB` • `MySQL`

### ⚙️ DevOps & Tooling
`Docker` • `GitHub Actions` • `n8n` • `Supabase` • `Git` • `Postman` • `Figma`

---

## 📊 Core Performance Metrics

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=coeusyk&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)
