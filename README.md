# 📞 Telco Customer Churn Prediction

## 🧠 Project Motivation

Customer churn directly impacts the revenue of telecom companies. This project aims to build a predictive model to identify customers who are likely to churn so that proactive retention strategies can be applied.

---

## 🧾 Dataset Overview

- **Source**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Observations**: 7,043
- **Features**: 21 columns including demographics, account info, and usage behavior
- **Target**: `Churn` (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution of churn across various categories. Key findings include:

- Month-to-month contract customers show higher churn.
- Electronic check payment method correlates with churn.
- Customers without dependents or tech support tend to churn more.

📌 *Sample Plot: Churn rate by contract type*
![newplot](https://github.com/user-attachments/assets/c0e8abaf-b2e3-4c0e-b8aa-432a94307a4e)

## 🔧 Feature Engineering

- Converted categorical features using One-Hot Encoding
- Replaced "No internet service" and "No phone service" with "No"
- Standardized numerical columns
- Created new feature: `TotalServices`

---

## 🤖 Modeling Approach

Trained and compared multiple classification models:

| Model               | Accuracy | F1 Score | ROC-AUC |
|--------------------|----------|----------|---------|
| Logistic Regression| 80%      | 0.75     | 0.84    |
| Decision Tree      | 79%      | 0.74     | 0.82    |
| Random Forest      | 83%      | 0.78     | 0.88    |
| XGBoost            | 85%      | 0.80     | 0.90    |

📌 *ROC Curve and Confusion Matrix visualizations below*
![Confusion matrix models](https://github.com/user-attachments/assets/59453279-a876-425c-838b-fcf910c2ea3c)
![Confusion matrix models 2](https://github.com/user-attachments/assets/49afd3fe-9770-4568-b115-823fc1fa2cb1)
![Confusion matrix models 3](https://github.com/user-attachments/assets/76a5d755-d324-4777-8241-73eafc4a2cfe)
