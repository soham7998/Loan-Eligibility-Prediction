# Loan-Eligibility-Prediction

Data Loading and Exploration: Imported necessary libraries and loaded the dataset from a CSV file. Explored the dataset with head(), info(), shape, and describe() methods to understand its structure and summary statistics.

Identified missing values using isnull().sum(). Filled missing values in categorical columns (e.g., Gender, Married) with the mode, and in numerical columns (e.g., LoanAmount, Loan_Amount_Term) with mean or mode as appropriate. Feature Engineering:

Created new features such as TotalIncome by summing ApplicantIncome and CoapplicantIncome. Transformed skewed data using logarithmic scaling (LoanAmount_log and TotalIncome_log).

Data Visualization: Used histograms and boxplots to visualize the distribution of ApplicantIncome, CoapplicantIncome, LoanAmount, and their logarithmic transformations. Examined the relationship between Credit_History and Loan_Status using cross-tabulation.

Data Preparation: Selected relevant features for model training and separated the target variable (Loan_Status). Split the data into training and testing sets using train_test_split. Encoded categorical variables into numerical values using LabelEncoder.

Model Training and Evaluation: Applied the Naive Bayes Classifier to train the model on the training set. Evaluated the model's performance on the test set, likely calculating metrics such as accuracy, precision, recall, and F1-score (though the evaluation part isn't explicitly mentioned in the provided code).
