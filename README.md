# Hi, I'm Kamalpreet 👋

**Aspiring Data Scientist / ML Engineer** · Punjab, India
Google Cloud **Professional Machine Learning Engineer** certified

I build ML systems end to end: from data and model, to an API, tests and a dashboard.
I care about measuring models the way the business does — money saved, not just accuracy.

---

## ⭐ Featured: [FraudShield AI](https://github.com/kamalpreet1604/fraudshield-ai)

Fraud detection and risk scoring on the IEEE-CIS dataset (~590K real e-commerce payments, only 3.5% fraud).

- **Time-based split** (train on past weeks, test on future weeks) — no data leakage
- **Logistic Regression baseline → XGBoost**, cut-off chosen by **total cost**, not 0.5
- On unseen test weeks: **PR-AUC 0.452** (≈13× better than random), **66% of fraud money caught**, **95% of the top 100 alerts are real fraud**
- Served with **FastAPI** + **SQLite** history, **pytest** tests, **Docker**, and a **Streamlit** dashboard

`XGBoost` `scikit-learn` `pandas` `FastAPI` `Docker` `Streamlit` `pytest`

---

## 🤖 LLM & RAG projects

| Project | What it does | Stack |
|---|---|---|
| [insta-video-rag](https://github.com/kamalpreet1604/insta-video-rag) | Paste a video link → Whisper transcribes it → chat with the video, answers cite which video they came from | yt-dlp · Groq Whisper · Pinecone · Llama · Streamlit |
| [pm-rag-chatbot](https://github.com/kamalpreet1604/pm-rag-chatbot) | RAG chatbot over a course knowledge base (PDFs with OCR, web pages, YouTube), with an eval harness for precision, recall and faithfulness | LangChain (LCEL) · Pinecone/Chroma · Groq · Streamlit |
| [claude-video](https://github.com/kamalpreet1604/claude-video) | Lets Claude "watch" a video using transcript + key frames, so it can fix words the transcript misheard | Python · Whisper · Claude Code |

## 📚 ML & DL foundations

**[ml-dl-projects](https://github.com/kamalpreet1604/ml-dl-projects)** — 9 classical ML algorithms (churn prediction) and ANN, CNN, LSTM, Transformers and transfer learning (reviews + vision), each with a FastAPI deployment.

---

## 🧰 Tech stack

**ML / DL:** Python · pandas · scikit-learn · XGBoost · TensorFlow · Hugging Face Transformers
**LLM / RAG:** LangChain · Pinecone · Chroma · Groq (Llama, Whisper) · embeddings
**Serving / MLOps:** FastAPI · Docker · Streamlit · pytest · SQLite · Google Cloud (BigQuery)

## 🌱 Currently

- Rebuilding FraudShield from scratch to master every line
- Building a demand-forecasting project on 12.6M rows in BigQuery

📫 Open to **Data Scientist / ML Engineer** fresher roles — reach me on [LinkedIn](https://www.linkedin.com/in/kamalpreet-samra-17578939a/)
