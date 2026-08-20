# Hi, I'm Pratik 👋

I'm a self-taught Data Scientist and AI Engineer based in Navi Mumbai, focused on building machine learning and AI systems that are reliable, explainable, and useful in real-world decision making.

My work spans predictive modeling, uncertainty quantification, retrieval-augmented generation (RAG), and memory-augmented AI systems.

---

## 🔍 What I Work On

- **Probabilistic modeling** — calibrated probabilities over hard classifications
- **Uncertainty quantification** — prediction intervals, confidence estimation
- **Explainability** — SHAP-based model transparency for regulated domains
- **Time-series forecasting** — demand forecasting with feature engineering
- **Simulation** — Monte Carlo methods for season-level uncertainty
- **Applied AI systems** — retrieval-augmented generation (RAG), semantic search, vector databases, and long-term memory architectures

---

## Currently Exploring

- Production ML systems and MLOps
- CI/CD for machine learning applications
- AI evaluation and reliability
- Advanced RAG and agent architectures
- Uncertainty-aware and interpretable ML
  
---

## 📂 Featured Projects

### 🏦 [Credit Risk Default Prediction](https://github.com/pratiksingh1296/credit-risk-modeling) · [🚀 Live Demo](https://credit-risk-default-predictor.streamlit.app/)

- Probability calibration: Platt scaling reduced XGBoost ECE from 0.2528 to 0.0025 while improving ROC-AUC from 0.760 to 0.763
- Compared calibration strategies across Logistic Regression and XGBoost, with calibrated models achieving ECE values of 0.0026 and 0.0025 respectively
- Risk-based decisioning translating calibrated default probabilities into Low / Medium / High / Very High risk tiers and lending decisions
- SHAP-based applicant-level explanations showing which features push predictions toward higher or lower risk
- Production-style deployment with a FastAPI inference API, Docker, Render, and Streamlit frontend
- `Python` `Scikit-learn` `XGBoost` `SHAP` `FastAPI` `Docker`
  
---

### 🧠 [Context-Aware AI Assistant](https://github.com/pratiksingh1296/context-aware-ai-assistant) · [🚀 Live Demo](https://memory-chatbot-ai.streamlit.app/)

Conversational AI assistant featuring persistent memory, multi-session chat management, and real-time web retrieval.

- Four-layer memory architecture combining session memory, semantic vector retrieval, structured fact memory, and conversation summarization
- Automatic user profiling with semantic deduplication and memory conflict resolution to maintain accurate long-term user profiles
- Running conversation summaries to reduce prompt growth and preserve long-term context
- Intelligent model routing using lightweight and large LLMs to balance latency, cost, and response quality
- Real-time web search integration using Tavily, LangChain agents, and tool-augmented reasoning
- Streamlit deployment with caching, session persistence, and automated chat organization
- Centralized debug logging and modular memory architecture  
- `Python` `LangChain` `PostgreSQL` `pgvector` `Groq` `Streamlit`

---

### ⚡ [Electricity Demand Forecasting](https://github.com/pratiksingh1296/electricity-demand-forecasting) · [🚀 Live Demo](https://grid-demand-forecast.streamlit.app/)
Hourly electricity demand forecasting on real EIA grid data (Texas, 2018–2023).
- Time-series feature engineering: lag features, rolling stats, cyclical encoding
- XGBoost achieving 2.40% MAPE — 48% improvement over seasonal naive baseline
- Weather integration via Open-Meteo API
- `Python` `XGBoost` `Scikit-learn` `Pandas`

---

### ⚽ [Football Momentum Forecasting](https://github.com/pratiksingh1296/football-momentum-forecasting) · [🚀 Live Demo](https://football-momentum-forecasting.streamlit.app/)

NLP system predicting football match momentum from live commentary text, built through five controlled experiments rather than a single model.

- Fine-tuned DistilBERT achieving 91% macro F1 (up from a 72% baseline) by diagnosing and fixing a home/away confound in raw commentary text
- Systematic ablation studies isolating the effect of entity anonymization, structured feature fusion, and temporal window size, including two honestly-reported null/negative results
- Boundary sensitivity analysis linking residual model errors to inherent label ambiguity, not just model weakness
- Full deployment: model hosted on Hugging Face Hub, interactive Streamlit replay demo with live momentum visualization
- `Python` `PyTorch` `Transformers (DistilBERT)` `LightGBM` `Streamlit` `Hugging Face Hub`
  
---

## 🛠️ Tech Stack

### Languages & Core
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)

### Machine Learning
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=flat)

### Deep Learning & NLP
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat)
![DistilBERT](https://img.shields.io/badge/DistilBERT-FFCA28?style=flat)

### AI & LLM Engineering
![LangChain](https://img.shields.io/badge/LangChain-00A67E?style=flat)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat)
![Llama](https://img.shields.io/badge/Llama_3.3-0467DF?style=flat)
![SentenceTransformers](https://img.shields.io/badge/Sentence_Transformers-FF6F00?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)
![Tavily](https://img.shields.io/badge/Tavily-1E90FF?style=flat)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

### APIs, Tools & Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Hugging Face Hub](https://img.shields.io/badge/🤗_Hub-FFD21E?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pratik-singh-ds/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/pratiksingh1296)
