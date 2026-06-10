# 🧠 Parkinson's Disease Severity Prediction

![Status](https://img.shields.io/badge/Status-Work%20In%20Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Type-Machine%20Learning-green)
![Dataset](https://img.shields.io/badge/Dataset-UCI-orange)

Predicting the severity of Parkinson's Disease symptoms using
Machine Learning on biomedical voice measurements.

---

## 📌 About

Parkinson's Disease is a neurological disorder where early monitoring
of symptom severity is critical for better treatment outcomes.

This project uses voice-based biomarkers to predict the **UPDRS score**
— a standard clinical measure of Parkinson's severity.
No hardware or sensors required. Just voice data.

> Inspired by **CortiCare** — Smart India Hackathon 2025 (SH25218)

---

## 📊 Dataset

**Oxford Parkinson's Disease Telemonitoring Dataset**
[UCI ML Repository](https://archive.ics.uci.edu/dataset/174/parkinsons)

- 5,875 voice recordings from 42 patients
- 22 features — Jitter, Shimmer, HNR, RPDE, DFA, PPE
- Target → `total_UPDRS` severity score

---

## 🔄 Project Workflow

```
Data Loading → EDA → Preprocessing → Model Training → Evaluation → Web App
```

---

## 🤖 ML Models

| Model | Status | MAE | RMSE | R² |
|---|---|---|---|---|
| Linear Regression | ✅ Done | 8.05 | 9.65 | 0.15 |
| Random Forest Regressor | 🔄 In Progress | - | - | - |
| XGBoost Regressor | ⏳ Pending | - | - | - |

---

## 📁 Project Structure

```
Parkinson_Early_Detection/
│
├── data/
│   └── parkinsons_updrs.data
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── linear_regression.ipynb
│   ├── random_forest.ipynb
│   └── xgboost.ipynb
│
├── models/
│   └── best_model.pkl
│
├── app/
│   └── app.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
joblib
streamlit
```

---

## 🚧 Status

EDA and Linear Regression completed.
Random Forest and XGBoost in progress.

---

## 👤 Author

**[Shanu Jha]**
