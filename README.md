# ❤️ Heart Disease Prediction using Machine Learning

> A Data Mining project focused on predicting coronary heart disease using Machine Learning techniques and the UCI Cleveland Heart Disease dataset.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Cardiovascular diseases remain one of the leading causes of death worldwide. Early diagnosis can significantly improve patient outcomes.

This project develops a complete **Machine Learning pipeline** to classify whether a patient has coronary heart disease based on clinical information from the **UCI Cleveland Heart Disease Dataset**.

The workflow follows the **CRISP-DM methodology**, including:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Preprocessing
- Machine Learning Modeling
- Performance Evaluation
- Result Interpretation

---

## 🎯 Objectives

- Explore and understand the medical dataset.
- Clean and preprocess clinical features.
- Compare multiple Machine Learning algorithms.
- Evaluate models using medical-oriented metrics.
- Identify the best-performing classifier.

---

## 📊 Dataset

**Dataset:** UCI Cleveland Heart Disease Dataset

- 303 patient records
- 14 clinical attributes
- Binary classification
  - Healthy
  - Heart Disease

Main features include:

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Maximum Heart Rate
- ST Depression
- Number of Major Vessels
- Thalassemia

---

## ⚙️ Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 🔄 Machine Learning Pipeline

The project follows these steps:

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Data Preprocessing
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
```

---

## 🤖 Models Evaluated

The following algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## 🏆 Results

| Model | Accuracy | ROC-AUC |
|--------|----------|---------|
| Logistic Regression | 86.9% | 0.962 |
| Decision Tree | 72.1% | 0.787 |
| Random Forest | 86.9% | 0.944 |
| **Support Vector Machine (RBF)** | **≈90%** | **0.970** |

The **Support Vector Machine (RBF Kernel)** achieved the best overall performance while maintaining an excellent Recall, making it the preferred model for medical diagnosis.

---

## 📂 Project Structure

```
Heart-Disease-Prediction/
│
├── Projet_Final.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Ihssanemoutchou/Heart-Disease-Prediction.git
```

Move into the project

```bash
cd Heart-Disease-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Learning Outcomes

Through this project we gained experience in:

- Data Mining
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Medical Data Analysis
- Model Evaluation
- Scikit-Learn Pipelines

---

## 👨‍💻 Authors

**Ihssane Moutchou**

- GitHub: https://github.com/Ihssanemoutchou

**Aymen Ichqarrane**

- GitHub: https://github.com/aymenichqa
---

## 📄 Academic Project

Engineering School of Management and Computer Science (EMSI)

Academic Data Mining Project

---

⭐ If you found this project useful, don't forget to leave a star!
