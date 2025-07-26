# 🧠 Marketing Campaign Customer Affinity Analysis

The project focuses on analyzing a retail marketing campaign dataset to predict high-value customers (`AFFINITY_CARD = 1`) using structured data processing, statistical analysis, and machine learning.


---

## 📦 Dataset Overview

- **File**: [`marketing_campaign.csv`](https://github.com/Irin-Thomas/Marketing-Campaign-Customer-Analysis/blob/main/Dataset/Marketing%20Campaign%20data.csv)
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

- [Code -> Code for the project](https://github.com/Irin-Thomas/Marketing-Campaign-Customer-Analysis/tree/main/Code) 
- [Dataset -> Dataset used in the code](https://github.com/Irin-Thomas/Marketing-Campaign-Customer-Analysis/blob/main/Dataset/Marketing%20Campaign%20data.csv)
- [Report -> Report about everything done in the project](https://github.com/Irin-Thomas/Marketing-Campaign-Customer-Analysis/blob/main/Report/IRIN%20%20PYTHON%20REPORT.pdf)
---


## 📦 Project Deliverables

| #    | Description                                                                 |
|------|------------------------------------------------------------------------------|
| 1    | Metadata summary and missing/error analysis                                  |
| 2    | Data cleaning and feature transformation (binary, ordinal, one-hot encoding)|
| 3    | Correlation matrix and sentiment analysis                                    |
| 4    | Interactive histogram display script                                         |
| 5    | Logistic regression model, evaluation, and prediction interface              |
| 6    | Technical report with findings, reflections, and recommendations             |


---

## 🔍 Key Insights

- High-value customers are often:
  - Educated and long-term residents
  - Interested in tech products
- Model achieved **78% accuracy**, but struggled with recall due to class imbalance.
- Sentiment analysis of `COMMENTS` had limited influence on prediction, suggesting a need for better text processing techniques.

---
## 📚 References
Citations and source materials are listed in the final report PDF [IRIN PYTHON REPORT.pdf](https://github.com/Irin-Thomas/Marketing-Campaign-Customer-Analysis/blob/main/Report/IRIN%20%20PYTHON%20REPORT.pdf) 

## 📬 Contact
Author: Irin Mary Thomas

Email: irinthomas0@gmail.com
