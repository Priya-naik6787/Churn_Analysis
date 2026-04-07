# Churn_Analysis📉 Customer Churn Analysis & Prediction (End-to-End Project)

📌 Project Overview

Customer churn is one of the biggest challenges in the telecom industry. This project focuses on analyzing customer behavior, identifying key churn drivers, and building a machine learning model to predict which customers are likely to leave.

The solution combines data analysis, feature engineering, and predictive modeling to deliver actionable business insights and improve customer retention strategies.

---

🎯 Objectives

- Analyze customer data to identify churn patterns
- Understand key factors influencing customer churn
- Build a predictive model to classify churn vs non-churn customers
- Provide actionable business recommendations to reduce churn

---

🗂️ Dataset Description

The dataset contains telecom customer information, including:

- Customer demographics (gender, tenure, etc.)
- Service details (internet service, contract type, etc.)
- Billing information (Monthly Charges, Long Distance Charges)
- Churn Category (reason for churn)

«⚠️ Note: Since the dataset did not include a direct churn flag, a binary target variable ("Churn") was created from the "Churn Category" column.»

---

🛠️ Tools & Technologies

- Python → Data analysis & modeling
- Pandas, NumPy → Data preprocessing
- Seaborn, Matplotlib → Data visualization
- Scikit-learn → Machine learning models
- Power BI → Interactive dashboard
- SQL → Data handling (optional step)

---

🔄 Project Workflow

1️⃣ Data Cleaning & Preprocessing

- Removed missing and inconsistent values
- Standardized column names
- Converted data types (e.g., TotalCharges → numeric)

2️⃣ Feature Engineering (Advanced)

- Created "Churn" (target variable) from "Churn Category"
- Built tenure groups to segment customer lifecycle
- Engineered "avg_spend" using monthly + long-distance charges
- Estimated total revenue per customer

«⚠️ Dropped "Churn Category" before modeling to avoid data leakage»

---

3️⃣ Exploratory Data Analysis (EDA)

- Churn distribution analysis
- Churn by tenure, contract type, and services
- Charges vs churn behavior
- Identification of key churn drivers

---

4️⃣ Handling Imbalanced Data

- Addressed class imbalance using:
  - SMOTE (Synthetic Minority Oversampling) (optional)
  - Class-weighted models (Random Forest)

---

5️⃣ Machine Learning Models

Built and evaluated multiple models:

- Logistic Regression
- Random Forest Classifier ✅ (final model)
- XGBoost Classifier (optional advanced)

---

6️⃣ Model Evaluation

- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Score

«🎯 Focus on Recall, as identifying churn customers is more critical than overall accuracy.»

---

7️⃣ Feature Importance

- Identified top features influencing churn
- Used Random Forest feature importance for interpretability

---

8️⃣ Power BI Dashboard

An interactive dashboard was created to visualize:

- Churn rate & customer KPIs
- Churn by tenure group
- Churn by contract type
- Charges vs churn
- Churn reasons (category)

---

🔍 Key Insights

- Customers with low tenure (0–12 months) are more likely to churn
- Month-to-month contracts show the highest churn rate
- High monthly and long-distance charges increase churn risk
- Specific service-related issues drive churn (from churn category)

---

💡 Business Recommendations

- Offer discounts or onboarding support for new customers
- Promote long-term contracts to improve retention
- Target high-value customers with personalized offers
- Address key churn reasons identified in the dataset

---

📊 Business Impact

This project helps businesses:

- Reduce customer churn
- Improve retention strategies
- Increase customer lifetime value
- Make data-driven decisions

---

📸 Dashboard Preview

---

🚀 Conclusion

This project demonstrates a complete end-to-end data analytics and machine learning pipeline, transforming raw telecom data into meaningful insights and predictive capabilities.

It highlights the importance of combining data analysis, domain understanding, and machine learning to solve real-world business problems.

---

📬 Contact

Feel free to connect for feedback, collaboration, or opportunities in Data Analytics & Machine Learning.
