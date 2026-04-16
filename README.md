# 🌱 ESG Greenwashing Detector

An AI-powered NLP pipeline to analyze ESG (Environmental, Social, Governance) reports and detect misleading or vague sustainability claims. This project helps improve transparency by identifying assertive vs vague corporate statements.

---

## 🚀 Key Features
- 🔍 Extracts environmental claims from PDF reports
- 🤖 Classifies claims using DistilBERT (Transformer-based NLP)
- ⚠️ Detects vague and non-committal language using custom NLP logic
- 📊 Scores claims based on assertiveness and readability
- ⚡ Uses GROQ API for fast validation (optimized over RAG for lower latency)
- 📈 Interactive dashboard for real-time analysis

---

## 🛠 Tech Stack
- **Frontend:** Streamlit  
- **ML/NLP:** DistilBERT, Transformers  
- **PDF Processing:** PyPDF2  
- **APIs:** GROQ API  
- **Metrics:** Readability (textstat), Assertiveness scoring  

---

## 🧠 AI/ML Contribution
- Applied transformer-based NLP (DistilBERT) for claim classification  
- Designed scoring mechanisms for assertiveness and vague language detection  
- Optimized system latency by replacing RAG with API-based inference  
- Built an end-to-end ML pipeline from raw PDF → structured insights  

---

## ⚙️ Setup

```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
