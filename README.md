<div align="center">

<a href="https://aditya74747.github.io/">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=26&pause=1400&color=5B3FD9&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Aditya+Ghatage+%F0%9F%91%8B;Machine+Learning+Engineer+in+Stuttgart;LLM+Agents+%C2%B7+RAG+%C2%B7+Generative+AI;Turning+data+into+decisions%2C+and+models+into+products." alt="Hi, I'm Aditya Ghatage. Machine Learning Engineer in Stuttgart." />
</a>

**Machine Learning Engineer · Applied ML · LLM Agents · RAG · Generative AI**

[![Portfolio](https://img.shields.io/badge/Portfolio-aditya74747.github.io-5B3FD9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://aditya74747.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ghatage)
[![Medium](https://img.shields.io/badge/Medium-Articles-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@apghatage)
[![Email](https://img.shields.io/badge/Email-Say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:apghatage@gmail.com)

📍 Stuttgart, Germany &nbsp;·&nbsp; 🎓 M.Sc. Software Technology @ HFT Stuttgart &nbsp;·&nbsp; 🗣️ English C1 · German B1.1

🌐 **[Visit my portfolio →](https://aditya74747.github.io/)** &nbsp;it's written as an ML model card, with a *Model view* switch.

</div>

---

## ⚡ At a glance

<div align="center">

| **94%** | **89.8%** | **100%** | **0.961** |
|:---:|:---:|:---:|:---:|
| of high-risk gym members targeted by my churn models stayed | accuracy across 48 legal clause types | safety score of my MCP agent, 0 unsafe actions | AUC of the LoRaWAN coverage model on unseen gateways |

</div>

## 👋 About me

I'm a Machine Learning Engineer with **3+ years** of experience taking machine learning, deep learning and Generative AI from raw data to production.

I've built churn-prediction systems for **250,000+ members**, automated ML and data pipelines, integrated foundation models into enterprise applications, and engineered AI agents that ask before they act. I care about reliability, privacy and AI you can actually check.

| | What I work on |
|---|---|
| 📈 **Applied ML** | Predictive modelling, classification, churn prediction, feature engineering, behavioural analytics |
| 🤖 **LLMs & GenAI** | OpenAI APIs, LangChain, LangGraph, prompt engineering, foundation-model integration |
| 🧰 **AI Agents & MCP** | Tool-using agents with controlled access to databases, documents and files |
| 🔎 **RAG & Retrieval** | Embeddings, vector databases, hybrid search, source-grounded answers |
| 🛠️ **Data & MLOps** | Data pipelines, OCR-based datasets, batch processing, deployment, monitoring, CI/CD |
| 🛡️ **Responsible AI** | GDPR-aligned applications, input/output filtering, human approval, AI safety |

---

## 🚀 Featured projects

### 🌱 [Kilowise](https://github.com/Aditya74747/kilowise): cost, energy & CO₂ ledger for IT
`sprintd Basel 2026` `Green AI & Data case (ALTYCA)` `Team Mini Militia` &nbsp;·&nbsp; [**Live app**](https://aditya74747.github.io/kilowise/app/index.html) · [**Demo video**](https://aditya74747.github.io/kilowise/pitch/assets/kilowise_demo_voice.mp4)

Turns a small company's IT exports (cloud invoices, servers, AI usage, SaaS contracts) into one ledger of cost, energy and location-based CO₂, then recommends measures that hit the targets without switching off anything critical.

> **−48.8% CO₂** (target −40%) · **−33.4% cost** (CHF 155k/year) · **0 conflicts** over 3,811 real job runs · fine-tuned assistant **0.815 vs. 0.276** for the base model

<details>
<summary><b>How it works</b></summary>

- Data pipeline that cleans and combines 28 messy exports (duplicates, three currencies, mixed date formats and units) into a traceable ledger, with every factor linked to one of 59 sources.
- 12 recommended measures within a 15 person-day budget.
- Safety checks: every schedule change is replayed against 3,811 real job runs, and instructions hidden in the data are quarantined, never acted on.
- **"Ask Kilo" assistant:** Qwen2.5-1.5B with a LoRA adapter we fine-tuned, plus retrieval over the ledger and a check of every figure in each answer. Scored 0.815 vs. 0.276 for the base model on 181 held-out questions.
- 11-page web app with dashboards, a forecast, comparisons of ML models and 20 LLMs, and read-only connectors for AWS, Azure, OpenAI, Claude and Microsoft 365.

</details>

`Python` `pandas` `scikit-learn` `PyTorch` `LoRA / PEFT` `Transformers` `RAG` `JavaScript` `pytest`

### 📡 [LoRaWAN Gateway Planner](https://github.com/Aditya74747/lorawan-gateway-planner): 3D digital twin
`Future City Hackathon 2026` `HNVG challenge` `Team Odyssey` &nbsp;·&nbsp; [**Live demo**](https://lorawan-gateway-planner.netlify.app/)

A 3D digital twin of Heilbronn that learns from real radio data and finds the fewest gateway sites that still hear almost every water meter in the city.

> **27 of 71 sites reach 98% coverage** (up from ≈46% today) · CatBoost **AUC 0.961** on unseen gateways · RSSI error **3.5 dB** vs. 4.8 dB for the textbook model

<details>
<summary><b>How it works</b></summary>

- Line-of-sight features computed for every meter-to-gateway path from 83,000 buildings, terrain and tree canopy in official open geodata.
- Compared 13 learners with leave-one-gateway-out validation. A CatBoost ensemble with monotonic constraints won.
- Greedy optimiser with pruning and swaps, plus a build order for the selected sites.
- Simulates gateway failures, plans for future districts from official building plans (XPlanung), and works for other cities from open data only (tested on Stuttgart).
- Interactive 3D planner built with deck.gl and MapLibre, served by FastAPI.

</details>

`Python` `CatBoost` `scikit-learn` `GeoPandas` `rasterio` `FastAPI` `deck.gl` `Docker`

### 🤖 [MCP Agent Database](https://github.com/Aditya74747/mcp-agent-database): an agent that asks before it acts

An AI agent backed by three custom MCP servers that lets LLMs work with structured data, documents and files, with a human in the loop for anything risky.

> **79%** task success on a 14-task benchmark · **100% safety** · **0 unsafe actions** · runs locally on Qwen3 8B

<details>
<summary><b>Engineering highlights</b></summary>

- DuckDB SQL server for structured database queries.
- Hybrid BM25 + embedding document retrieval.
- Sandboxed file workspace with GitHub integration.
- Human approval for every non-read-only operation.
- SQL validated by parsing, not pattern matching.
- JSONL audit logging and prompt-injection testing.
- Runs fully locally through Ollama, or on Claude or OpenAI by changing one setting.

</details>

`Python` `MCP` `FastAPI` `DuckDB` `Ollama` `Docker` `pytest`

### ⚖️ [Legal Contract Analysis AI](https://github.com/Aditya74747/legal-contract-analysis-ai): clause detection & risk scoring

A fine-tuned DistilBERT application that reads contracts, detects 48 clause types and flags the risky ones.

> **89.8%** test accuracy · **0.89** weighted F1 across 48 classes · trained on **20,744** cleaned CUAD clauses

<details>
<summary><b>What it does</b></summary>

- Detects 48 clause categories, including Governing Law, Non-Compete and Uncapped Liability.
- Stratified 80/10/10 split, per-class F1 evaluation, confusion matrix and error analysis.
- Reads PDF, DOCX and TXT contracts and computes an overall risk score.
- Gradio web interface and CLI.

</details>

`Python` `PyTorch` `Hugging Face Transformers` `DistilBERT` `Gradio` `scikit-learn`

### 🔒 [Privacy-First RAG Assistant](https://github.com/Aditya74747/hr-policy-rag): answers with citations, fully offline

A Retrieval-Augmented Generation assistant for confidential HR, handbook and compliance documents that never leave local infrastructure.

> **100% offline** · every answer cites its **source file and chunk** · Llama 3.1 8B via Ollama

<details>
<summary><b>How it works</b></summary>

- Loads PDF, DOCX and TXT documents and splits them into overlapping chunks.
- Local embedding model and ChromaDB semantic retrieval.
- Grounded responses from Llama 3.1 8B through Ollama.

</details>

`Python` `LangChain` `Ollama` `ChromaDB` `RAG`

---

## 🧪 More projects

<sub>Updated automatically every day from my public repositories, newest first.</sub>

<!-- AUTO-PROJECTS-START -->
| Project | What it is |
|---|---|
| **[DAX Intraday Analysis](https://github.com/Aditya74747/dax-intraday-analysis)**<br><sub>Python · Nov 2026</sub> | Backtesting study of when to invest in Germany's DAX index (^GDAXI). Tests lump sum vs. monthly buying, dip-buying, weekday and hour-of-day timing on 17 years of daily…<br>`backtesting` `dax` `financial-analysis` |
| **[Termite Swarm Cooling](https://github.com/Aditya74747/termite-swarm-cooling)**<br><sub>HTML · Oct 2026</sub> | Swarm intelligence simulation of self-organising data center cooling, inspired by termite mounds. 24 rack agents coordinate through stigmergy with no central controller…<br>`cooling` `data-center` `emergent-behavior` · [Live demo](https://aditya74747.github.io/termite-swarm-cooling/) |
| **[AutoPartsIMS](https://github.com/Aditya74747/AutoPartsIMS)**<br><sub>Java · Oct 2026</sub> | Desktop inventory management system for automotive spare parts, built with Java Swing and MySQL. Includes role-based access, triggers, stored procedures and transactions.<br>`database` `desktop-app` `inventory-management` |
<!-- AUTO-PROJECTS-END -->

---

## 💼 Experience

**🏋️ Machine Learning Engineer · Leejam Sports Company**
<br><sub>Riyadh, Saudi Arabia · Feb 2025 – Feb 2026</sub>

- Built and deployed a Random Forest-based churn-prediction system on **250,000+ members**. **94%** of the high-risk members targeted by the resulting retention campaigns stayed.
- Developed OCR-based datasets and batch ML pipelines that deliver predictive member insights to the company's app.
- Built an LLM-based NLP pipeline with text embeddings to extract, categorise and summarise customer feedback from social media.

**☁️ Application Developer · Accenture**
<br><sub>Pune, India · Oct 2024 – Feb 2025</sub>

- Integrated Generative AI features into enterprise applications with OpenAI APIs and LangChain.
- Built wrappers around foundation models to bring enterprise data into GenAI pipelines securely.
- Implemented input/output filtering for user-facing AI chatbots, following GDPR-aligned data protection practices.

**🎓 Data Science Specialist · Skyrise Education**
<br><sub>Remote · Mar 2023 – Sep 2024</sub>

- Built and optimised ML classification models that predict student enrollment and course drop-out.
- Built preprocessing and feature-extraction pipelines with Pandas, NumPy and SQL for student behaviour data.
- Wrote data-ingestion scripts into the existing CRM, following Agile and clean-code practices.

---

## 🎓 Education & recognition

| | |
|---|---|
| **M.Sc. Software Technology**<br><sub>Hochschule für Technik Stuttgart · Mar 2026 – present</sub> | Grade average **1.39** after the first semester |
| **B.E. Artificial Intelligence & Data Science**<br><sub>Pune University · 2020 – 2024</sub> | GPA **9.2/10** (German grade 1.4) |
| **Registered Software Copyright, Govt. of India**<br><sub>SW-18871/2024 · May 2024</sub> | *Sentiment Analysis using Lexicon Based Approach and Algorithms with Large Language Model Implementation*, co-authored with faculty supervisors |

---

## 🧠 Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,ts,pytorch,tensorflow,sklearn,fastapi,docker,kubernetes,aws,gcp,azure,git,gitlab,githubactions&perline=8" alt="Python, Java, TypeScript, PyTorch, TensorFlow, scikit-learn, FastAPI, Docker, Kubernetes, AWS, Google Cloud, Azure, Git, GitLab, GitHub Actions" />

</div>

| | |
|---|---|
| **ML & Deep Learning** | `PyTorch` `TensorFlow` `scikit-learn` `Pandas` `NumPy` `Deep Learning` `NLP` `Computer Vision` |
| **LLMs & GenAI** | `OpenAI API` `Hugging Face` `LangChain` `LangGraph` `RAG` `Embeddings` `Prompt Engineering` `MCP` `Ollama` `Vector Databases` |
| **Data & MLOps** | `PySpark` `Data Pipelines` `MLOps` `Monitoring & Observability` `A/B Testing` |
| **Backend & Cloud** | `FastAPI` `REST APIs` `Docker` `Kubernetes` `AWS` `Google Cloud` `Azure` |
| **Tools & Ways of working** | `Git` `GitLab` `GitHub Actions` `Power BI` `Agile` `Scrum` |

---

<div align="center">

## 🤝 Let's connect

I'm open to opportunities and collaborations in applied machine learning, Generative AI, LLM agents and production AI systems, especially where AI turns into measurable business impact.

[![Portfolio](https://img.shields.io/badge/Portfolio-5B3FD9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://aditya74747.github.io/)
[![Email](https://img.shields.io/badge/apghatage@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:apghatage@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ghatage)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aditya74747)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@apghatage)

</div>
