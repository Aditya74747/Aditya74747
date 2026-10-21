<h1 align="left">Aditya Ghatage</h1>
<h3 align="left">ML Engineer · LLM Agents, RAG &amp; Applied Machine Learning</h3>

<p align="left">
<a href="https://linkedin.com/in/ghatage"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://medium.com/@apghatage"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="https://instagram.com/aditya_747_"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:apghatage@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

📍 Stuttgart, Germany · 🎓 M.Sc. Software Technology @ HFT Stuttgart · 🗣️ English (C1), German (B1)

---

I build ML and LLM systems that hold up outside a notebook: churn models running on data from 250,000+ monthly members, LLM pipelines that turn messy social-media feedback into categories a business can act on, and AI agents that are safe enough to point at real data.

Lately I've been most interested in the parts that decide whether an AI system can be trusted: retrieval that cites its sources, agents that ask before they act, local models that keep confidential documents on your own machine, and benchmarks that measure safety as seriously as accuracy.

---

## 🚀 Featured Projects

**[MCP Agent Database](https://github.com/Aditya74747/mcp-agent-database)**
An AI agent backed by three MCP servers I built: DuckDB SQL, hybrid BM25 + embedding document search, and a sandboxed file workspace. It runs on local Ollama models or Claude/OpenAI. The safety layer requires human approval for any non-read-only action, validates SQL by parsing it rather than pattern-matching, sandboxes file paths, writes a JSONL audit log, and is tested against a prompt-injection document.
→ Benchmarked on 14 tasks with local Qwen3 8B: **79% overall, 100% safety, 0 unsafe actions**. FastAPI web UI + CLI, Docker, 110 tests.
<br>`Python` `MCP SDK` `FastAPI` `DuckDB` `Ollama` `Docker` `pytest`

**[Legal Contract Analysis AI](https://github.com/Aditya74747/legal-contract-analysis-ai)**
A fine-tuned DistilBERT that reads a contract (PDF, DOCX or TXT), detects 48 clause types such as Governing Law, Non-Compete and Uncapped Liability, and flags risky clauses with an overall risk score. The training data merges three CUAD annotation formats (JSON, CSV, Excel) into 20,744 cleaned clauses. Evaluation covers per-class F1, a confusion matrix and error analysis.
→ **89.8% test accuracy, 0.89 weighted F1** across 48 classes. Gradio web UI with file upload + CLI.
<br>`Python` `PyTorch` `Hugging Face Transformers` `DistilBERT` `Gradio` `scikit-learn`

**[HR Policy RAG](https://github.com/Aditya74747/hr-policy-rag)**
A fully offline RAG assistant for employee handbooks, HR policies, IT-use guidelines and compliance SOPs, so confidential documents never leave local infrastructure. It loads PDF/DOCX/TXT, uses overlapping chunks, local `nomic-embed-text` embeddings and ChromaDB top-K retrieval, and answers with Llama 3.1 8B through a grounded prompt. **Every answer cites its source file and chunk.**
<br>`Python` `LangChain` `Ollama` `ChromaDB` `Jupyter` `uv`

### More projects

| Project | What it is | Stack |
|---|---|---|
| **[Termite Swarm Cooling](https://github.com/Aditya74747/termite-swarm-cooling)** · [▶️ Live demo](https://aditya74747.github.io/termite-swarm-cooling/) | Swarm-intelligence simulation where 24 server racks keep a data center cool with no central controller. They coordinate only through stigmergy (heat signals left in the shared environment), inspired by termite mounds. | `Python` `Flask` `JavaScript` |
| **[AutoParts IMS](https://github.com/Aditya74747/AutoPartsIMS)** | Desktop inventory system for automotive spare parts with role-based access. The business logic lives in the database: 4 triggers, 5 stored procedures and transactional writes with rollback. | `Java` `Swing` `MySQL` `JDBC` |

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
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
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
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

**Backend, Cloud & Tooling**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

<p align="left">💬 Open to collaborating on LLM agents, RAG, and applied ML. The fastest way to reach me is <a href="mailto:apghatage@gmail.com">apghatage@gmail.com</a>.</p>
