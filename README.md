# Credit-Card-Fraud-Detection
This project demonstrates the process of credit card fraud detection using a logistic regression model.  The purpose of this project is to develop a predictive model that can identify fraudulent transactions and distinguish them from legitimate ones.


# Dataset
The dataset used in this project contains information about various credit card transactions. It includes features such as transaction amount, time, and other anonymized variables. The dataset is loaded into a pandas dataframe and thoroughly explored to understand its structure and characteristics.

# Balancing the Dataset
To ensure the model receives sufficient exposure to both legitimate and fraudulent transactions during training, the dataset is balanced. This is achieved by randomly sampling an equal number of legitimate transactions and combining them with fraudulent transactions. The balanced dataset is then used for model training.

# Logistic Regression Model
A logistic regression model is employed for the credit card fraud detection task. Logistic regression is a popular machine learning algorithm for binary classification problems. It learns from the features of past transactions to predict whether a new transaction is legitimate or fraudulent. The model is trained using the balanced dataset, and its performance is evaluated using accuracy metrics.

# Model Evaluation
The accuracy of the trained model is assessed on both the training and test datasets. Accuracy represents the proportion of correctly classified transactions. By evaluating the model's accuracy, we can gauge its effectiveness in identifying fraudulent transactions based on the learned features. This evaluation helps financial institutions take appropriate measures to prevent financial losses and protect their customers.

# Usage
To use this project, follow these steps:

1. Install the required dependencies, including numpy, pandas, and scikit-learn.
2. Download the credit card dataset and place it in the appropriate directory.
3. Run the provided code to load the dataset, balance it, and train the logistic regression model.
4. Evaluate the model's accuracy on both the training and test datasets.
Analyze the results and make necessary adjustments to improve the model's performance.
5. By leveraging this credit card fraud detection project, financial institutions can enhance their ability to identify and prevent fraudulent transactions, thereby protecting their customers and minimizing financial losses.
