# 📉 HR Employee Attrition Prediction

## 📌 Project Overview
Employee attrition is a major cost for organizations. This project builds a machine learning pipeline to predict whether an employee will leave the company (Attrition: Yes/No) and identifies the key factors driving these decisions.

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost
- **Techniques:** Data Cleaning, Bivariate Analysis, Manual Oversampling, Model Benchmarking

## 📊 Model Evaluation Results
I evaluated 6 different classification models. While Boosting models showed high accuracy, **Logistic Regression** was selected as the champion model for its superior performance on imbalanced data metrics.

| Model | Accuracy | Recall | F1 Score | ROC-AUC |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | **0.854** | **0.538** | **0.494** | **0.772** |
| Gradient Boosting | 0.864 | 0.354 | 0.487 | 0.758 |
| XGBoost | 0.861 | 0.308 | 0.473 | 0.762 |

## 💡 Key Insights (Top Factors)
Based on Feature Importance, the top 3 reasons for attrition are:
1. **OStockOptionLevel** 
2. **JobLevel** 
3. **Department**

## 🚀 Business Recommendations
- Optimize Compensation & Benefits: Regularly review and benchmark stock option plans and job level compensation
- Enhance Employee Experience: Implement programs to boost job involvement and satisfaction,

