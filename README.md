# 🧠 Breast Cancer Classification (Machine Learning Project)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

This project focuses on building a **machine learning classification model** to predict whether a tumor is **malignant or benign** using the Breast Cancer dataset.

The project demonstrates a complete ML workflow including:

* Data preprocessing
* Model training
* Evaluation using advanced metrics
* Model improvement techniques

---

## 🎯 Objectives

* Build a reliable classification model
* Evaluate using real-world metrics (not just accuracy)
* Handle class imbalance
* Compare multiple models

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib
* Scikit-learn

---

## 🔄 Workflow

1. 📥 Data Loading
2. 🔀 Train-Test Split
3. ⚖️ Feature Scaling (StandardScaler)
4. 🤖 Model Training

   * Logistic Regression
   * Decision Tree
5. 📊 Model Evaluation

   * Confusion Matrix
   * Precision, Recall, F1-score
6. 📈 ROC Curve & AUC Score
7. ⚠️ Handling Class Imbalance
8. 🏆 Model Comparison & Selection

---

## 📊 Evaluation Metrics

| Metric    | Description                            |
| --------- | -------------------------------------- |
| Precision | Accuracy of positive predictions       |
| Recall    | Ability to detect actual positives ⚠️  |
| F1-score  | Balance of precision & recall          |
| ROC-AUC   | Model's ability to distinguish classes |

---

## 🧠 Key Insights

* ❌ Accuracy alone is misleading for imbalanced data
* ⚠️ Recall is critical in medical diagnosis
* 📈 ROC-AUC provides better performance understanding
* ⚖️ Class balancing improves detection of minority class

---

## 🏆 Final Model

✅ **Balanced Logistic Regression**

**Reason:**

* Better recall (important for cancer detection)
* More stable than Decision Tree
* Handles class imbalance effectively

---

## 📁 Project Structure

```bash
AI_ML_Task_4/
│
├── notebook.ipynb
├── ML_Task4_Advanced_Report.pdf
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 📸 Sample Output

* ROC Curve 📈
* Confusion Matrix
* Classification Report

---

## 📚 Learnings

This project helped in understanding:

* Real-world model evaluation
* Importance of recall in critical systems
* Handling imbalanced datasets
* Model comparison techniques

---

## 👨‍💻 Author

**Abhishek Rai**
Machine Learning Enthusiast 🚀

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
