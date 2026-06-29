# 👋 Hi, I'm Tarun Tippana

## AI Engineer | Agentic AI & RAG Pipelines

📍 Vizianagaram, Andhra Pradesh, India  
📧 taruntippana@gmail.com  
🔗 [Portfolio](https://my-portfolio-coral-three-c89n6s5uxy.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/tarun-tippana/) | [GitHub](https://github.com/tarun-tippana) 

---

### 🚀 About Me

I'm an AI Engineer with hands-on experience building **production-ready agentic workflows** using LangChain, LangGraph, and RAG pipelines. I'm passionate about creating intelligent systems that automate complex decision-making processes and solve real-world problems.

- 🤖 Built a production-ready **Agentic Hiring Assistant** automating 70-80% of HR tasks
- 🔍 Designed end-to-end **RAG pipelines** with ChromaDB and FAISS
- ⚡ Integrated **Mistral AI** and **Groq** LLM APIs for intent extraction and response generation
- 🛠️ Exposed AI capabilities via **FastAPI** REST APIs
- 📊 Currently upskilling in Advanced Data Science @ **Innomatics Research Labs**

---
### 💼 Experience

- **Data Analyst Intern (AI Engineering Focus)** @ Intellentech Pvt Ltd (Jan 2026 - Mar 2026)
  - Built Agentic AI hiring assistant with LangChain/LangGraph
  - Designed RAG pipelines with ChromaDB and LLM APIs
  - Integrated LangSmith for tracing and debugging

- **Data Science Trainee** @ Innomatics Research Labs (Current)
  - Advanced training in Data Science, ML, and AI systems

---

### 🛠️ Tech Stack

**Core AI & LLMs:**
![Agentic AI](https://img.shields.io/badge/Agentic_AI-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat&logo=ai&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-4A90E2?style=flat&logo=ai&logoColor=white)

**LLM APIs & Vector DBs:**
![Mistral AI](https://img.shields.io/badge/Mistral_AI-7B3FE4?style=flat&logo=mistralai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-FF6B6B?style=flat&logo=groq&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4A154B?style=flat&logo=chromadb&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-005A9C?style=flat&logo=facebook&logoColor=white)

**Programming & Backend:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**NLP & Observability:**
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=flat&logo=python&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat&logo=langchain&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

### 🏆 Featured Projects

### HR AI Scout - Agentic Hiring Assistant 
LangChain · LangGraph · RAG · Mistral AI · Groq · ChromaDB · FastAPI · LangSmith

A production-grade, end-to-end Agentic AI system developed during my internship at Inteltechnet Pvt Ltd, designed to automate 70-80% of routine HR tasks and streamline the recruitment pipeline.

### 🚀 Key Features & Capabilities:

Agentic Workflow Orchestration: Built a stateful, multi-step agentic workflow using LangChain and LangGraph. Implemented conditional routing and state graphs to manage complex, decision-driven HR processes like resume screening, candidate shortlisting, and interview query generation.

Custom Tool Integration: Developed and integrated custom tools for document parsing, candidate data retrieval, and automated scoring, enabling the agent to interact with external data sources seamlessly.

Advanced RAG Pipeline: Designed a complete Retrieval-Augmented Generation (RAG) pipeline (chunking → embedding → retrieval → response grounding) over HR policy documents and job description repositories. Used ChromaDB as the vector store and FAISS for efficient similarity search.

LLM Integration & Prompt Engineering: Leveraged Mistral AI and Groq LLM APIs for critical tasks including:

Intent Extraction: Understanding candidate queries and HR requirements

Candidate Scoring: Automatically ranking applicants based on JD fitment

Interview Query Generation: Creating contextually relevant, role-specific questions

Observability & Debugging: Integrated LangSmith for comprehensive tracing, debugging, and evaluation of LLM and agent trajectories, ensuring system reliability and performance transparency.

Production-Ready API Layer: Exposed the agent's capabilities through FastAPI REST APIs, allowing external systems (like ATS platforms) to trigger retrieval, orchestration, and automated actions programmatically.

CI/CD & Version Control: Managed code with GitHub, implemented CI/CD workflows, and maintained unit testing to ensure production-grade code quality.

📊 Business Impact: Reduced manual HR effort by 70-80%, significantly accelerating the recruitment cycle and improving candidate-role matching accuracy.



#### [LLM Review Analyst - LangGraph Workflow]
> **LangGraph · Groq · Streamlit · Pydantic**

A smart, agentic review analysis system built with LangGraph. It analyzes customer feedback, detects sentiment, and generates appropriate responses through a structured workflow:

- **Sentiment Analysis:** Classifies reviews as Positive or Negative.
- **Conditional Routing:** Routes positive reviews to a thank-you response generator and negative reviews to a diagnostic node.
- **Issue Diagnosis (for Negative Reviews):** Identifies the **Issue Type** (UX, Performance, Bug, Support, Other), analyzes the **Tone** (angry, frustrated, disappointed, calm), and detects **Urgency** (low, medium, high).
- **Smart Response Generation:** Crafts empathetic, context-aware replies based on the diagnosis.

**Example:** For a review like *"The product is broken and also the colour that I have expected is faded"*, the system correctly identifies:
- **Sentiment:** Negative
- **Issue Type:** Bug
- **Tone:** Angry
- **Urgency:** High
- **Response:** An empathetic, high-priority support message.

[![Hugging Face Space](https://img.shields.io/badge/🤗-Live_Demo-yellow)](https://huggingface.co/spaces/taruntippana/llm-review-analyst)

#### [Diet Plan Suggester]
> **Scikit-learn · Pandas · Logistic Regression · Streamlit · Hugging Face**

ML classification system achieving 90% accuracy after hyperparameter tuning. Features EDA, feature engineering, and model deployment on Hugging Face Spaces for real-time dietary predictions.

[![Hugging Face Space](https://img.shields.io/badge/🤗-Live_Demo-yellow)](https://huggingface.co/spaces/taruntippana/Diet_plan_suggestor)

#### [Stack Overflow Tags Prediction]
> **Python · TF-IDF · Scikit-learn · BeautifulSoup**

Scraped and classified 10,000+ multi-label data points with 80% accuracy using logistic regression. Demonstrates NLP preprocessing and multi-label classification skills.

[![Hugging Face Space](https://img.shields.io/badge/🤗-Live_Demo-yellow)](https://huggingface.co/spaces/taruntippana/stackoverflow_tags)

---


### 📫 Let's Connect

I'm open to collaborating on AI/ML projects and exploring new opportunities!

📧 taruntippana@gmail.com  
🔗 [Portfolio](https://my-portfolio-coral-three-c89n6s5uxy.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/tarun-tippana/) | [GitHub](https://github.com/tarun-tippana)

---

⭐ *"Building intelligent agents that solve real-world problems."*
