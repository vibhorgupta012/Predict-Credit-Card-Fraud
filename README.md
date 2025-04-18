# Predict-Credit-Card-Fraud
INTRODUCTION
The problem revolves around predicting whether a borrower will default on a loan based on various factors such as financial history, credit scores, etc. Loan default prediction is critical for financial institutions to minimize losses and make data-driven decisions.
In this task, we are using a dataset that includes various attributes of borrowers, including their financial history and other credit-related features. Our goal is to build a machine learning model to predict whether a borrower will default on a loan or not.
Key Concepts to Include:
•	Loan default and its impact on financial institutions
•	Importance of credit scoring models in predicting loan default
•	Machine learning models used in classification problems

 
METHODOLOGY
To solve this problem, we used a classification approach. Here's how we approached the problem:
•	Data Preprocessing:
o	Loaded the dataset from a CSV file.
o	Dropped the LoanID column as it was not useful for prediction.
o	One-hot encoded categorical features to make them suitable for machine learning models.
•	Feature Selection:
o	The features used for prediction are financial information and credit scores, while the target variable is Default (whether the borrower defaults on the loan or not).
•	Model Selection:
o	We selected a Random Forest Classifier, which is an ensemble learning method that works well for classification problems and is robust to overfitting.
•	Data Splitting and Scaling:
o	The data was split into training and test sets (70% for training, 30% for testing).
o	Feature scaling was applied using StandardScaler to ensure that the model was not biased toward any particular feature due to scale differences.
•	Training the Model:
o	We trained the Random Forest Classifier on the training data using the scaled features.
