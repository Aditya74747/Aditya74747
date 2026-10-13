<h1 align="left">Aditya Ghatage</h1>
<h3 align="left">ML Engineer · LLM Agents, RAG &amp; Applied Machine Learning</h3>

<p align="left">
<a href="https://linkedin.com/in/ghatage"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:apghatage@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

📍 Stuttgart, Germany · 🎓 M.Sc. Software Technology @ HFT Stuttgart · 🗣️ English (C1), German (B1)

---

I build ML and LLM systems that hold up outside a notebook: churn models running on data from 250,000+ monthly members, LLM pipelines that turn messy social-media feedback into categories a business can act on, and AI agents that are safe enough to point at real data.

Lately I've been most interested in the parts that decide whether an AI system can be trusted: retrieval that cites its sources, agents that ask before they act, local models that keep confidential documents on your own machine, and benchmarks that measure safety as seriously as accuracy.

---

## 🚀 Featured Projects

<!-- TODO: replace REPO-NAME with the real repository names -->

**[MCP Agent Database](https://github.com/Aditya74747/REPO-NAME)**
An AI agent backed by three MCP servers I built: DuckDB SQL, hybrid BM25 + embedding document search, and a sandboxed file workspace. It runs on local Ollama models or Claude/OpenAI. The safety layer requires human approval for any non-read-only action, validates SQL by parsing it rather than pattern-matching, sandboxes file paths, writes a JSONL audit log, and is tested against a prompt-injection document.
→ Benchmarked on 14 tasks with local Qwen3 8B: **79% overall, 100% safety, 0 unsafe actions**. FastAPI web UI + CLI, Docker, 110 tests.
<br>`Python` `MCP SDK` `FastAPI` `DuckDB` `Ollama` `Docker` `pytest`

**[Employee Policies & Compliance RAG](https://github.com/Aditya74747/REPO-NAME)**
A fully offline RAG assistant for employee handbooks, HR policies, IT-use guidelines and compliance SOPs, so confidential documents never leave local infrastructure. It loads PDF/DOCX/TXT, uses overlapping chunks, local `nomic-embed-text` embeddings and ChromaDB top-K retrieval, and answers with Llama 3.1 8B through a grounded prompt. **Every answer cites its source file and chunk.**
<br>`Python` `LangChain` `Ollama` `ChromaDB` `Jupyter` `uv`
---

## 💼 Experience

**Data Analyst (ML Engineer) · Leejam Sports Company** · Riyadh, KSA · *Feb 2025 – Feb 2026*
- Built and productionized churn-prediction models on behavioural data from 250,000+ monthly members, identifying high-risk segments for targeted retention campaigns.
- Developed an automated LLM pipeline (OpenAI APIs + open-source models) that extracts, categorizes and summarizes customer concerns from Instagram, Facebook and Twitter.

**Application Developer · Accenture** · Pune, IND · *Oct 2024 – Feb 2025*
- Added chatbot interfaces and AI workloads to enterprise applications using REST and OpenAI APIs.
- Deployed the AI features on Azure (App Services, Azure Functions) through Azure DevOps CI/CD, with GDPR-aligned security practices for the data they processed.

---

## 📜 Research & Recognition

- **Registered software copyright, Government of India:** *"Sentiment Analysis using Lexicon Based Approach and Algorithms with Large Language Model Implementation"*, Reg. No. SW-18871/2024 (May 2024), co-authored with faculty supervisors.
- **B.E. in Artificial Intelligence & Data Science**, Pune University, GPA 9.2/10.

---

## 🛠️ Tech Stack

**LLMs & AI**
<br>
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1a1a1a?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-1a1a1a?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1a1a1a?style=flat-square)
![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=flat-square)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)

**Machine Learning & Data**
<br>
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Backend, Cloud & Tooling**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

<p align="left">💬 Open to collaborating on LLM agents, RAG, and applied ML. The fastest way to reach me is <a href="mailto:apghatage@gmail.com">apghatage@gmail.com</a>.</p>
