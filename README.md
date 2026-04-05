# loan-approval-ml-model
A supervised machine learning project to predict loan approval using classification models (logistic regression and random forest), including evaluation on unseen data.

## Loan Approval Prediction using Machine Learning

### Overview
The project demonstrates the full machine learning pipeline, including preprocessing, model training, evaluation, and interpretation.

### Dataset
The dataset contains approximately 45,000 observations with both numerical and categorical variables, including income, credit score, and loan characteristics. The dataset was sourced from Kaggle.com - https://www.kaggle.com/code/youssefelbadry10/loan-approval-classification-eda-ml

### Models Used
- Logistic Regression
- Random Forest

### Results
The Random Forest model achieved the best performance, with an accuracy of 0.93 and F1-score of 0.83 for the positive class.
Feature importance analysis shows that previous loan defaults and financial affordability are the most influential factors.

### How to Run
The notebook can be opened and executed in Google Colab. The dataset is loaded directly from this repository.
