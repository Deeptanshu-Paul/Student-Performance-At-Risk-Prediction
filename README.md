# 🎓 Student Performance Prediction & At-Risk Identification System

## 📌 Project Overview

This project develops a machine learning-based system for predicting student academic performance and identifying students who may be academically at risk.

The system performs two major tasks:

- Five-class student grade prediction
- Binary At-Risk student identification

The objective is to provide an early-warning system that can help educators identify students who may require additional academic support.

---

## 📊 Dataset

The dataset contains **9,997 student records**.

### At-Risk Distribution

| Category | Students | Percentage |
|---|---:|---:|
| Not At Risk | 9,264 | 92.67% |
| At Risk | 733 | 7.33% |
| **Total** | **9,997** | **100%** |

The dataset contains demographic, educational, and academic-preparation features.

---

## 🤖 Machine Learning Models

The following algorithms were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

---

## 🎯 Five-Class Grade Prediction

The system predicts five academic performance categories:

- A
- B
- C
- D
- Fail

### Best Model

**Gradient Boosting**

| Metric | Score |
|---|---:|
| Accuracy | **56.35%** |
| Weighted Precision | **42.68%** |
| Weighted Recall | **56.35%** |
| Weighted F1 Score | **42.84%** |

---

## ⚠️ At-Risk Student Identification

A dedicated binary classification model was developed to identify students who may be academically at risk.

### Final Model

**Random Forest**

### Selected Probability Threshold

**0.60**

| Metric | Score |
|---|---:|
| Accuracy | **65.70%** |
| Precision | **13.92%** |
| Recall | **70.75%** |
| F1 Score | **23.27%** |
| Specificity | **65.30%** |
| ROC-AUC | **0.7067** |
| PR-AUC | **0.1263** |

The relatively high recall makes the model useful as an early-warning mechanism because identifying potentially struggling students is a major objective.
