# Abolfazl Afkhami

**Production AI Engineer** specializing in **Speech AI (ASR)**, **Agentic Workflows**, and **High-Throughput RAG Pipelines**.

I engineer production-grade AI infrastructure with a focus on system determinism, low-latency execution, and measurable pipeline trade-offs.

---

### 🏛️ Core Specializations

* **Speech AI & ASR Engineering:** End-to-end dataset processing pipelines (~53 GB to 7.7 GB clean subsets), PyTorch fine-tuning (`whisper-small`), dialect/phoneme adaptation, and Hugging Face deployment.
* **Agentic Workflows & State Engines:** Non-blocking asynchronous orchestration built on n8n state memory, zero-disk I/O in-memory binary processing, and multi-model routing (OpenRouter).
* **Production RAG Systems:** Dynamic vector synchronization (3-hour automated updates), sub-second execution context optimization, and decoupled asynchronous CRM/ERP analytics.

---

### 🚀 Featured Systems & Proof of Work

#### 🎙️ 1. Fine-Tuned Persian Whisper (Houshinoo) — Speech AI / ASR
> **Domain-adapted ASR model optimized for conversational Persian and regional dialects (Kurdish & Lori).**

* **Data Pipeline:** Engineered a noise-stripping framework that isolated and curated **7.7 GB** of pristine vocal tracks from a **~53 GB** raw, unsegmented audio dataset.
* **Fine-Tuning & Performance:** Fine-tuned `whisper-small` via PyTorch and Hugging Face `transformers`, achieving **27.435% WER** and **25.342% CER** on conversational evaluation sets.
* **Deployment:** Live real-time inference web application deployed on Hugging Face Spaces.
* 🔗 **[Try Live Model on Hugging Face Spaces](https://huggingface.co/spaces/Abolfazl27Aflhami88/Houshinoo)**

#### 🤖 2. Autonomous AI Content & Omnichannel Distribution Engine — Agentic Workflows
> **Non-blocking asynchronous state machine for automated B2B content generation and multi-channel publishing.**

* **State Tracking & Memory:** Built an async state engine using n8n workflow static data (`$getWorkflowStaticData`), eliminating external database I/O bottlenecks.
* **Zero-Disk I/O Binary Processing:** Encoded media streams directly into Base64/Data URL buffers in memory to maintain ultra-low processing latency.
* **Multimodal Pipeline & Resilience:** Integrated Gemini 2.5 Flash (B2B copywriting) and Wan 2.7 (image-to-video) via OpenRouter, featuring automated circuit breakers for static mockup fallbacks during upstream timeouts.
* **Distribution Gateway:** Automated distribution across global platforms (TikTok, WhatsApp, IG, FB, Telegram) and regional Iranian networks (Eitaa, Bale, Rubika) via intermediary API gateways.

#### ⚡ 3. Production RAG & Dynamic Inventory Pipeline — AI Product Engineering
> **Sub-second customer support RAG engine featuring automated dynamic vector synchronization.**

* **Dynamic Context Hygiene:** Designed a 3-hour background synchronization pipeline that continuously updates vector embeddings with live stock/pricing context and purges out-of-stock items to eliminate inventory hallucinations.
* **Inference Efficiency:** Optimized retrieval chunks and prompt structures using Gemini 2.5 Flash to achieve sub-second execution times for live user queries.
* **Decoupled Analytics:** Built an asynchronous post-session processing pipeline that parses chat logs into structured lead profiles and intent metadata for direct CRM/ERP ingestion.

---

### 🛠️ Technical Stack & Tooling

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Core & AI/ML** | Python, PyTorch, Hugging Face (`transformers`, `datasets`), Whisper, Librosa |
| **LLMs & RAG** | Gemini 2.5 Flash, OpenRouter Gateway, Vector Databases, Context Optimization |
| **Orchestration & DevOps** | n8n State Machines, Docker, Linux (Ubuntu), Asynchronous Programming, REST APIs |
| **Media & Pipelines** | In-Memory Binary Streams (Base64/Data URLs), FFmpeg, Webhook Architectures |

---

### 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Abolfazl-Afkhami&theme=react-dark" alt="Abolfazl's GitHub Activity Graph" width="100%" />
</div>

---

### 📬 Contact & Links

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abolfazl-afkhami)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/spaces/Abolfazl27Aflhami88)
[![Telegram Channel](https://img.shields.io/badge/Telegram_Channel-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Afkhami_AI)
[![Telegram Direct](https://img.shields.io/badge/Telegram_Direct-229ED9?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Office_Afkhami)
