# 🧠 Marketing Campaign Customer Affinity Analysis

This repository contains the complete coursework project for **CC7182: Programming for Analytics (Spring 2024–2025)**. The project focuses on analyzing a retail marketing campaign dataset to predict high-value customers (`AFFINITY_CARD = 1`) using structured data processing, statistical analysis, and machine learning.

📅 **Submission Date**: 9th May 2025  
👤 **Student Name**: *Irin Thomas*  
🏫 **Institution**: London Metropolitan University

---

## 📦 Dataset Overview

- **File**: `marketing_campaign.csv`
- **Records**: 1500 customers
- **Variables**: 19 attributes including socio-demographic data, product ownership, and `COMMENTS`.
- **Target Variable**: `AFFINITY_CARD` (1 = High-value, 0 = Low-value)

---

## 🎯 Project Objectives

- Understand and summarize the dataset through metadata and missing/error analysis.
- Prepare and clean data for predictive modeling.
- Perform transformations: encoding, normalization, ordinal ranking.
- Conduct exploratory analysis and sentiment analysis.
- Build a **logistic regression model** to predict customer value.
- Evaluate the model and build a **user-facing predictive application**.

---

## 🛠️ Technologies Used

- **Language**: Python 3.10
- **Libraries**:
  - `pandas`, `numpy`, `scikit-learn`
  - `matplotlib`, `seaborn`
  - `nltk`, `textblob` (for sentiment analysis)
  - `ipywidgets`, `tkinter` (for interactive interface)

---

## 📂 Folder Structure


---

## ✅ Task Checklist

| Task ID | Description                                                             | Status |
|--------|-------------------------------------------------------------------------|--------|
| 1      | Metadata summary + missing/error analysis                               | ✅     |
| 2      | Data cleaning + feature transformation (binary, ordinal, one-hot)       | ✅     |
| 3      | Correlation matrix + sentiment analysis                                 | ✅     |
| 4      | Interactive histogram display script                                    | ✅     |
| 5      | Logistic regression model build, evaluation, prediction app             | ✅     |
| 6      | Technical report with findings, reflections, and recommendations        | ✅     |

---

## 🔍 Key Insights

- High-value customers are often:
  - Educated and long-term residents
  - Interested in tech products
- Model achieved **78% accuracy**, but struggled with recall due to class imbalance.
- Sentiment analysis of `COMMENTS` had limited influence on prediction, suggesting a need for better text processing techniques.

---
## ✍️ Author
Irin Thomas
irinthomas0.thomas@gmail.com 
