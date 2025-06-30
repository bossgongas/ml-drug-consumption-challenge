# 🧠 ML Challenge – Drug Consumption Classification

This project was developed as part of the course **Aprendizagem Computacional / Machine Learning (2023)** at the **Department of Informatics Engineering (DEI), Faculty of Science and Technology, University of Coimbra**.

---

## 🎯 Objective

To solve a real-world binary classification problem using simple machine learning models. The case study focuses on predicting the consumption of alcohol, nicotine, and cannabis based on personal and psychological traits from a public dataset.

---

## 📊 Dataset

- **Source**: Public dataset with 1885 respondents
- **Features**: Age, gender, education, neuroticism, extraversion, openness, agreeableness, conscientiousness, impulsiveness, sensation seeking
- **Target**: Consumption status of alcohol, nicotine, and cannabis (binary: consumer / non-consumer)
- **Preprocessing**:
  - Removed fake responses (e.g., consumers of fictitious drug *Semeron*)
  - Encoded categorical variables
  - Dropped nationality and ethnicity for simplification

---

## 🧪 Models and Methodology

Two ML models were implemented and compared:

### 1. **Decision Tree**
- Criterion: Entropy and Gini
- Best F1-Score: **0.75** (Entropy)

### 2. **K-Nearest Neighbors (KNN)**
- Best result at **k=22**
- F1-Score: **0.80**

**Evaluation metric used**: Confusion Matrix and derived metrics (Accuracy, Precision, F1-Score)

---

## 📂 Files

- [`ML_Challenge.pdf`](./ML_Challenge.pdf) – Final report
- [`2023-MLChallenge.pdf`](./2023-MLChallenge.pdf) – Official challenge description
- [`src/`](./src/) – Python code and notebooks for training and evaluation

---

## 👨‍🎓 Authors

- **Gonçalo Tavares de Bastos** – nº 2020238997  
- **Leonardo Cordeiro Gonçalves** – nº 2020228071  

📅 Submitted: March 2023
