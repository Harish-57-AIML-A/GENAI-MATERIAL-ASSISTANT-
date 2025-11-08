🧠 **GenAI Material Assistant**

> *Reimagining Material Selection with Artificial Intelligence* ⚙️💡

![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-FF4B4B?logo=streamlit\&logoColor=white)
![LangChain](https://img.shields.io/badge/AI-Engine-LangChain-1abc9c?logo=openai\&logoColor=white)
![FAISS](https://img.shields.io/badge/Database-FAISS%2FChroma-3498db)
![Python](https://img.shields.io/badge/Built%20With-Python-3776AB?logo=python\&logoColor=white)
![Status](https://img.shields.io/badge/Status-Prototype%20in%20Progress-yellow)

---

## 🚀 **Overview**

**GenAI Material Assistant** is a smart **Generative AI-powered system** designed to automate the **Material Selection Process** during **New Product Development (NPD)**.
It helps engineers choose the right materials based on **design constraints, performance requirements, international standards (ASTM, DIN, EN, ISO),** and **sustainability data.**

The system combines **Retrieval-Augmented Generation (RAG)** and **Machine Learning** to provide **faster, more accurate, and explainable recommendations**, reducing manual effort by **25–30%** compared to traditional methods.

---

## 🎯 **Key Objectives**

* Automate **material selection** using **GenAI recommendations**
* Integrate **global material standards** for higher reliability
* Deliver **real-time, explainable insights** during design
* Prioritize **eco-friendly and cost-effective** materials

---

## 🧩 **Core Features**

✅ **AI-Powered Material Recommendations** — Generate suggestions based on temperature, stress, corrosion, and application needs
✅ **RAG-based Knowledge Retrieval** — Fetch standard references from ASTM, DIN, EN, and ISO documents
✅ **Interactive Streamlit UI** — Simple interface for engineers to input requirements
✅ **Smart Ranking System** — Prioritizes materials by performance, cost, and sustainability
✅ **Sustainability Analytics** — Lifecycle and environmental impact insights
✅ **Exportable Reports** — Download results as **PDF or CSV summaries**
✅ **Continuous Learning Loop** — Improves through engineer feedback

---

## 🏗️ **System Architecture**

```
GenAI_Material_Assistant/
│
├── app/
│   ├── app.py                 # Streamlit main UI
│   ├── chatbot.py             # Chatbot interaction logic
│   ├── ranking.py             # Ranking and scoring engine
│   ├── report.py              # Generate PDF report
│
├── data/
│   ├── materials.csv          # Core material property dataset
│   ├── sustainability.csv     # Optional dataset for environmental data
│   ├── standards/             # PDFs/texts of ASTM, DIN, EN, ISO
│
├── models/
│   ├── llm_interface.py       # LangChain + LLM integration
│   ├── vector_store.py        # FAISS/Chroma vector DB setup
│
├── notebooks/
│   ├── data_cleaning.ipynb    # Data preprocessing and cleaning
│
├── README.md
└── requirements.txt           # Dependencies list
```

---

## 🔄 **Workflow**

1. **Input Phase:** Engineer enters design constraints via Streamlit UI
2. **RAG Retrieval:** AI fetches relevant material data and standards
3. **Recommendation Phase:** Model ranks materials by suitability
4. **Engineer Validation:** Results reviewed and fine-tuned
5. **Feedback Loop:** Improves AI model for future accuracy
6. **Report Generation:** Export summary report for documentation

---

## 🧠 **Example Use Case**

> **Design Input:**
> Temperature: 250°C | Pressure: 50 bar | Application: Oil & Gas
>
> **AI Recommendation:**
>
> * 🧩 **Inconel 625** — Excellent corrosion & high-temperature performance
> * 🧩 **AISI 316L** — Economical & corrosion-resistant choice
> * 🧩 **Hastelloy C276** — Suitable for extreme environments
>
> **Output:** Ranked cards + PDF summary report

---

## ⚙️ **Tech Stack**

| Layer               | Technology                        |
| ------------------- | --------------------------------- |
| **Frontend**        | Streamlit                         |
| **AI Engine**       | LangChain + LLM (OpenAI / Llama3) |
| **Database**        | FAISS / Chroma                    |
| **Data Processing** | Pandas, NumPy                     |
| **Reporting**       | ReportLab / FPDF                  |
| **Version Control** | Git + GitHub                      |

---

## 📈 **Impact & Expected Results**

* ⏱️ 25–30% faster material selection
* 📉 Reduced dependency on manual expertise
* 📊 Standardized and explainable decision-making
* 🌿 Encourages sustainability and cost optimization

---

## 🧭 **Future Enhancements**

* Integration with **CAD tools** for live design analysis
* Expansion of **domain-specific datasets** (Aerospace, Subsea, Cryogenics)
* Development of **multi-agent collaboration** for collective material reasoning

---

## 👨‍💻 **Created By**

**Harish Kumar V**
🎓 3rd Year – AIML Department | Rajalakshmi Engineering College
📅 Duration: November 2025 (Prototype Phase)
📧 [231501057@rajalakshmi.edu.in](mailto:231501057@rajalakshmi.edu.in)

---

## 🌟 **Tagline**

> *From intuition to intelligence — transforming material selection with GenAI.* 🤖⚙️

---
