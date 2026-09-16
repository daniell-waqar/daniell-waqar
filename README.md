<div align="center">

# Hey, I'm Waqar Ahmed 👋
### AI Engineer @ Visualyfe · ML / NLP / Deep Learning · Full-Stack (React · Next.js)

Computer Science grad turning messy real-world data into models that actually ship —
and building the interfaces people use to reach them.

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00C4B4&center=true&vCenter=true&width=600&lines=Building+ML+pipelines+end-to-end;From+raw+data+to+deployed+model;Currently%3A+LangChain+%2B+RAG+%2B+Agents)

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB_USERNAME)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:waqarahmedme7@gmail.com)

</div>

---

## 🧭 Where I am right now

```mermaid
timeline
    title My path so far
    2021 - 2025 : BS Computer Science, FAST NUCES Karachi
    Nov 2024 - Jan 2025 : Front-End Dev Intern @ Reallytics.ai
                        : React + Next.js + Firebase
    Feb 2025 - Present : AI Engineer @ Visualyfe
                       : ML, DL, NLP, model deployment
    Sep 2025 - Dec 2025 : Python Instructor @ Source Code Academy
```

---

## 🧠 How I build ML/AI systems

```mermaid
flowchart LR
    A[Raw / Messy Data] --> B[EDA + Cleaning<br/>outlier detection]
    B --> C[Feature Engineering]
    C --> D{Model Type?}
    D -->|Tabular| E[XGBoost / Random Forest]
    D -->|Text| F[BERT / TF-IDF / Word2Vec]
    D -->|Vision| G[CNN / ResNet / ViT]
    E --> H[Hyperparameter Tuning]
    F --> H
    G --> H
    H --> I[Deployment<br/>Flask · FastAPI · Streamlit]
    I --> J[React / Next.js Frontend]
```

Every project below is a real pass through this pipeline — not a tutorial dataset.

---

## 🚀 Featured Projects

### 🚕 Uber Fare Prediction
**Problem:** Raw ride data is noisy — corrupted GPS points, missing fares, no obvious signal.
**What I did:**
- Cleaned **190k+ real Uber trips**, removing under 5% of records using IQR + percentile outlier detection
- Implemented the **Haversine formula from scratch** to compute trip distance from raw GPS — it became the single most important feature at **90% model importance**
- Engineered temporal features (rush hour, night, weekend flags) to capture NYC pricing patterns
- Compared Linear Regression, Random Forest, and Gradient Boosting

**Result:** Gradient Boosting won with **R² of 0.83** and **RMSE of $3.50** — then shipped as a live interactive Streamlit app.

`Python` `Scikit-learn` `Pandas` `NumPy` `Streamlit`

[![Live Demo](https://img.shields.io/badge/Live-Demo-00C4B4?style=flat-square&logo=streamlit&logoColor=white)](#)
[![Repo](https://img.shields.io/badge/View-Repo-181717?style=flat-square&logo=github)](#)

---

### 🩺 GraphMedX
**Problem:** Clinical notes are unstructured — relationships between symptoms, diagnoses, and treatments stay buried in free text.
**What I did:**
- Built an **NLP pipeline** to extract medical entities from unstructured clinical text
- Linked extracted entities into a **knowledge graph** using NetworkX
- Surfaced non-obvious relationships between symptoms, diagnoses, and treatments via graph algorithms

`Python` `NLTK` `NetworkX` `OpenAI API` `PyTesseract`

[![Repo](https://img.shields.io/badge/View-Repo-181717?style=flat-square&logo=github)](#)

---

## 🛠️ Tech Stack

<div align="center">

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**ML / AI**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**Web**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Tools**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true" width="35%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" width="49%" />

</div>

---

## 🎓 Education & Certifications

**BS Computer Science** — FAST National University of Computer and Emerging Sciences, Karachi (2021–2025)

- IBM Data Analyst
- Google Advanced Python Programming
- Prodigy InfoTech — Machine Learning Internship
- Visualyfe — Internship Completion + Recommendation Letter

---

<div align="center">

**Currently exploring:** agentic RAG systems, LangChain-based pipelines, and making deployed models survive contact with real users.

📫 **waqarahmedme7@gmail.com**

</div>
