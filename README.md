# 🧑‍💻 Job Candidate Recommender System  
**A Job Candidate Recommendation System using Sentence-BERT and Cosine Similarity**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📖 Description
This project is the implementation of my undergraduate thesis titled  
**“Job Candidate Recommendation System using Sentence-BERT and Cosine Similarity.”**

The goal is to help companies select the most suitable candidates for job vacancies based on **skill matching**.

The following methods are compared:
- **TF-IDF** → frequency-based word representation
- **Sentence-BERT (SBERT)** → semantic embeddings representation
- **Hybrid (TF-IDF + SBERT)** → a combination of both

---

## ✨ Features
- Upload candidate & job vacancy datasets (CSV)  
- Text preprocessing (case folding, tokenization, stopword removal, lemmatization)  
- Similarity calculation with Cosine Similarity  
- Recommendation methods: **TF-IDF**, **SBERT**, and **Hybrid**  
- Candidate ranking based on similarity scores  
- Result visualization (method comparison charts, candidate ranking tables)

---

## 🚀 Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/USERNAME/job-recommender-sbert.git
   cd job-recommender-sbert
2. Run the Streamlit app:
   ```bash
   streamlit run app/main.py


  
