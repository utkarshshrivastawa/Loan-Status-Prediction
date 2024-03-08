# Loan Status Prediction Using Support Vector Machine Model
## Dataset Overview
1. Source: The data for this project is sourced from a loan dataset, comprising 614 entries and 13 attributes.
2. Cleaning: The dataset contained missing values in several columns which were addressed by removing rows with any missing values, ensuring data integrity for model training.
## Data Preprocessing
1. Label Encoding: Categorical variables were converted to numerical format, facilitating their use in the SVM model. For example, 'Loan_Status' was encoded as 0 for 'No' and 1 for 'Yes'.
2. Feature Selection: All relevant features were retained for model training, excluding the 'Loan_ID' and 'Loan_Status' columns.
## Exploratory Data Analysis (EDA)
Visualization techniques were employed to explore the relationship between various factors and loan approval status. Insights from EDA include:
1. The impact of education level on loan approval.
2. The correlation between marital status and loan approval.
3. Gender differences in loan approval rates.

## Model Training and Evaluation
1. Algorithm Used: SVM with a linear kernel.
2. Training: The model was trained using a subset of the data, with the 'Loan_Status' column as the target variable.
3. Evaluation: The model's performance was evaluated on both training and testing datasets using accuracy as the metric. Results indicated a training accuracy of approximately 79.86% and a testing accuracy of 83.33%.

## Predictive System
A predictive system was set up to predict loan approval status based on input data. The system requires input in the form of the applicant's details (e.g., gender, marital status, income) and outputs the loan approval status (Approved or Not Approved).

## Conclusion
The SVM model demonstrated good predictive capability in determining loan approval status based on various applicant features. The model's accuracy suggests its potential utility in automating the loan approval process, thereby aiding financial institutions in making informed decisions.

## Contributions
Contributions to this project are welcome! Whether it's suggesting improvements, adding new features, or refining the predictive model, your input is valuable. Feel free to fork the repository, make changes, and submit a pull request with your enhancements.
