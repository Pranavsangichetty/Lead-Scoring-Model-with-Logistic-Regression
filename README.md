# 🚀 Lead Scoring Using Machine Learning (Logistic Regression)

## 📌 Project Overview

This project focuses on building a **lead scoring model** that predicts the likelihood of a lead converting into a customer.
Using **Supervised Machine Learning (Logistic Regression)**, the model analyzes customer attributes and engagement patterns to help businesses prioritize high-intent leads and improve sales efficiency.

The dataset contains multiple customer behavior features such as lead source, website activity, last interaction, and more.

---

## 🎯 Objectives

* To build a predictive model that classifies leads as **Converted (1)** or **Not Converted (0)**
* To identify the most influential variables driving conversions
* To assist the sales and marketing teams with actionable insights
* To suggest decision strategies based on different business scenarios (high recall vs high precision)

---

## 🧼 1. Data Cleaning

* Removed duplicate records
* Handled missing values using imputers
* Standardized numerical features
* Encoded categorical variables using One-Hot and Ordinal Encoding
* Removed identifier columns that do not contribute to prediction

---

## 🧠 2. Model Used — Logistic Regression

A **supervised classification algorithm**, suitable because:

* The target variable is binary (Converted = 0/1)
* It provides interpretable coefficients
* It outputs probability scores ideal for lead ranking
* Fast, scalable, and widely used in marketing analytics

---

## ⚙️ 3. Preprocessing Steps

* **Numerical Columns** → Median imputation + Standard Scaling
* **Low-cardinality Categorical Columns** → One-Hot Encoding
* **High-cardinality Categorical Columns** → Ordinal Encoding
* Combined using **ColumnTransformer**
* Pipeline created for easy training and inference

---

## 📊 4. Model Evaluation

| Metric    | Score |
| --------- | ----- |
| Accuracy  | ~0.81 |
| Precision | ~0.79 |
| Recall    | ~0.70 |
| F1-Score  | ~0.74 |
| ROC-AUC   | ~0.88 |

Excellent balance between business interpretability and predictive performance.

---

## 🔍 5. Key Insights (Feature Importance)

Top variables contributing to lead conversion:

1. **Total Time Spent on Website**
2. **Lead Origin: Lead Add Form**
3. **Last Activity: Email Opened**

These features indicate engagement, intent, and active marketing interaction.

---

## 📝 6. Assignment Subjective Questions & Answers

The project also answers 4 business-focused questions, including:

* Top converting variables
* Most influential categorical features
* Strategy during periods with extra interns (high recall)
* Strategy when the sales target is achieved early (high precision)

All answers are included as separate PDF files in the repository.

---

## 🧩 8. Technologies Used

* Python
* Pandas, NumPy
* Scikit-Learn
* Logistic Regression
* ReportLab (PDF generation)
* Jupyter Notebook

---

## 🤝 10. Contributions

Pull requests and improvements are welcome!

---
