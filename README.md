# 🌸 Iris Flower Classification

A beginner-friendly Machine Learning project that classifies Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using a Random Forest Classifier.

Built as **Task 1** of my **Data Science Internship at CodeAlpha**.

---

## 📌 Project Overview

The Iris dataset is one of the most well-known datasets in Machine Learning. This project walks through the complete ML pipeline — from loading data to evaluating the model — in a clean, step-by-step format.

| Detail | Info |
|--------|------|
| Dataset | Iris (via `sklearn.datasets`) |
| Algorithm | Random Forest Classifier |
| Language | Python 3 |
| Platform | Google Colab |
| Accuracy | **100%** on test data |

---

## 🌺 Classes (Target Labels)

| Class | Species |
|-------|---------|
| 0 | Setosa |
| 1 | Versicolor |
| 2 | Virginica |

---

## 📊 Dataset Details

- **Total Samples:** 150 (50 per class)
- **Features:** 4
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)

---

## 🔁 Project Pipeline

```
Step 1 → Load Dataset
Step 2 → Train/Test Split (80% train, 20% test)
Step 3 → Train Random Forest (100 trees)
Step 4 → Predict on Test Data
Step 5 → Evaluate Accuracy
Step 6 → Classification Report
Step 7 → Confusion Matrix
Step 8 → Predict a New Flower
```

---

## 📈 Results

- **Accuracy:** 100% (30/30 test samples correct)
- **Model:** Random Forest Classifier (`n_estimators=100`, `random_state=42`)

### Confusion Matrix

|  | Setosa | Versicolor | Virginica |
|--|--------|------------|-----------|
| **Setosa** | 10 | 0 | 0 |
| **Versicolor** | 0 | 9 | 0 |
| **Virginica** | 0 | 0 | 11 |

---

## 🚀 How to Run

**Option 1: Google Colab (Recommended)**

Open in Colab and run all cells — no setup needed.

**Option 2: Local**

```bash
pip install scikit-learn
python code_alpha_project_1.py
```

---

## 🧠 Key Concepts Learned

- Loading built-in datasets with `sklearn.datasets`
- Train/test splitting with `train_test_split`
- Training a `RandomForestClassifier`
- Evaluating with `accuracy_score`, `classification_report`, and `confusion_matrix`
- Making predictions on new/unseen data

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow?logo=googlecolab)

---

## 👨‍💻 Author

**Vinay Kumar**
B.Tech CSE (AI & Data Science) — Apeejay Stya University, Gurugram
Data Science Intern @ CodeAlpha

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vinayyadav011-blue?logo=linkedin)](https://www.linkedin.com/in/vinayyadav011)
[![Kaggle](https://img.shields.io/badge/Kaggle-vinayyadav011-20BEFF?logo=kaggle)](https://www.kaggle.com/vinayyadav011)
[![GitHub](https://img.shields.io/badge/GitHub-Vinay--Kumar--011-black?logo=github)](https://github.com/Vinay-Kumar-011)

---

## 📁 Repository Structure

```
iris-flower-classification/
│
├── code_alpha_project_1.py   # Main Python script
└── README.md                 # Project documentation
```

---

> *This project was completed as part of the CodeAlpha Data Science Internship — Task 1: Iris Flower Classification.*
