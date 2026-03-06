# 📧 Spam Mail Prediction using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.9-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Accuracy](https://img.shields.io/badge/Accuracy-97%25-brightgreen)

## 📋 Project Overview
An end-to-end Machine Learning project to classify emails/SMS as **spam** or **ham (not spam)** using **Logistic Regression**. The model achieves **97% accuracy** on test data with comprehensive evaluation metrics.

This project demonstrates the complete ML workflow from data preprocessing to model evaluation with professional visualizations.

---

## 🎯 Objective
To build a robust spam detection system that can automatically identify unwanted messages, helping users filter out spam emails and SMS effectively.

---

## 🧠 Model Performance

| Metric | Score |
|--------|-------|
| **Accuracy** | 97% |
| **Precision** | 98% |
| **Recall** | 96% |
| **F1 Score** | 97% |
| **AUC-ROC** | 0.99 |

---

## 📸 Visualizations

### 1. Confusion Matrix
![2-Capture](https://github.com/user-attachments/assets/f3fec774-47d7-4d00-9245-cf4d0a02c3ff)

*Shows true positives, false positives, true negatives, and false negatives*

### 2. Model Accuracy Comparison
![3-Capture](https://github.com/user-attachments/assets/0ea58f32-bb99-440e-b818-d888144333e3)

*Training vs Test Accuracy - no overfitting detected*

### 3. ROC Curve
![33-Capture](https://github.com/user-attachments/assets/55512be1-08ef-47d9-847d-7c0b62a63813)

*ROC curve with AUC = 0.99, indicating excellent model performance*

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy)
- **Scikit-learn** (Logistic Regression, TfidfVectorizer)
- **Matplotlib & Seaborn** (Data Visualization)
- **Jupyter Notebook** (Development)

---

## 🚀 Project Pipeline
- 1️⃣ Data Loading → Load mail_data.csv
- 2️⃣ Data Preprocessing → Map categories (spam:0, ham:1)
- 3️⃣ Feature Extraction → TF-IDF Vectorization
- 4️⃣ Train-Test Split → 80-20 split with random_state=3
- 5️⃣ Model Training → Logistic Regression
- 6️⃣ Evaluation → Accuracy, Confusion Matrix, ROC Curve, Precision, Recall, F1

---

## 👨‍💻 Author
**Mehfooz Ali**  
Aspiring AI Engineer | Software Engineer

### ⭐ Show your support
Give a ⭐ if this project helped you!
