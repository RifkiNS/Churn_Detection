# Customer Churn Prediction using Machine Learning

## Project Overview
Customer churn is one of the biggest challenges for subscription-based and service-oriented businesses. Losing customers not only reduces revenue but also increases acquisition costs.

This project aims to build a **machine learning model to predict customer churn**, allowing businesses to identify at-risk customers early and take preventive retention actions.

By leveraging customer demographic and behavioral data, this model helps uncover the main factors contributing to churn and supports **data-driven customer retention strategies**.

---

## Business Problem
Customer retention is often more cost-effective than acquiring new customers. However, businesses frequently struggle to identify which customers are likely to leave.

The objective of this project is to:

- Predict whether a customer is likely to churn
- Identify key factors driving customer churn
- Provide actionable insights to improve retention efforts

---

## Project Workflow

### 1. Data Collection
The dataset consists of multiple customer-related tables combined into one analytical dataset:
- Customer demographic data
- Service subscription information
- Customer account details
- Churn labels

### 2. Exploratory Data Analysis (EDA)
Performed exploratory analysis to:
- Understand customer distribution
- Detect patterns related to churn
- Explore relationships between features
- Identify important numerical and categorical variables

### 3. Data Preprocessing
Applied preprocessing steps including:
- Merging multiple sheets into one dataset
- Handling categorical variables with encoding
- Train-test splitting
- Feature preparation for model training

### 4. Model Building
Built a **Customer Churn Prediction Model** using:

- **XGBoost Classifier**

Chosen because XGBoost performs well on structured/tabular data and handles feature interactions effectively.

### 5. Model Evaluation
Evaluated model performance using:
- Classification Report
- Confusion Matrix
- ROC AUC Score
- Feature Importance Analysis

---

## Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **XGBoost**
- **Matplotlib**
- **Seaborn**

---

## Key Insights
The model identified several major indicators of customer churn, including:

- Low customer engagement
- High service-related interactions
- Reduced activity patterns

These insights can help businesses proactively target customers with retention campaigns before churn occurs.

---

## Business Impact
This project demonstrates how predictive analytics can improve customer retention by:

- Identifying customers at risk of leaving
- Supporting targeted intervention strategies
- Reducing revenue loss from churn
- Improving customer lifetime value

---

## Future Improvements
Potential enhancements for this project:

- Hyperparameter tuning for improved performance
- Deployment with **Streamlit** for real-time churn prediction
- Integration with business dashboards
- Automated retraining pipeline

---

## Repository Structure
```bash
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks
├── models/             # Saved model files
├── README.md           # Project documentation
