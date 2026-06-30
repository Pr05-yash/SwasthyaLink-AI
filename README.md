# SwasthyaLink AI 🏥
### Next-Generation Decision Intelligence Platform for Community Healthcare Access

## 🚀 Overview
SwasthyaLink AI is an intelligent platform designed to optimize public healthcare access and provide predictive disease intelligence for smart communities. It bridges the gap between citizens and healthcare systems using advanced AI-driven triage and automated municipal analytics.

## 🌟 Core Features
- **Patient Self-Assessment Port (RAG + LLM):** Integrates Gemini to parse user symptoms against structured medical knowledge bases, providing instant clinical triage assessments in real-time.
- **Epidemiological Command Center:** Simulates smart-city health telemetry to track vector anomalies, evaluate regional outbreak risk indices, and trigger automated healthcare resource rerouting.

## 🛠️ Tech Stack
- **Frontend/UI:** Streamlit (Python-based dashboarding framework)
- **AI Core:** Google Generative AI SDK (Gemini Models Engine)
- **Data Architecture:** Retrieval-Augmented Generation (RAG) using structured local JSON Knowledge Bases, Pandas for telemetry simulations.

## 🏃‍♂️ How to Run Locally
1. Clone the repository: `git clone https://github.com/yourusername/swasthyalink-ai.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set your Gemini API key: 
   - Windows: `set GEMINI_API_KEY=your_key`
   - Mac/Linux: `export GEMINI_API_KEY=your_key`
4. Run the application: `python -m streamlit run app.py`