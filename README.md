# Bank_Churn_ML
A machine learning project to predict customer churn in banking using classification models such as Logistic Regression, Random Forest, SVM, KNN, and XGBoost. The project includes end-to-end data preprocessing, exploratory data analysis, feature engineering, model comparison, and out-of-sample prediction.
This project focuses on predicting customer churn in the banking sector using machine learning techniques. The goal is to identify customers who are likely to leave (attrite) based on their demographic, financial, and behavioral data.
An end-to-end machine learning pipeline was developed, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and out-of-sample prediction.

# Objective
- Predict whether a customer will churn
- Identify key factors influencing customer attrition
- Compare multiple machine learning models
- Build a deployable prediction pipeline

# Model Used
- Logistic Regression (baseline model)
- Random Forest (tree-based model)
- XGBoost (boosting model)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

# Key Techniques
- Data preprocessing using ColumnTransformer
- One-hot encoding for categorical variables
- Feature scaling for numerical variables
- Feature engineering (e.g., average transaction value)
- Model comparison using Accuracy, Precision, Recall, and F1-score
- Confusion Matrix and ROC Curve analysis

# Key Results
- Transaction activity is a strong indicator of churn
- Inactive customers are more likely to leave
- Non-linear models outperform linear models

# Key Insight
- Transaction activity is a strong indicator of churn
- Inactive customers are more likely to leave
- Non-linear models outperform linear models

# Out-of-sample prediction
The final model was tested on new, unseen customer profiles to simulate real-world deployment. The results demonstrate the model's ability to generalize and support customer retention strategies.

# Tags
machine-learning
data-science
classification
churn-prediction
xgboost
scikit-learn
eda
