# Aditya Ghatage

### Machine Learning Engineer | Applied ML · LLM Agents · RAG · Generative AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/ghatage)
[![Medium](https://img.shields.io/badge/Medium-Articles-12100E?style=flat-square&logo=medium)](https://medium.com/@apghatage)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:apghatage@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Projects-181717?style=flat-square&logo=github)](https://github.com/Aditya74747)

📍 Stuttgart, Germany · 🎓 M.Sc. Software Technology @ HFT Stuttgart · English (C1) · German (B1)

---

## About Me

I'm a Machine Learning Engineer with 3+ years of experience building and deploying machine learning, deep learning, and Generative AI solutions.

My experience spans predictive modelling, NLP, LLM applications, RAG systems, and AI agents. I've developed churn-prediction systems, built automated ML and data pipelines, integrated foundation models into enterprise applications, and engineered AI systems with a focus on reliability, privacy, and production readiness.

Some areas I've worked on:

- **Applied Machine Learning:** Predictive modelling, classification, churn prediction, feature engineering, and behavioural analytics.
- **LLMs & Generative AI:** OpenAI APIs, LangChain, LangGraph, prompt engineering, and foundation-model integration.
- **AI Agents & MCP:** Building tool-using agents with controlled access to databases, documents, and files.
- **RAG & Information Retrieval:** Embeddings, vector databases, hybrid search, and source-grounded responses.
- **Data Engineering & MLOps:** Data pipelines, OCR-based datasets, batch processing, deployment, monitoring, and CI/CD.
- **Responsible AI:** GDPR-aligned AI applications, input/output filtering, human approval, and AI safety.

Currently pursuing an M.Sc. in Software Technology at HFT Stuttgart, Germany.

---

## Featured Projects

### 1. [MCP Agent Database](https://github.com/Aditya74747/mcp-agent-database)

An AI agent backed by three custom MCP servers, enabling LLMs to interact with structured data, documents, and files.

**Key engineering highlights:**
- DuckDB SQL server for structured database queries.
- Hybrid BM25 + embedding-based document retrieval.
- Sandboxed file workspace.
- Human approval for non-read-only operations.
- SQL validation through parsing rather than pattern matching.
- JSONL audit logging and prompt-injection testing.

**Evaluation:** 79% overall success across 14 tasks, 100% safety, and zero unsafe actions using Qwen3 8B.

`Python` `MCP` `FastAPI` `DuckDB` `Ollama` `Docker` `pytest`

### 2. [Legal Contract Analysis AI](https://github.com/Aditya74747/legal-contract-analysis-ai)

A fine-tuned DistilBERT-based NLP application for automated legal contract analysis and risk identification.

- Detects 48 legal clause categories, including Governing Law, Non-Compete, and Uncapped Liability.
- Trained using 20,744 cleaned clauses from the CUAD dataset.
- Processes PDF, DOCX, and TXT contracts.
- Identifies potentially risky clauses and generates an overall risk score.
- Includes per-class F1 evaluation, confusion matrix, and error analysis.
- Gradio web interface and CLI.

**Evaluation:** 89.8% test accuracy and 0.89 weighted F1 across 48 classes.

`Python` `PyTorch` `Hugging Face Transformers` `DistilBERT` `Gradio` `scikit-learn`

### 3. [Privacy-First RAG Assistant](https://github.com/Aditya74747/hr-policy-rag)

A fully offline Retrieval-Augmented Generation assistant for confidential HR, employee handbook, and compliance documents.

- Supports PDF, DOCX, and TXT documents.
- Uses local embedding models and document chunking.
- ChromaDB-powered semantic retrieval.
- Generates grounded responses using Llama 3.1 8B through Ollama.
- Provides source-file and document-chunk citations.
- Designed to keep confidential documents within local infrastructure.

`Python` `LangChain` `Ollama` `ChromaDB` `RAG`

---

## Other Projects

<!-- AUTO-PROJECTS-START -->
| Project | Description | Language | Last Updated |
|---|---|---|---|
| [dax-intraday-analysis](https://github.com/Aditya74747/dax-intraday-analysis) | Backtesting study of when to invest in Germany's DAX index (^GDAXI). Tests lump sum vs. monthly buying, dip-buying, weekday and hour-of-day timing on 17 years of daily and 2 years of hourly data, with a €1 fee per trade, 43,758 exhaustive splits and 200,000 Monte Carlo plans. Python, pandas | Python | 2026-11-02 |
| [termite-swarm-cooling](https://github.com/Aditya74747/termite-swarm-cooling) | Swarm intelligence simulation of self-organising data center cooling, inspired by termite mounds. 24 rack agents coordinate through stigmergy with no central controller. Python/Flask backend plus a standalone browser version. | HTML | 2026-10-21 |
| [AutoPartsIMS](https://github.com/Aditya74747/AutoPartsIMS) | Desktop inventory management system for automotive spare parts, built with Java Swing and MySQL. Includes role-based access, triggers, stored procedures and transactions. | Java | 2026-10-19 |
<!-- AUTO-PROJECTS-END -->

*Automatically generated from my public GitHub repositories. New projects are added as I publish them.*

---

## Professional Experience

### Machine Learning Engineer · Leejam Sports Company
Riyadh, Saudi Arabia · February 2025 – February 2026

- Built and deployed a Random Forest-based churn-prediction system to identify high-risk gym members and support targeted retention initiatives.
- Developed OCR-based datasets and batch machine learning pipelines to deliver predictive member insights to the company's application.
- Built an LLM-based NLP pipeline using text embeddings to extract, categorize, and summarize customer feedback from social media.

### AI Application Developer · Accenture
Pune, India · October 2024 – February 2025

- Integrated Generative AI features into enterprise applications using OpenAI APIs and LangChain, streamlining prompt workflows.
- Developed wrappers around foundation models to securely incorporate enterprise data into Generative AI pipelines.
- Implemented input/output filtering for user-facing AI chatbot interfaces.
- Followed GDPR-aligned data protection practices while collaborating with cross-functional teams.

### Data Science Specialist · Skyrise Education
Remote · March 2023 – August 2024

- Built data preprocessing and feature-extraction pipelines using Pandas, NumPy, and SQL for student behavioural datasets.
- Developed and optimized machine learning classification models to predict student enrollment and course dropout.
- Created data-ingestion scripts to integrate processed datasets into existing CRM systems.
- Followed Agile development practices and clean-code principles.

---

## Education

**M.Sc. Software Technology**  
Hochschule für Technik (HFT), Stuttgart, Germany · March 2026 – Present

**B.E. Artificial Intelligence & Data Science**  
Pune University, India · 2020 – 2024

---

## Research & Recognition

- **Registered Software Copyright – Government of India:** "Sentiment Analysis using Lexicon Based Approach and Algorithms with Large Language Model Implementation" · Registration No. SW-18871/2024 · May 2024. Co-authored with faculty supervisors.
- **Bachelor's Degree:** Artificial Intelligence & Data Science · Pune University.

---

## Technical Skills

**Programming Languages**

`Python` `SQL` `Java` `TypeScript`

**Machine Learning & Deep Learning**

`PyTorch` `TensorFlow` `Scikit-learn` `Pandas` `NumPy` `Deep Learning` `NLP` `Computer Vision`

**LLMs & Generative AI**

`OpenAI API` `Hugging Face` `LangChain` `LangGraph` `RAG` `Embeddings` `Prompt Engineering` `MCP` `Ollama` `Vector Databases`

**Data Engineering & MLOps**

`PySpark` `Data Pipelines` `MLOps` `Monitoring & Observability` `A/B Testing`

**Backend & Cloud**

`FastAPI` `REST APIs` `Docker` `Kubernetes` `AWS` `Google Cloud` `Azure`

**Tools & Methodologies**

`Git` `GitLab` `GitHub Actions` `Power BI` `Agile` `Scrum`

---

## Let's Connect

I'm interested in opportunities and collaborations involving applied machine learning, Generative AI, LLM agents, and production AI systems.

I enjoy working on problems where machine learning and AI can translate into practical, measurable business impact.

📧 [apghatage@gmail.com](mailto:apghatage@gmail.com)

💼 [LinkedIn](https://linkedin.com/in/ghatage)

💻 [GitHub](https://github.com/Aditya74747)

✍️ [Medium](https://medium.com/@apghatage)
