Project Description
This project focuses on predicting telecom customer churn using a Random Forest Classifier. It follows a full machine learning workflow including:

Data preprocessing:

Loading and cleaning the dataset

Handling missing values and data type conversions

Feature engineering:

One-hot encoding categorical features

Creating new features (e.g., customer tenure in years)

Model training and tuning:

Splitting data into training and test sets

Training a Random Forest model

Hyperparameter tuning using GridSearchCV

Model evaluation:

Assessing performance with Accuracy and ROC-AUC

Model interpretability:

Explaining predictions using SHAP (SHapley Additive exPlanations)

Analyzing feature importance for transparent decision-making

This approach helps stakeholders understand not just if a customer is likely to churn, but also why — enabling actionable business insights.


# Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/mubanda123/customer-churn-prediction.git
   cd customer-churn-prediction
2. pip install -r requirements.txt
3. jupyter notebook
   Then open churn_prediction.ipynb.
