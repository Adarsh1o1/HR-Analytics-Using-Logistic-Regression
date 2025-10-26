# HR Analytics Churn Prediction using Logistic Regression

This project focuses on predicting employee churn (whether an employee will leave the organization) using Logistic Regression. It includes complete HR data analysis, feature engineering, and model evaluation to gain insights into employee retention strategies.

## 📌 Project Overview

Employee attrition leads to high recruitment and training costs. Using machine learning on HR data helps identify key factors contributing to churn and predict employees with a high probability of leaving.

This project includes:

- Exploratory Data Analysis (EDA)
- Data pre-processing and feature engineering
- Training a Logistic Regression model
- Model performance evaluation
- Interpretation of results and business implications

---

## 📊 Dataset

The dataset contains employee information like:

- Satisfaction level  
- Last evaluation score  
- Number of projects  
- Average monthly hours  
- Time spent in company  
- Work accidents  
- Promotions in the last 5 years  
- Salary level  
- Department  

**Target variable**: `left` (0 = Stayed, 1 = Left)

---

## 🧪 Methodology

1. **EDA**
   - Identified correlations and churn-driving features
   - Visualizations: heatmaps, distributions, count plots

2. **Data Processing**
   - Encoding categorical features
   - Scaling numerical features

3. **Modeling**
   - Logistic Regression with train/test split
   - Optimization using class balancing and threshold tuning

4. **Evaluation Metrics**
   - Accuracy
   - Confusion matrix
   - r2 score

---

## ✅ Key Results

- Logistic Regression performed well in classifying churn risk
- Certain features such as **low satisfaction level** and **high workload** strongly influence attrition
- The model helps HR departments focus retention strategies where needed most

(Add your actual accuracy, AUC, insights once you run your final model)

---

## 📈 Visualizations Included

- Churn distribution
- Salary vs churn
- Heatmap between `y_test` and `y_pred`
- ROC curve and confusion matrix




---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core Language |
| Pandas, NumPy | Data handling |
| Matplotlib, Seaborn | Visualizations |
| Scikit-Learn | Logistic Regression and evaluation |

![Deft who left](https://github.com/Adarsh1o1/HR-Analytics-Using-Logistic-Regression/blob/e804bc35157ecd9909649849e8c50bcb2e858e34/images/dept_left.png)

![Salaires who left](https://github.com/Adarsh1o1/HR-Analytics-Using-Logistic-Regression/blob/e804bc35157ecd9909649849e8c50bcb2e858e34/images/salary_left.png) 
![heatmap](https://github.com/Adarsh1o1/HR-Analytics-Using-Logistic-Regression/blob/e804bc35157ecd9909649849e8c50bcb2e858e34/images/heatmap.png)

---

## ✅ Key Results

- **Accuracy:** 75.89%
- **Confusion Matrix:**

  |                | Predicted Stay | Predicted Leave |
  |----------------|----------------|----------------|
  | Actual Stay    | 3156           | 272            |
  | Actual Leave   | 813            | 259            |

- The model correctly identifies most employees who stay, although it struggles more with predicting employees who leave.
- The results provide actionable insights for HR teams to investigate employees at higher risk of leaving the company.
