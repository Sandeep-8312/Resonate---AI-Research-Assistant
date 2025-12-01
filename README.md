# 🌐 RESONATE: AI Research Exploration Assistant

> **Track:** Agents for Good | Kaggle AI Agents Challenge  
> **Author:** Sandeep Kumar

---

## 💡 Overview
**RESONATE (Research Exploration System of Networked Agents for Thought Enhancement)** is a multi-agent AI system that automates the process of reading, summarizing, tagging, linking, and visualizing research papers.

It transforms unstructured scientific text into structured, interconnected knowledge — empowering researchers and students to explore ideas more efficiently.

---

## 🧠 Features
- 📄 Automated paper ingestion and normalization  
- 🧩 Structured summarization using Gemini API with offline fallback  
- 🧠 Topic tagging for thematic categorization  
- 🔗 Inter-paper relationship discovery  
- 🕸️ Knowledge graph visualization  
- 🧾 Markdown report generation  

---

## ⚙️ Architecture

![Architecture Diagram](resonate_architecture.png)

Each specialized agent performs a modular task coordinated by an **Orchestrator**:  

1. **Ingestion Agent** – Normalizes inputs  
2. **Summarization Agent** – Extracts structured summaries  
3. **Tagging Agent** – Assigns research domains  
4. **Linking Agent** – Detects conceptual relationships  
5. **Graph Builder Agent** – Builds a visual graph  
6. **Report Agent** – Generates the final report  

---

## 📊 Example Output

![Knowledge Graph](resonate_graph.png)

**Generated Files:**
- `resonate_graph.png` → Knowledge graph  
- `resonate_report.md` → Structured research summary report  

---

## 🚀 Future Enhancements
- Interactive Streamlit/Gradio dashboard  
- Live research retrieval via arXiv/Semantic Scholar  
- Citation-based graph linking  
- Collaborative open-science knowledge base  
- Multi-agent reasoning and QA expansion  

---

## 🧠 Tech Stack
- **Language:** Python 3.12  
- **Libraries:** `networkx`, `matplotlib`, `pandas`, `google.generativeai`  
- **Platform:** Kaggle Notebook  
- **Model:** Google Gemini 2.5 Pro (hybrid LLM client)  

---

## 🌍 Impact
RESONATE demonstrates how AI agents can enhance human understanding rather than replace it.  
By bridging fragmented research through intelligent collaboration, it advances open science and educational accessibility — truly an **Agent for Good**.

---

## 🧾 License
This project is open-source under the **MIT License**.

---

## 📫 Connect
**Author:** Sandeep Kumar  
- Kaggle: [@sandeepkumar43](https://www.kaggle.com/sandeepkumar43)  
- LinkedIn: [Your LinkedIn Profile](#)  
- GitHub: [Your GitHub Profile](#)
