Dataset Description
This project uses a loan dataset that contains information about borrowers and their loan details. The dataset is commonly used for classification tasks, especially to predict whether a borrower will fully repay their loan or not.

Each row represents a loan issued to a borrower, and the columns include a mix of numerical and categorical features such as:

Credit policy status
Purpose of the loan (e.g., credit card, small business, etc.)
Interest rate
Installment amount
Annual income
Debt-to-income ratio
Credit history indicators (e.g., FICO score)
Number of credit lines
Revolving balance and utilization

The target variable in this dataset is:
not.fully.paid → Indicates whether the borrower failed to fully repay the loan (1 = not fully paid, 0 = fully paid)

 Objective
The main goal of this project is to build a machine learning model that can predict whether a loan will be fully paid or not based on the given features.

 Preprocessing Steps
Handling categorical variables using one-hot encoding
Splitting the dataset into training and testing sets
Feature selection and preparation for modeling
 Models Used
Decision Tree Classifier
(Optional) K-Nearest Neighbors (KNN)

 Evaluation
The model performance is evaluated using standard classification metrics such as accuracy, precision, recall, and confusion matrix.
