# 📞 SyriaTel Customer Churn Prediction

This project aims to develop a machine learning model to predict customer churn for SyriaTel, a telecommunications company. By identifying at-risk customers and understanding key churn drivers, the business can take proactive steps to retain valuable customers and reduce attrition.

---

## 📚 Table of Contents

1. Project Overview 
2. Objectives
- Analysis Objectives
- Modelling Objectives  
3. Dataset Description  
4. Data Preprocessing 
5. Exploratory Data Analysis (EDA)  
6. Modeling 
7. Model Evaluation 
9. Business Insights & Recommendations
10. Conclusion  

---

## 🧠 Project Overview

Customer churn is a major concern for telecom providers. This project builds a predictive model that flags customers likely to churn, analyzes behavioral patterns of at-risk users, and provides actionable business recommendations to help SyriaTel improve customer retention.

---

## 🎯 Objectives

### 🔍 Analysis Objectives
1. Identify key behavioral and demographic factors influencing customer churn.
2. Profile at-risk customers to support targeted business interventions.

### 🤖 Modeling Objectives
1. Build a robust binary classification model to predict churn using SMOTE for imbalance handling.
2. Generate churn risk scores to support proactive retention strategies.

---

## 📊 Dataset Description

The dataset contains customer information such as:
- Account length
- Call usage patterns (international, day, evening, night)
- Customer service calls
- Voicemail and international plans
- Churn label (True/False)

---

## 🧹 Data Preprocessing

- Handled missing values and encoded categorical variables  
- Applied SMOTE to balance the dataset  
- Split data into training and test sets  
- Scaled features for models that require it

---

## 📈 Exploratory Data Analysis (EDA)

Key findings from EDA:
- Churn is more common among customers with international plans and frequent customer service calls.
- Customers without voicemail plans churn more frequently.
- High international charge is a potential churn driver.

---

## 🤖 Modeling

Models built and evaluated:
- Logistic Regression with SMOTE  
- Decision Tree with SMOTE  

Performance was evaluated using:
- Accuracy, Precision, Recall, F1-score  
- ROC-AUC Curve  
- Confusion Matrix  

---

## ✅ Model Evaluation

| Model                 | AUC Score | F1 Score | Recall (Churn) |
|----------------------|-----------|----------|----------------|
| Decision Tree + SMOTE | 0.86      | 0.76     | 0.78           |
| Logistic Reg + SMOTE | 0.79      | 0.71     | 0.74           |

The Decision Tree model showed better performance overall and was selected for final deployment consideration.

---

## 👥 Customer Profiling

At-risk customers tend to:
- Have international plans
- Make more customer service calls
- Lack voicemail services
- Incur high international call charges

---

## 💼 Business Insights & Recommendations

1. **Proactively engage high-risk customers** with retention offers based on model predictions.
2. **Improve customer service** for users with frequent complaints.
3. **Introduce affordable international calling packages.**
4. **Encourage voicemail plan adoption** through bundling or promotions.

---

## 📌 Conclusion

This project successfully developed a churn prediction model with strong performance and provided business-relevant insights. SyriaTel can now better allocate resources to retain customers who are most likely to leave.

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   https://github.com/anngachuhi/SyrialTel_Customer_Churn-_Analysis
   
