# 🛒 Customer Retail Data Analysis Using Machine Learning Models

**Final Machine Learning Project Report**  
**Prepared by: N. Abishan**

---

## 📌 Project Overview

This project implements and compares multiple Machine Learning classification algorithms using a customer retail dataset. The complete ML pipeline is covered — from data preprocessing and visualization to model training, evaluation, and performance comparison.

---

## 🎯 Objectives

- Preprocess and clean the customer retail dataset
- Handle missing values and encode categorical data
- Visualize data distribution using Matplotlib
- Train and evaluate three ML classification models
- Compare model performance using accuracy scores

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `Customer_Retail_ML_Project.ipynb` | Google Colab Jupyter Notebook with full code and outputs |
| `customer_retail_ml_project.py` | Python script version of the project |
| `MLP_Professional_Report_Abishan.pdf` | Full project report (7 pages) |

---

## 🗃️ Dataset

The dataset used is a **customer retail dataset** containing sales transaction records.

**Features used:**
- `Quantity` — number of units sold per transaction
- `UnitPrice` — price per unit
- `Country` — geographic origin of the transaction

**Target variable:**
- `1` → Quantity > 10 (High volume)
- `0` → Quantity ≤ 10 (Standard volume)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Primary programming language |
| Google Colab | Cloud-based development environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Scikit-learn | ML model implementation and evaluation |

---

## 🤖 Machine Learning Models

| Model | Description |
|-------|-------------|
| Logistic Regression | Supervised binary classification using sigmoid function |
| Decision Tree Classifier | Tree-based model for classification and prediction |
| K-Nearest Neighbors (KNN) | Instance-based classifier using nearest neighbours |

---

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 1.0000 (100%) |
| Decision Tree Classifier | 1.0000 (100%) |
| K-Nearest Neighbors (KNN) | 0.9999 (99.99%) |

All three models achieved exceptional accuracy on the dataset.

---

## ⚙️ How to Run

1. Open `Customer_Retail_ML_Project.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload the `customer_retail csv file (1).csv` dataset when prompted
3. Run all cells in order

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Google Colab](https://colab.research.google.com)
- [Python Documentation](https://docs.python.org/3/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

---

*Final Machine Learning Project — N. Abishan*
