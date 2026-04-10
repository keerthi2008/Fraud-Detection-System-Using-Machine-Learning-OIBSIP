# Fraud-Detection-System-Using-Machine-Learning-OIBSIP
🔹 Description

This project focuses on detecting fraudulent transactions using machine learning techniques. It analyzes transaction data, performs data preprocessing, feature engineering, and builds predictive models to classify transactions as fraudulent or legitimate.

The system uses:

Logistic Regression

Decision Tree Classifier

to identify fraud patterns effectively.

🔹 Dataset

The dataset contains transaction-related features such as:

Transaction amount

Transaction type

International transaction flag

Fraud flag (target variable)

🔹 Project Workflow

1. Data Loading

Load dataset using Pandas

2. Data Understanding
View dataset structure (head, info, describe)
Check fraud distribution

3. Data Cleaning
Handle missing values
Remove duplicates

4. Feature Engineering
Created high_amount feature
Created risk category based on amount + international transactions

5. Data Preprocessing
   
6. Convert categorical variables using one-hot encoding
   
7. Model Building
   
Logistic Regression

Decision Tree Classifier

8. Model Evaluation
   
Accuracy Score

Confusion Matrix

9. Visualization
    
Fraud vs Normal transactions

Fraud by transaction type

🔹 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn


🔹 Usage

python src/main.py

🔹 Results

Successfully classified fraudulent transactions

Logistic Regression and Decision Tree models compared

Visual insights generated for better understanding
