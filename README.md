# Telco Customer Churn Prediction
![image](https://github.com/user-attachments/assets/1906171e-17ac-4fae-b928-a6dae8e5238f)


## What is Customer Churn?

Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels.As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.

---

## Objectives:

- Finding the % of Churn Customers and customers that keep in with the active services.
- Analysing the data in terms of various features responsible for customer Churn
- Finding a most suited machine learning model for correct classification of Churn and non churn customers.

---

## Dataset:

[Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## The data set includes information about:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

## Implementation:

Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy

---

## 🤖 Modeling Approach

Trained and compared multiple classification models:

| Model               | Accuracy | F1 Score | ROC-AUC |
|--------------------|----------|----------|---------|
| Logistic Regression| 80%      | 0.75     | 0.84    |
| Decision Tree      | 79%      | 0.74     | 0.82    |
| Random Forest      | 83%      | 0.78     | 0.88    |
| XGBoost            | 85%      | 0.80     | 0.90    |

---

## Optimizations

We could use Hyperparamete Tuning or Feature enginnering methods to improve the accuracy further.

## 🙋‍♀️ About Me

Hi! I'm **Maguvarshini M**, a B.Tech AI & Data Science student.

- [GitHub](https://github.com/maghuvarshini)  
- [LinkedIn](https://linkedin.com/in/maguvarshinim)
- [E-mail](maguvarshini7@gmail.com)
