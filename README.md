# Telecom-customer-churn-prediction
This project implements a machine learning model to predict customer churn in the telecom sector. The pipeline integrates data preprocessing, feature engineering, and model training to capture patterns in customer behavior. It handles both numerical and categorical inputs, computes derived metrics, and outputs churn predictions with probabilities.

Key Features:

1. Input Features: Customer demographics, service usage, billing details, contract type, support interactions, and engineered features such as complaint ratio, data-per-call, charge normalization, and call intensity.

2. Preprocessing:

- Standard scaling for numerical variables.

- One-hot encoding for categorical variables.

- Automatic handling of missing or invalid entries.

3. Modeling:

- Trains and selects the best-performing model using grid search and cross-validation.

- Supports probability-based predictions in addition to binary classification.

- Evaluation Metrics: Accuracy, precision, recall, F1-score, and ROC-AUC.

4. Prediction Modes:

- Interactive Mode: Accepts individual customer and dataset details through terminal input and predicts churn likelihood.

5. Applications:

- Customer retention analysis.

- Early churn detection for telecom operators.

- Interactive demo for churn prediction.
