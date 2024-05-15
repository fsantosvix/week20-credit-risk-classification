### Module 20 - credit-risk-classification

## Data Analysis Report: Assessing Creditworthiness of Borrowers

### Overview of the Analysis

The objective of this analysis was to evaluate the creditworthiness of borrowers during the loan application process. The analysis utilised a variety of borrower-related metrics, including loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks on credit, and total debt.

The primary aim was to predict the 'loan status,' categorized as either 'healthy' or 'high risk of defaulting.'

### Methodology

The analysis proceeded through several stages of the machine-learning process:

1. **Target and Features Selection:** Identified relevant features and the target variable, loan status.
2. **Data Splitting:** Utilized the train_test_split function from the scikit-learn library to divide the dataset into training and testing subsets.
3. **Model Development:** Employed Logistic Regression to build a predictive model based on the selected features.

### Results

The Logistic Regression model yielded the following performance metrics:

**Precision:**

- 100% precision for predicting healthy loan applications.
- 85% precision for identifying high-risk loans.

**Recall:**

- 99% recall rate for healthy loans.
- 91% recall rate for high-risk loans.

**Accuracy:**

- Overall accuracy of the model stands at an impressive 99%.

### Summary

The Logistic Regression model demonstrated robust performance, showcasing high precision, recall, and accuracy metrics. Notably, the model exhibited exceptional capability in accurately identifying healthy loans while also effectively flagging a significant portion of high-risk cases.

**Recommendation:**
Based on the exemplary accuracy rates achieved by the Logistic Regression model, it is recommended for adoption in practical applications in the company. Its ability to accurately assess borrower creditworthiness makes it a valuable tool for loan evaluation processes.
