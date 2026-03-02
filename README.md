# Customer Churn Prediction

Predicting customer churn using Machine Learning to help telecom companies reduce customer loss and improve retention strategies.

# Project Overview

Customer churn is a major challenge in the telecom industry. Acquiring new customers is more expensive than retaining existing ones.

This project builds a Machine Learning classification model to predict whether a customer is likely to churn based on service usage, contract type, billing details, and demographic information.

The goal is to:

Identify high-risk customers

Improve retention strategies

Reduce revenue loss

📁 Dataset Information

Dataset: Telco Customer Churn Dataset

Records: 7,000+ customers

Target Variable: Churn (Yes / No)

Features Include:

Demographics (Gender, Senior Citizen, Partner, Dependents)

Services (Internet Service, Streaming TV, Tech Support)

Account Info (Tenure, Contract, Payment Method)

Charges (MonthlyCharges, TotalCharges)

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

Jupyter Notebook

⚙️ Project Workflow
1️⃣ Data Preprocessing

Removed unnecessary columns (e.g., customerID)

Converted Yes/No to 1/0

Handled missing values using SimpleImputer

Encoded categorical variables using:

OrdinalEncoder

LabelEncoder

Feature scaling using StandardScaler

Used ColumnTransformer + Pipeline

2️⃣ Exploratory Data Analysis (EDA)

Key insights:

Customers with month-to-month contracts have higher churn.

Higher monthly charges increase churn probability.

Customers without Tech Support churn more frequently.

Long-term contract customers churn less.

3️⃣ Model Building

Model Used:

Logistic Regression

Train-Test Split:

80% Training

20% Testing

📈 Model Performance

Metric                   	Value

Accuracy	                79.4%
Precision (Churn         	62%
Recall (Churn)	          56%
F1 Score (Churn)	        59%


Classification report and confusion matrix were used to evaluate model performance.

📊 Business Impact

This model helps telecom companies:

Identify customers likely to churn

Offer targeted retention offers

Improve customer lifetime value

Reduce revenue loss

Even a 5% reduction in churn can significantly increase profitability.

🔮 Future Improvements

Try advanced models (Random Forest, XGBoost)

Hyperparameter tuning

Handle class imbalance (SMOTE)

Deploy model using Flask / Streamlit

Build interactive dashboard
