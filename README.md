# 📉 Customer Churn Prediction

> Predicting which telecom customers are likely to leave, using machine learning.

## 📌 Project Overview
Built a binary classification model on the IBM Telco Customer Churn dataset.  
Compared Logistic Regression vs Random Forest to find the best predictor.  
Used feature importance to identify key business drivers of churn.

## 📊 Dataset
| Property | Value |
|----------|-------|
| Source | IBM Telco Customer Churn |
| Rows | 7,043 customers |
| Features | 20 (contract, tenure, charges, services) |
| Target | Churn (Yes / No) |

## 🛠️ Tools Used
- Python 3, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LogisticRegression, RandomForest)

## 📈 Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80% |
| Random Forest | ~82% |

## 🔍 Key Findings
1. Month-to-month customers churn **3x more** than yearly contract customers
2. High monthly charges (> $65) strongly predict churn
3. New customers (tenure < 6 months) are the **highest risk** group
4. Fiber optic users churn more than DSL users

## 💡 Business Recommendations
- Offer loyalty discounts at the **3-month mark**
- Promote annual contracts with pricing incentives
- Flag high-charge new customers for proactive retention calls

## 🚀 How to Run
Click below to open directly in Google Colab — no setup needed:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/customer-churn-prediction/blob/main/Customer_Churn_Project.ipynb)

## 👤 Author
**Alok Roy Karmakar**  
[LinkedIn](https://www.linkedin.com/in/alokroykarmakar1994) | [GitHub](https://github.com/royalokkarmakar1994)
