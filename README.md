<div align="center">

# Hey, I'm Vidya Sagar 👋

**M.S. Computer Science @ George Mason University**

*Building at the intersection of LLMs, autonomous agents, and machine learning*

[![GitHub](https://img.shields.io/badge/GitHub-vidyasagar17-181717?style=for-the-badge&logo=github)](https://github.com/vidyasagar17)

</div>

## About Me
I'm a recent Computer Science graduate (M.S., George Mason University, May 2026) with hands-on experience in Python, machine learning, and large language models. As a Graduate Research Assistant, I built large-scale pipelines for extracting structured financial data from SEC filings using LLMs on GCP/Vertex AI work that taught me how to wrestle messy, real-world data into something useful. I love tackling unstructured data problems and building pipelines that actually work in production, not just in notebooks. Now I'm looking for full-time roles in data engineering, ML, or software engineering where I can keep solving hard problems at scale.

**What I'm working on:**
- 🔬 LLM-based financial data extraction from SEC filings (Gemini / Vertex AI)
- 🛡️ Trust-gated news verification systems
- 🧠 Stacked ensemble ML models for healthcare prediction
- 🎨 Multi-modal AI agent pipelines

---

## Featured Projects

### 🛡️ [TrustLens-GDELT — Real-Time News Verification](https://github.com/vidyasagar17/TrustLens-GDELT-Real-Time-News-Verification-System)

A trust-gated news claim verification system powered by the GDELT global news database. Given any claim, TrustLens queries GDELT for matching articles, filters them through a curated trusted-domain allowlist, scores corroboration across independent outlets, and generates a citation-backed verdict using a local LLaMA model via `llama.cpp`.

`Python` · `FastAPI` · `FAISS` · `Ollama/Llama 3.1` · `GDELT API` · `Streamlit`

---

### 🎨 [Multi-Modal Story-to-Illustration Agent](https://github.com/vidyasagar17/Multi-Modal-Story-to-Illustration-Agent)

An AI agent pipeline that reads a plain text story, splits it into scenes, condenses each into concise narration, and generates a matching illustration per page. Uses a **verbal sampling** technique — generating multiple candidate image prompts with different creative lenses (character emotion, environment, composition), then merging the best visual details into a single rich prompt.

`GPT-4o-mini` · `DALL-E 2` · `smolagents` · `LiteLLM`

---

### 🧠 [Stroke Prediction — Stacked Ensemble Learning](https://github.com/vidyasagar17/Stroke-prediction)

A machine learning pipeline that predicts stroke risk from patient health records using a stacked ensemble of four classifiers (Logistic Regression, Random Forest, XGBoost, CatBoost). Handles severe class imbalance with per-model SMOTE tuning and optimizes for high recall using F2 scoring and threshold tuning via Optuna.

**Key result:** ROC-AUC 0.8333 · Optimized for minimal false negatives in a clinical context

`scikit-learn` · `XGBoost` · `CatBoost` · `SMOTE` · `Optuna`

---

### ❤️ [Heart Disease Prediction](https://github.com/vidyasagar17/heart-disease-prediction)

Exploratory data analysis and predictive modeling for heart disease risk using classical ML techniques on clinical patient data.

`Jupyter Notebook` · `pandas` · `scikit-learn`

---

## Tech Stack

| Domain | Tools |
|---|---|
| **Languages** | Python, JavaScript/React, SQL, LaTeX |
| **ML / AI** | scikit-learn, XGBoost, CatBoost, Optuna, SMOTE, FAISS |
| **LLMs** | Gemini (Vertex AI), GPT-4o, Llama 3.1, Ollama, LiteLLM |
| **Data** | pandas, NumPy, SEC EDGAR, GDELT API |
| **Backend** | FastAPI, Flask, Streamlit |
| **Cloud / Infra** | Google Cloud (Vertex AI), Docker |

---

## Research Interests

- **Financial NLP** — Extracting structured data from unstructured SEC filings at scale
- **Information Retrieval** — BM25, semantic search, FAISS-based retrieval
- **Healthcare ML** — High-recall prediction systems for clinical decision support
- **Multi-Agent Systems** — Tool-use patterns, meta-tool synthesis, algorithmic game theory

---

<div align="center">

*Open to research collaborations and full-time opportunities in ML/AI engineering and data science.*

📍 Fairfax, VA · 🎓 George Mason University

</div>
