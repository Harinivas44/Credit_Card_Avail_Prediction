
# Credit Card Availablility Prediction 📊💳

## Overview

This project is designed to predict whether a person is eligible for a credit card based on various attributes. The aim is to determine if an applicant is likely to be approved or denied a credit card, thereby assisting in the decision-making process.

The project uses machine learning techniques to analyze and predict credit card availability. It employs a dataset consisting of attributes such as checking balance, credit history, purpose, amount, savings balance, employment duration, and more to make predictions. The "default" attribute is used as the target variable, with values "Yes" indicating that the person is not eligible for a credit card and "No" indicating eligibility.

## Data Preprocessing 🧹

The dataset is preprocessed by converting categorical attributes into numerical values.
Encoding is applied to features like checking balance, credit history, savings balance, employment duration, phone, and default.
One-hot encoding is used for attributes like purpose, housing, other credit, and job.
Data is split into training and testing sets to evaluate model performance.

# Model Building 🤖

A Decision Tree Classifier is initially used for prediction.
The model is trained on the training data and evaluated on the testing data.
The Decision Tree model shows signs of overfitting, as it performs well on training data but less so on testing data.
Pruning techniques are applied to reduce overfitting, resulting in a more balanced model.
Additional ensemble techniques, including Bagging, AdaBoost, Gradient Boosting, Random Forest, and XGBoost, are explored to improve predictive accuracy.

# Results 📈

The models' performances are evaluated using accuracy scores and confusion matrices:

* Decision Tree (Overfit): Training Accuracy - 100%, Testing Accuracy - 69.33%
  
* Decision Tree (Pruned): Training Accuracy - 75.29%, Testing Accuracy - 74.33%

* Bagging Classifier: Testing Accuracy - 77.67%

* AdaBoost Classifier: Testing Accuracy - 74.00%

* Gradient Boosting Classifier: Testing Accuracy - 74.00%

* XGBoost Classifier: Testing Accuracy - 71.33%

* Random Forest Classifier: Testing Accuracy - 77.67%

# Conclusion 📊📉

This project demonstrates the use of various machine learning techniques to predict credit card availability. The Decision Tree model, when pruned, provides a balanced result, and ensemble methods like Bagging and Random Forest achieve the highest testing accuracies of 77.67%. These models can be further optimized and fine-tuned for better predictive performance.
## 🔗 Links
[![portfolio](https://img.shields.io/badge/view_my_notebook-000?style=for-the-badge&logo=github&logoColor=white)](https://nbviewer.org/github/Harinivas44/Credit_Card_Avail_Prediction/blob/main/Decision_Tree.ipynb)
