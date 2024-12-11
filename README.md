Loan Repayment Prediction

This repository contains a machine learning project aimed at predicting loan repayment behavior for a Non-Banking Financial Company (NBFC). The primary goal is to classify borrowers into potential defaulters and non-defaulters to enhance risk assessment and improve the loan approval process.

Project Overview

Key Objectives:

Analyze the loan dataset to identify patterns and key predictors of repayment behavior.

Perform data preprocessing to handle missing values, encode categorical features, and scale numerical data.

Train and evaluate multiple machine learning models.

Provide a robust and scalable solution to predict repayment behavior accurately.

Repository Structure:

train_data.xlsx: Training dataset containing loan information.

test_data.xlsx: Test dataset used for evaluating model performance.

eda.ipynb: Jupyter notebook for Exploratory Data Analysis (EDA), including visualizations and insights.

model_selection.ipynb: Jupyter notebook for model selection, training, evaluation, and comparison.

model_.py: Python script to generate, train, and evaluate machine learning models.

Tools and Technologies

Programming Language: Python

Libraries:

pandas for data manipulation

numpy for numerical operations

scikit-learn for machine learning models and evaluation

matplotlib and seaborn for data visualization

Key Features

1. Data Preprocessing:

Handling missing values and inconsistencies.

Encoding categorical variables using techniques like one-hot encoding.

Scaling numerical features for models sensitive to feature magnitude.

2. Exploratory Data Analysis (EDA):

Visualization of key loan features and repayment trends.

Statistical analysis of borrower demographics and loan attributes.

3. Modeling:

Implementation of multiple machine learning models, including:

Random Forest Classifier

Logistic Regression

Model evaluation using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

4. Model Generation:

The model_.py script automates the generation, training, and evaluation of models, ensuring reproducibility.

Results

Insights from EDA revealed key factors influencing repayment behavior.

The best-performing model was selected based on evaluation metrics, ensuring a balance of precision and recall.

Why This Model Was Chosen:

Logistic Regression:

Ideal for binary classification tasks like predicting defaulters vs. non-defaulters.

Provides interpretable coefficients for understanding feature impacts.

Delivered consistent performance with:

Accuracy: 76.44%

Precision: 78.49%

Recall: 93.84%

F1-Score: 85.48%

ROC-AUC: 73.52%

Random Forest:

Effective in handling non-linear relationships and reducing overfitting.

Offers feature importance metrics for insights into influential predictors.

Achieved robust metrics:

Accuracy: 75.84%

Precision: 78.62%

Recall: 92.43%

F1-Score: 84.97%

ROC-AUC: 72.64%

These models provide a balanced trade-off between interpretability and accuracy, with Logistic Regression excelling in recall and Random Forest offering robust generalization.
