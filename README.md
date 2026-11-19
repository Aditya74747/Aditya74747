# Aditya Ghatage

### Machine Learning Engineer | LLM Agents · RAG · Applied AI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/ghatage)
[![Medium](https://img.shields.io/badge/Medium-Articles-12100E?style=flat-square&logo=medium)](https://medium.com/@apghatage)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:apghatage@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Projects-181717?style=flat-square&logo=github)](https://github.com/Aditya74747)

📍 Stuttgart, Germany · 🎓 M.Sc. Software Technology @ HFT Stuttgart · English (C1) · German (B1)

---

## About Me

I'm a Machine Learning Engineer interested in building AI systems that work beyond proof-of-concepts.

My experience spans applied machine learning, LLM-powered applications, information retrieval, and AI integration. I've worked with behavioural datasets covering **250,000+ monthly members**, developed automated pipelines for extracting insights from social-media feedback, and integrated AI capabilities into enterprise applications.

Currently, I'm particularly interested in:

- **AI Agents & MCP:** Building tool-using agents with controlled access to data and systems.
- **RAG & Information Retrieval:** Improving retrieval quality, grounding, and source attribution.
- **Local & Private AI:** Running LLM applications locally for privacy-sensitive workloads.
- **Applied ML:** Developing predictive models that translate data into actionable business decisions.
- **AI Evaluation & Safety:** Measuring reliability, preventing unsafe actions, and testing systems against adversarial inputs.

I enjoy taking an idea from experimentation to a working application, with an emphasis on practical engineering, measurable results, and responsible AI.

---

## Featured Projects

Projects I'm particularly proud of:

### 1. [MCP Agent Database](https://github.com/Aditya74747/mcp-agent-database)

An AI agent connected to three custom MCP servers:

- DuckDB SQL server for structured data.
- Hybrid BM25 + embedding-based document search.
- Sandboxed file workspace.

**Engineering highlights:**
- Human approval required for non-read-only operations.
- SQL validation through parsing rather than pattern matching.
- Sandboxed file access and JSONL audit logging.
- Tested against prompt-injection documents.

**Evaluation:** 79% overall success across 14 tasks, 100% safety, and zero unsafe actions using Qwen3 8B.

`Python` `MCP` `FastAPI` `DuckDB` `Ollama` `Docker` `pytest`

### 2. [Legal Contract Analysis AI](https://github.com/Aditya74747/legal-contract-analysis-ai)

A fine-tuned DistilBERT model for contract clause classification and risk identification.

- Processes PDF, DOCX and TXT contracts.
- Classifies 48 clause categories, including Governing Law, Non-Compete and Uncapped Liability.
- Combines three CUAD annotation formats into 20,744 cleaned training examples.
- Includes per-class F1 evaluation, confusion matrix and error analysis.
- Provides a Gradio interface and CLI.

**Evaluation:** 89.8% test accuracy and 0.89 weighted F1 across 48 classes.

`Python` `PyTorch` `Transformers` `DistilBERT` `Gradio` `scikit-learn`

### 3. [HR Policy RAG](https://github.com/Aditya74747/hr-policy-rag)

A fully local RAG assistant designed for confidential HR documents and internal company policies.

- Supports PDF, DOCX and TXT documents.
- Uses overlapping document chunks and local embeddings.
- ChromaDB-powered top-K retrieval.
- Generates grounded answers using Llama 3.1 8B through Ollama.
- Includes source-file and document-chunk citations.

`Python` `LangChain` `Ollama` `ChromaDB` `Jupyter`

---

## All Other Projects

<!-- AUTO-PROJECTS-START -->
| Project | Description | Language | Stars | Last Updated |
|---|---|---|---:|---|
| [lorawan-gateway-planner](https://github.com/Aditya74747/lorawan-gateway-planner) | 3D digital twin that finds the fewest LoRaWAN gateway sites to hear every water meter in Heilbronn · Future City Hackathon 2026 · Team Odyssey | Python | 1 | 2026-11-17 |
| [dax-intraday-analysis](https://github.com/Aditya74747/dax-intraday-analysis) | Backtesting study of when to invest in Germany's DAX index (^GDAXI). Tests lump sum vs. monthly buying, dip-buying, weekday and hour-of-day timing on 17 years of daily and 2 years of hourly data, with a €1 fee per trade, 43,758 exhaustive splits and 200,000 Monte Carlo plans. Python, pandas | Python | 0 | 2026-11-02 |
| [legal-contract-analysis-ai](https://github.com/Aditya74747/legal-contract-analysis-ai) | Fine-tuned DistilBERT that detects 48 clause types in legal contracts and flags risky clauses with a risk score. Trained on the CUAD dataset (89.8% accuracy). Gradio web UI with PDF, DOCX and TXT upload. | Jupyter Notebook | 0 | 2026-10-21 |
| [termite-swarm-cooling](https://github.com/Aditya74747/termite-swarm-cooling) | Swarm intelligence simulation of self-organising data center cooling, inspired by termite mounds. 24 rack agents coordinate through stigmergy with no central controller. Python/Flask backend plus a standalone browser version. | HTML | 0 | 2026-10-21 |
| [hr-policy-rag](https://github.com/Aditya74747/hr-policy-rag) | AI-powered RAG system for answering employee policy and compliance questions using official HR documents. Retrieves relevant policy sections and generates accurate, citation-backed responses to ensure reliability and reduce HR dependency. | Jupyter Notebook | 0 | 2026-10-19 |
| [AutoPartsIMS](https://github.com/Aditya74747/AutoPartsIMS) | Desktop inventory management system for automotive spare parts, built with Java Swing and MySQL. Includes role-based access, triggers, stored procedures and transactions. | Java | 0 | 2026-10-19 |
| [mcp-agent-database](https://github.com/Aditya74747/mcp-agent-database) | AI agent with three MCP servers (SQL, document search, files) that asks for human approval before changing anything. Runs locally on Ollama, or on Claude or OpenAI. | Python | 0 | 2026-10-19 |
<!-- AUTO-PROJECTS-END -->

*This section is automatically generated from my public GitHub repositories. New projects are added without manually editing this README.*

---

## Professional Experience

**Data Analyst (ML Engineer) · Leejam Sports Company**  
Riyadh, Saudi Arabia · February 2025 – February 2026

- Built and productionized churn-prediction models using behavioural data from 250,000+ monthly members to identify high-risk customer segments.
- Developed automated LLM pipelines using OpenAI APIs and open-source models to extract, categorize and summarize customer feedback from Instagram, Facebook and Twitter.

**Application Developer · Accenture**  
Pune, India · October 2024 – February 2025

- Integrated chatbot interfaces and AI workloads into enterprise applications using REST APIs and OpenAI APIs.
- Deployed AI features on Microsoft Azure using App Services, Azure Functions and Azure DevOps CI/CD.
- Applied GDPR-aligned security practices to the data processed by these applications.

---

## Research & Recognition

- **Registered Software Copyright – Government of India:** "Sentiment Analysis using Lexicon Based Approach and Algorithms with Large Language Model Implementation" (SW-18871/2024, May 2024), co-authored with faculty supervisors.
- **B.E. Artificial Intelligence & Data Science:** Pune University · GPA 9.2/10.

---

## Technical Skills

**AI, LLMs & Retrieval**

`LLM Applications` `AI Agents` `MCP` `RAG` `LangChain` `Hugging Face` `Transformers` `OpenAI API` `Ollama` `ChromaDB` `NLTK` `spaCy`

**Machine Learning & Data Science**

`Python` `PyTorch` `TensorFlow` `Scikit-learn` `Pandas` `NumPy` `SQL` `Apache Spark` `Databricks` `DuckDB` `MLflow`

**Databases & Analytics**

`PostgreSQL` `MySQL` `MongoDB` `Power BI` `Tableau`

**Backend, Cloud & Engineering**

`FastAPI` `Flask` `Gradio` `Java` `Docker` `Azure` `AWS` `Azure DevOps` `GitHub Actions` `pytest` `Git` `Jupyter`

---

## Let's Connect

I'm interested in collaborating on practical AI/ML projects, LLM agents, retrieval systems, and applied machine learning.

If you're building something interesting or looking for an engineer who enjoys turning AI concepts into working systems, let's connect.

📧 [apghatage@gmail.com](mailto:apghatage@gmail.com)  
💼 [LinkedIn](https://linkedin.com/in/ghatage)  
💻 [GitHub](https://github.com/Aditya74747)
