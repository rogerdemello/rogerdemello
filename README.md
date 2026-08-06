<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,50:1f6feb,100:8957e5&height=170&section=header&text=Roger%20Demello&fontSize=56&fontColor=ffffff&fontAlignY=42&desc=AI%20Engineer%20%7C%20Agentic%20Systems%20%26%20LLM%20Infrastructure&descSize=17&descAlignY=62" alt="Roger Demello"/>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=720&height=45&lines=I+build+production-grade+AI+that+reaches+users;Agentic+systems+%7C+RAG+pipelines+%7C+LLM+evaluation;3+production+LLM+apps+%7C+200%2B+users+%7C+AWS+Certified" alt="Typing SVG"/></a>
</p>

<p align="center">
  <a href="https://www.rogerdemello.tech/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/rogerdemello"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rogerdemello289@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/u/rogerdemello/"><img src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=orange" alt="LeetCode"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rogerdemello&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
</p>

---

## 🚀 About Me

I'm an **Electronics & Communication** engineer who fell for software the moment I realized code could *think*. What began as curiosity about machine learning turned into a habit I can't shake — **shipping**. Not notebooks that die in a folder, but real systems: LLM applications, RAG pipelines, and autonomous multi-agent frameworks that reach actual users.

Along the way I've built **3 production LLM applications serving 200+ users**, researched **clinical ML models hitting 87% accuracy**, and placed at **national AI hackathons**. The work I care about most sits where agents meet real infrastructure — deterministic policy engines that gate AI decisions, evaluation harnesses that prove a system actually works, and offline-first designs that run without a single API key.

I also keep coming back to the unglamorous, high-impact problems: voice-first tools for kirana shops, adaptive tutors for rural classrooms, and copilots that give small teams enterprise-grade leverage.

> 🌱 **Currently going deep on:** Agentic AI, multi-agent orchestration, MCP, RAG systems & MLOps
> 📫 **Reach me at:** [rogerdemello289@gmail.com](mailto:rogerdemello289@gmail.com)

---

## 🏆 Achievements

- 🥈 **2nd Place** — ByteSize Sage AI National Hackathon
- 🏅 **Finalist** — Paytm × Sarvam × Logitech AI National Hackathon
- ☁️ **AWS Certified Cloud Practitioner** — Amazon Web Services (Oct 2025)
- 🎓 **9.67 / 10 GPA** — Minor in Artificial Intelligence & Machine Learning
- 🤖 Shipped **3 production LLM apps** serving **200+ users** — 35% lower latency, 40% higher task-completion efficiency

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=rogerdemello&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="trophies"/>
</div>

---

## 💼 Experience

**AI Engineer Intern** · *AI LifeBOT* · Jan 2026 – Jun 2026
Engineered 3 production LLM applications and autonomous agents (LangChain, GPT-4) serving 200+ users. Architected end-to-end GenAI pipelines with RAG, vector databases and real-time streaming — cutting response latency 35% at 99.5% uptime — plus multi-agent orchestration with approval gates, telemetry pipelines and audit logging for reproducible agent evaluation.

**Machine Learning Research Intern** · *CFM, RCOEM* · May 2025 – Jul 2025
Built a clinical prediction system on 1,000+ patient health records with biometric feature engineering (blood pressure, sleep duration, stress indices), reaching **87% accuracy**. Optimized the ML pipeline via cross-validation and rigorous evaluation, cutting development time 30%.

---

## ✨ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ ML Guardian
Autonomous ML reliability agent built on **DataHub via MCP** that catches silent production failures — stale upstreams, creeping null rates, renamed columns — before a KPI moves. Runs a *scan → score → incident → write-back → remediate* loop, naming the exact downstream models at risk and generating fail-fast remediation code.

**Offline-first:** bundled fixtures run with no Docker and no API keys; one env var switches it onto a live DataHub.

`Python` `FastAPI` `MCP` `DataHub` `Gemini` `GitHub Actions`

▸ [**Code**](https://github.com/rogerdemello/ml-guardian)

</td>
<td width="50%" valign="top">

### 🤖 Autonomous Executive Email Copilot
A deterministic, RL-style simulation environment for **benchmarking** autonomous email agents across classification, prioritization and full action execution — with bounded, numerically stable grading metrics.

Ships four policy modes (heuristic, stress-test, LLM-driven, multi-agent hybrid), episode replay, approval workflows and published benchmark results with honest findings.

`Multi-Agent RAG` `FastAPI` `React` `SciPy` `PostgreSQL`

▸ [**Live Demo**](https://exec-email-copilot.onrender.com) · [**Code**](https://github.com/rogerdemello/autonomous-executive-email-copilot)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎵 music-recsys
Production-scale two-stage music recommender — **two-tower embeddings → ANN retrieval → LightGBM ranker** — with a full MLOps loop: event bus, feature updater, online store, model registry and retrain jobs.

**Interface-first:** cache, event bus, store, ANN index and registry each sit behind a Protocol, so it runs CPU-only and Windows-native with zero external services, then scales to Kafka/K8s by flipping one config value.

`PyTorch` `LightGBM` `MLflow` `Kafka` `Redis` `Prometheus`

▸ [**Code**](https://github.com/rogerdemello/music-recsys)

</td>
<td width="50%" valign="top">

### 📡 Shadow GTM
Autonomous go-to-market intelligence platform that watches competitors, diffs live web data and delivers ranked revenue plays **grounded in verbatim source evidence**.

Multi-tenant SaaS with workspaces, roles, autonomous scheduling, multi-channel alerts, Stripe billing, battlecard generation, a conversational analyst agent and a public REST API with outbound webhooks.

`Next.js 16` `React 19` `Gemini API` `Supabase` `Stripe` `TypeScript`

▸ [**Live Demo**](https://shadow-gtm.vercel.app) · [**Code**](https://github.com/rogerdemello/shadow-gtm)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ DealSentry
AI-assisted proposal compliance and risk-review system letting sales teams create, analyze, upload and approve proposals while checking pricing, legal and structural requirements — reducing manual review effort by ~70%.

Combines RBAC with an automated compliance rules engine, risk scoring, SLA-tracked approval routing and Salesforce / HubSpot / Gmail / Drive integrations.

`Azure OpenAI` `RAG` `React` `Express` `Prisma` `PostgreSQL`

▸ [**Live Demo**](https://dealsentry.onrender.com/) · [**Code**](https://github.com/rogerdemello/DealSentry)

</td>
<td width="50%" valign="top">

### 🔗 Engram (mneme)
User-owned, **verifiable memory layer for AI agents** on the Sui blockchain — portable memory across apps with on-chain consent grants and revokes, Seal-encrypted Walrus storage and an audit trail of every access.

Agents cite the exact memories they used (receipts), so users can audit and correct AI responses. Built at the Sui hackathon.

`Sui Move` `Walrus` `Seal` `Next.js 16` `React 19` `Playwright`

▸ [**Live Demo**](https://engram-alpha-sage.vercel.app) · [**Code**](https://github.com/rogerdemello/Engram)

</td>
</tr>
</table>

---

## 📂 More Projects

<details>
<summary><b>🧠 AI Platforms & Agentic Systems</b></summary>

<br/>

| Project | What it does | Stack | Links |
|---|---|---|---|
| **SentinelOps** | Predicts incidents before they occur, runs multi-agent root-cause analysis, estimates business impact and proposes human-approved remediation. IsolationForest anomaly detection + dependency-graph modelling, simulated self-healing, Slack/PagerDuty alerting. | `FastAPI` `scikit-learn` `NetworkX` `React` `Supabase` | [Code](https://github.com/rogerdemello/sentinel-ops) |
| **contentflow-ai** | Multi-agent content engine orchestrating drafting, compliance checking, localization and publishing. Policy-aware compliance via local RAG with automatic remediation, audit logging and human-in-the-loop gates. | `LangGraph` `FastAPI` `Streamlit` `Azure OpenAI` | [Code](https://github.com/rogerdemello/contentflow-ai) |
| **SentinelZero** | Industrial safety platform ingesting live sensor data, computing risk, answering SOP-grounded RAG questions and running crisis simulations with coaching. Six-service modular monolith that runs end-to-end with **no external services and no API key**. | `FastAPI` `WebSockets` `SQLite` `Next.js` `Gemini` | [Code](https://github.com/rogerdemello/sentinelzero) |
| **MARK — HR Automation Agent** | AI-native HR platform: floating employee chat widget + HR analytics dashboard. Multi-agent sentiment analysis, proactive nudges, complaint workflows and RAG-grounded policy Q&A, with department heatmaps and at-risk detection. | `FastAPI` `PostgreSQL` `Celery` `React 18` `shadcn/ui` | [Code](https://github.com/rogerdemello/AI-Workplace-Assistant) |
| **omniai-world** | Marketplace for AI agent *crews* that collaborate on tasks and produce downloadable deliverables under a credit-based model, with published agents earning revenue share. | `Next.js 16` `Genkit` `Gemini 2.5` `Firebase` `Stripe` | [Code](https://github.com/rogerdemello/omniai-world) |
| **aipptgen** | Turns a text prompt into a full presentation, streaming outline and slide generation into a rich editable canvas in near real time — layouts, charts, per-slide AI imagery, themes and export. | `Next.js 15` `Plate.js` `Zustand` `TanStack Query` | [Code](https://github.com/rogerdemello/aipptgen) |

</details>

<details>
<summary><b>🇮🇳 India-Market & Social Impact</b></summary>

<br/>

| Project | What it does | Stack | Links |
|---|---|---|---|
| **BharatOS** | Autonomous business OS for India's small businesses, running on **Sarvam-105B** reasoning rather than just voice APIs. Five specialist agents (CFO, Inventory, Marketing, Risk, Growth) plus a Business Twin, with full multilingual voice I/O and a network-proof demo mode. | `Sarvam-105B` `TypeScript` `Express` `Web Audio API` | [Code](https://github.com/rogerdemello/bharatos) |
| **navi-paytm** | Merchant copilot turning photos, voice notes and chat into product catalogs, structured orders, stock alerts and marketing content across **23 Indian languages**. 10+ modules including Auto-Catalog, Stock-Out Predictor and Banner Generator. | `Flutter` `FastAPI` `Sarvam AI` `Telegram Bot API` | [Code](https://github.com/rogerdemello/navi-paytm) |
| **Edumentor AI** | Adaptive tutoring for Grade 5–12 students in government and rural schools. Dynamically adapts learning paths from performance, analyses mistakes to find knowledge gaps, and works **offline in low-connectivity areas** with NCERT-aligned multilingual explanations. | `FastAPI` `Neo4j` `PostgreSQL` `Next.js` | [Code](https://github.com/rogerdemello/edumentor-ai) |
| **edgelearn-ai** | Research-grade adaptive learning platform with multi-agent architecture and knowledge-graph intelligence detecting concept dependencies. Cognitive profiling, predictive exam scoring, an AI debate tutor and spaced repetition across 10+ languages. | `FastAPI` `LangChain` `scikit-learn` `Next.js` | [Live](https://edgelearn-ai.vercel.app) · [Code](https://github.com/rogerdemello/edgelearn-ai) |
| **Autonomous Risk Railguard** | Built for the **NABARD hackathon @ Global Fintech Fest 2026** — forecasts 6-month cash flow per rural micro-enterprise, simulates monsoon/price/demand shocks and flags Green/Amber/Red risk with driver attribution. Bilingual entrepreneur view + field-officer dashboard. | `FastAPI` `React` `Vite` `Recharts` | [Code](https://github.com/rogerdemello/nabard-hackathon) |

</details>

<details>
<summary><b>⛓️ Web3 & Blockchain</b></summary>

<br/>

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Oracle Zero** | Policy-constrained autonomous treasury OS on Mantle. **AI recommends, a deterministic policy engine decides** — every decision hashed, policy-validated and recorded on-chain. Treasury Console + Policy Studio for mandate definition. | `Solidity` `Hardhat` `Mantle` `Next.js 14` `Genkit` | [Code](https://github.com/rogerdemello/oracle-zero) |
| **SplitChain** | Onchain group-expense settlement on Monad — snap a receipt, tap who had what, and clear every debt in **one transaction**. Balances simplified into the fewest transfers, USD entry via a Pyth price feed, live onchain activity feed. | `Solidity` `Monad` `Next.js` `Pyth` `Vision LLM` | [Live](https://splitchain.onrender.com) · [Code](https://github.com/rogerdemello/splitchain) |

</details>

<details>
<summary><b>📊 ML, Data Science & IoT</b></summary>

<br/>

| Project | What it does | Stack | Links |
|---|---|---|---|
| **LifePulse** | Health analytics platform with four trained models — heart disease **87.2%**, sleep disorder **78.3%**, migraine **82.0%**, health score **81.9% R²** — plus risk stratification and a USDA-integrated nutrition tracker, with offline local inference. | `scikit-learn` `XGBoost` `ONNX` `Flask` | [Live](https://lifepulse-9vz4.onrender.com/) · [Code](https://github.com/rogerdemello/LifePulse) |
| **NPK Crop Recommendation** | Reads an RS485 soil sensor over Modbus RTU, then runs a Decision Tree **compiled to a C++ header** so inference happens fully on-device with no internet — the recommendation happens in the field, in seconds. | `scikit-learn` `TFLite` `ESP32` `Modbus RTU` | [Code](https://github.com/rogerdemello/npk-crop-recommendation-system) |
| **Automatic Solar Panel Cleaning** | ESP32-CAM + OpenCV system that detects dust accumulation on solar panels and automatically triggers the cleaning mechanism, with two ESP32s coordinating over WiFi and IR edge detection for safe cycles. | `OpenCV` `FastAPI` `ESP32-CAM` `Arduino` | [Code](https://github.com/rogerdemello/Automatic-Solar-Panel-Cleaning-System) |
| **ImageToToonArt** | Transforms photos into cartoon artwork across 10 styles (Classic Cartoon, Pencil Sketch, Oil Painting, Anime, Watercolor) via OpenCV pipelines with optional deep-learning models. | `OpenCV` `FastAPI` `PyTorch` `React 18` | [Code](https://github.com/rogerdemello/ImageToToonArt) |
| **LabLingo AI** | Scientific dictionary generating instant definitions for any term using a **fully local LLM** — no API keys, no internet, no dependency costs — with caching and privacy-preserving lookup for students and researchers. | `Ollama` `Flask` `React 18` `Vite` | [Code](https://github.com/rogerdemello/LabLingo-AI) |

</details>

<details>
<summary><b>🎯 Assignments & Case Studies</b></summary>

<br/>

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Composio Buildability Study** | Async agent pipeline that researched **100 apps** against their live developer docs, scoring each one's buildability with evidence and confidence per field. An independent auditor agent took verification from **73% → 96%**. Headline finding: 70/100 are buildable today and nearly every blocker is commercial, not technical. | `Python` `Multi-provider LLM` `SQLite` `Composio SDK` | [Live](https://rogerdemello.github.io/composio-buildability-study/) · [Code](https://github.com/rogerdemello/composio-buildability-study) |
| **Email Reply Suggester** | Generates grounded replies to support email, then **measures how good each reply actually is and why** — the bulk of the work is the evaluation system plus a meta-validation suite proving the score reflects real quality. Live NVIDIA NIM run: **4.09/5, 100% pass rate, 0.82 mean similarity**. | `NVIDIA NIM` `Llama 3.1` `Vercel` `uv` | [Live](https://email-reply-suggester-kfga.vercel.app/) · [Code](https://github.com/rogerdemello/email-reply-suggester) |
| **Project Health Reporting Agent** | Analyses Microsoft Project exports and generates executive RAG-status health reports. **A deterministic rules engine computes the scores with no LLM involved; the LLM only explains them** — so the numbers stay auditable. Fuzzy column detection handles messy real spreadsheets. | `Pydantic` `pandas` `python-pptx` `pytest` | [Code](https://github.com/rogerdemello/project-health-agent) |

</details>

---

## 💻 Tech Stack

#### Languages
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)

#### Generative AI & Agents
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

#### ML & Data
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge&logo=leaflet&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

#### Vector & Data Stores
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge&logo=chromatic&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

#### Backend & Frontend
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=flutter&logoColor=white)

#### DevOps & Cloud
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rogerdemello&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rogerdemello&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rogerdemello&theme=tokyonight&hide_border=true" alt="streak"/>
</div>

---

## 🧩 Competitive Coding

<p align="center">
  <a href="https://leetcode.com/u/rogerdemello/"><img src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=leetcode&logoColor=orange" alt="LeetCode"/></a>
  <a href="https://www.codechef.com/users/droger289/"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/></a>
</p>

<div align="center">

![](https://leetcard.jacoblin.cool/rogerdemello?theme=dark&font=Baloo%202&ext=heatmap)

</div>

---

## 📈 Activity

<p align="center">
<img src="https://raw.githubusercontent.com/rogerdemello/rogerdemello/output/github-contribution-grid-snake.svg" alt="snake animation"/>
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=rogerdemello&theme=tokyo-night&hide_border=true" alt="contribution graph"/>
</p>

---

## 🎓 Education

**B.Tech, Electronics & Communication Engineering** — Shri Ramdeobaba College of Engineering and Management (RCOEM), 2022–2026
GPA **8.90/10** · Minor in **Artificial Intelligence & Machine Learning**, GPA **9.67/10**

---

<div align="center">
  <i>⚡ Always building. Open to roles, collaborations, and hard problems worth solving.</i>
  <br/>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8957e5,50:1f6feb,100:0d1117&height=90&section=footer" alt=""/>
</div>
