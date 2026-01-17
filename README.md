# TASK--03-customer-purchase-prediction
Implemented a machine learning model using Python to analyze data and generate predictions as part of a data science task.
# Task-03: Decision Tree Classifier on Bank Marketing Dataset

## Overview
This project implements a Decision Tree classifier to predict whether a customer will subscribe to a product or service based on their demographic and behavioral attributes. The task is part of the Prodigy InfoTech Data Science Internship program.

## Dataset
- *Source:* UCI Machine Learning Repository (Bank Marketing Dataset)
- *File:* bank.csv
- *Target Variable:* y
  - 1 → Customer subscribed
  - 0 → Customer did not subscribe

The dataset contains customer demographics (age, job, education, marital status) and behavioral data related to marketing campaigns.

## Tools and Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
  
## Methodology
1. Loaded and explored the Bank Marketing dataset
2. Checked and handled missing values
3. Encoded categorical variables using Label Encoding
4. Split the data into training and testing sets (80:20)
5. Trained a Decision Tree Classifier
6. Evaluated the model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report

## Results
- *Accuracy:* ~87%
- The model performs strongly on the majority class (non-subscribers)
- Lower recall for the subscriber class reflects the natural class imbalance in the dataset

  ## Conclusion
This project demonstrates the end-to-end implementation of a Decision Tree classifier, from data preprocessing to model evaluation. The results highlight both the strengths and limitations of decision trees when applied to real-world, imbalanced marketing data
- Overall, the model demonstrates effective learning from demographic and behavioral patterns


