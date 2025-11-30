# 🌍 EcoLens: The Autonomous LCA Architect

**Track:** Agents for Good (Sustainability)  
**Submission:** Capstone Project 2025

## 📖 Project Description
EcoLens is a multi-agent system designed to democratize Life Cycle Assessment (LCA). It uses a sequential agent architecture to:
1.  **Scout Agent:** Search the web for environmental impact data (using Google Search).
2.  **Analyst Agent:** Synthesize unstructured text into structured decision matrices (using LLM).

## 🚀 How to Run
1.  Install requirements: `pip install -r requirements.txt`
2.  Run the app: `streamlit run app.py`

## 🔑 Features Implemented
* **Multi-Agent System:** Sequential pipeline (Scout -> Analyst).
* **Tools:** Google Search Integration.
* **Session Memory:** Tracks history of comparisons in the sidebar.
* **Graceful Degradation:** The system includes a "Safe Mode" that runs a simulated analysis if no API keys are present, ensuring the application is testable by anyone.