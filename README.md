# 🤖 AI Job Recommendation System

> An intelligent web application that analyzes your skills or CV and recommends the most suitable jobs using Machine Learning and Deep Learning — built with KNN, Random Forest, and ANN.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ANN-orange?style=for-the-badge&logo=tensorflow)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-yellow?style=for-the-badge&logo=scikitlearn)

---

## 🎯 What It Does

Upload your **CV** or type your **skills** — the system will:
- Extract your skills using NLP
- Predict your best job category using 3 AI models
- Recommend **Top 5 jobs** with match percentages
- Show model accuracy comparison with progress bars

---

## 📊 Model Performance

| Model | Accuracy | Type |
|-------|----------|------|
| KNN | 78.65% | Baseline |
| Random Forest | 80.72% | Ensemble |
| ⭐ ANN | **84.32%** | Deep Learning |

> 🚀 ANN outperforms the baseline average by **+4.63%**

---

## ✨ Features

- 🌙 Dark modern UI with animated floating job icons
- 📄 CV upload support — PDF and DOCX
- ✍️ Manual skill input option
- 🧠 3 ML models running simultaneously
- 💼 Top 5 job recommendations with match %
- 📊 Live accuracy comparison with animated progress bars
- 🔷 Confusion matrix for all 3 models
- 🥇 Gold / Silver / Bronze rank badges for jobs

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.10 |
| Deep Learning | TensorFlow / Keras |
| Machine Learning | Scikit-learn |
| NLP | TF-IDF Vectorizer |
| Web Framework | Flask |
| CV Parsing | PyPDF2, python-docx |
| Visualization | Matplotlib, Seaborn |
| Frontend | HTML, CSS, JavaScript, Canvas API |

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/AI-Job-Recommendation-System.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
python app.py
```

Then open your browser at: http://127.0.0.1:5000


---
## 📁 Project Structure

```
AI_Job_Recommendation/
│
├── notebooks/
│   ├── 1_eda.py              ← Data exploration
│   ├── 2_preprocessing.py    ← TF-IDF + train/test split
│   └── 3_models.py           ← KNN, Random Forest, ANN training
│
├── templates/
│   └── index.html            ← Dark modern web UI
│
├── app.py                    ← Flask backend + recommendation logic
└── requirements.txt          ← All dependencies

---

## 🧠 How It Works

```
User Input (Skills / CV)
         ↓
  NLP Skill Extraction
         ↓
   TF-IDF Vectorizer
         ↓
  ┌──────┬─────────────────┬──────┐
  │ KNN  │  Random Forest  │ ANN  │
  └──────┴─────────────────┴──────┘
         ↓
  Top 5 Job Recommendations
     with Match Percentage
```

---

## 👨‍💻 Author

**Adarsh Bhatia**  
Iqra University — AI Lab Final Project — June 2026
