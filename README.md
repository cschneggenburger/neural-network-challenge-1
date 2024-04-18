# neural-network-challenge-1
This repo will be used for the week 18 homework assignment on Neural Networks.

# Background
You work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. Your team has asked you to create a model to predict student loan repayment.

The business team has given you a CSV file that contains information about previous student loan recipients. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

# Files
One jupyter notebook "student_loans_with_deep_learning.ipynb" holds the entire application/modeling and analysis. This file shows the workings of a neural network to determine if a student will repay their loans. During the process of creating the model, the model was saved as "student_loans.keras" that is also in this repo.

# Functions/Dependencies
- import pandas as pd
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler
- from sklearn.metrics import classification_report
- from pathlib import Path

# Analysis
My model performed with an accuracy of 75.5% and a loss of .529. Further tuning or data gathering would be appropriate for this model to reduce the loss in training to provide a better model for predicting loan repayment. 
