# Customer Churn Prediction — Bank Customers

Predicting which bank customers are likely to leave using supervised machine learning. Built as part of my data science internship at Developers Hub Corporation.

---

## Problem Statement

Customer churn is one of the most expensive problems in retail banking — acquiring a new customer costs 5–7x more than retaining an existing one. This project builds a classification model to identify at-risk customers before they leave, and surfaces the key factors driving churn.

---

## Dataset

**Source:** [Churn Modelling Dataset — Kaggle](https://www.kaggle.com/datasets/shubh0799/churn-modelling)  
10,000 bank customer records | 13 features | Target: `Exited` (1 = churned, 0 = stayed)

---

## Tech Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn

---

## Project Workflow

```
1. Data Cleaning        
2. Encoding              
3. EDA                   
4. Model Training       
5. Evaluation          
6. Feature Importance   
```

---

## Results

| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 80.80% | 0.775 |
| Decision Tree | 85.60% | 0.842 |
| **Random Forest** | **86.90%** | **0.866** |

Random Forest outperformed both models across accuracy and AUC.

---

## Key Insights

1. Age is the strongest churn predictor customers aged 40–60 churn significantly more
2. Customers with 2 products are the most loyal; single product customers are high risk
3. Inactive members churn at roughly 2x the rate of active members
4. High-balance customers churn more consistent with having more banking options elsewhere
5. Germany shows disproportionately high churn compared to France and Spain

---

## Author

**Aiman Ishaq**  CS Student | Data Analyst Intern @ Developers Hub Corporation  
[LinkedIn](https://linkedin.com/in/aiman-ishaq) · [GitHub](https://github.com/aiman-ami)
