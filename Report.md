# Performance Report

## Overview
The purpose of this analysis is to develop a deep learning model to predict the success of organizations if funded by Alphabet Soup. The classification model is used to identify applicants to make this prediction.

## Results
### Data Preprocessing
- The target variable for the model is “IS_SUCCESSFUL” column. This indicates the data for whether or not the money was used effectively.
- The featured variable for the model are "AFFILIATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", etc... columns. 
- The removed variables “EIN” and “NAME” are identification columns.

### Compiling, Training, and Evaluating the Model:
The neural network architecture is designed to capture and learn patterns effectively. The deep learning model has several layers that produces different activation functions.

To increase model performance to over 75% accuracy the testing data needs to be optimized. After my first optimization attempt I was unable to achieve the target.

## Summary
Neither model was able to achieve accuracy above 75% which makes it hard to summarize the data. The experiments with different neural networks helped to give ideas on how to improve the model's performance. There need to be further improvements to the machine and neurons to improve the accuracy.