# Customer Churn Prediction | Machine Learning

A Machine Learning classification project that predicts customer churn in the telecommunications industry using customer demographics, service subscriptions, contract details, and billing information.

The goal is to identify customers who are likely to leave a telecom service, helping businesses make data-driven decisions and develop targeted customer retention strategies.

## 📌 Project Overview

Customer churn is a significant challenge for telecom companies, as retaining existing customers is often more cost-effective than acquiring new ones.

This project analyzes customer data, identifies patterns associated with churn, and builds a Logistic Regression model to predict whether a customer is likely to leave the service.

**Key Objectives**
- Predict customer churn using supervised Machine Learning.
- Identify factors associated with customer attrition.
- Analyze customer behavior through Exploratory Data Analysis (EDA).
- Support data-driven customer retention strategies.

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

- **Records:** 7,000+ customer records
- **Target variable:** `Churn` (Yes/No)
- **Problem type:** Binary Classification

### Features Used

| Category | Example Features |
|---|---|
| Customer Demographics | Gender, Senior Citizen, Partner, Dependents |
| Service Information | Internet Service, Streaming TV, Tech Support |
| Account Information | Tenure, Contract, Payment Method |
| Billing Information | Monthly Charges, Total Charges |

## 🛠️ Tech Stack

- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Removed unnecessary columns, including `customerID`.
- Handled missing values using `SimpleImputer`.
- Converted the target variable into a binary format.
- Encoded categorical features using appropriate encoding techniques.
- Applied feature scaling using `StandardScaler`.
- Built preprocessing workflows using `ColumnTransformer` and `Pipeline`.

### 2. Exploratory Data Analysis (EDA)

Analyzed customer characteristics and their relationship with churn.

**Key Findings**
- Customers on month-to-month contracts showed higher churn.
- Customers without technical support were more likely to churn.
- Churn patterns varied with monthly charges and customer tenure.
- Long-term contracts were associated with lower churn.

### 3. Model Development

**Algorithm:** Logistic Regression

The dataset was split into training and testing sets using an 80:20 ratio. The model was trained on the training data and evaluated on the held-out test set.

### 4. Model Evaluation

The model was evaluated using accuracy, precision, recall, F1-score, a classification report, and a confusion matrix.

## 📊 Model Performance

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 79.4% |
| Precision (Churn) | 62% |
| Recall (Churn) | 56% |
| F1-Score (Churn) | 59% |

**Interpretation:** The model correctly classified 79.4% of test observations overall. Its 56% recall for the churn class indicates that it identified approximately 56% of actual churn cases, leaving room for improvement in detecting at-risk customers.

For a business focused on customer retention, improving churn recall while maintaining useful precision is an important next step.

## 💼 Business Applications

The predictions can help telecom businesses:

- Identify customers who may be at risk of leaving.
- Prioritize customers for retention campaigns.
- Develop targeted offers and service improvements.
- Understand factors associated with customer attrition.
- Support customer retention and revenue protection strategies.


## 🚀 Future Improvements

- Experiment with Random Forest, XGBoost, and other classification algorithms.
- Address class imbalance using class weights or resampling techniques.
- Perform hyperparameter tuning and cross-validation.
- Optimize the decision threshold based on retention costs and business objectives.
- Evaluate ROC-AUC, PR-AUC, and churn-class recall.
- Deploy the model using Streamlit or Flask.
- Build an interactive dashboard for churn analysis and risk prediction.

## ▶️ Getting Started

### Prerequisites

Install Python and the required libraries.

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Navigate to the project directory:

   ```bash
   cd <YOUR_PROJECT_FOLDER>
   ```

3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the project notebook and run the cells in sequence.


## 📁 Project Structure

```text
Customer-Churn-Prediction/
├── Telco-Customer-Churn.csv
├── Customer_churn.ipynb
├── README.md
└── requirements.txt
```


## 📚 Skills Demonstrated

Python · Data Cleaning · Exploratory Data Analysis · Feature Engineering · Categorical Encoding · Feature Scaling · Scikit-learn Pipelines · Logistic Regression · Classification Metrics · Data Visualization

## 👩‍💻 Author

**Parmpreet Kaur**

B.Tech Computer Science Engineering Student | AI/ML & Generative AI Enthusiast

