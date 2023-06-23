# Random Forest Project

In this project, we will explore publicly available data from LendingClub.com and create a model to predict whether a borrower will pay back their loan in full. We will use lending data from 2007-2010 and employ a Random Forest classification model for prediction.

## Project Description

[LendingClub.com](www.lendingclub.com) is a platform that connects borrowers with investors. As an investor, it is essential to identify borrowers who have a high probability of repaying the loan. The goal of this project is to create a model that can predict whether a borrower will pay back the loan in full.

We will use historical lending data from 2007-2010, which is available for download on the LendingClub website. The dataset includes various features such as credit policy, loan purpose, interest rate, borrower's income, credit score, and more.

## Project Steps

1. Import necessary libraries for data analysis and visualization.
2. Read the loan_data.csv file into a pandas dataframe.
3. Perform exploratory data analysis (EDA) to gain insights into the data and visualize key relationships.
   - Create histograms to compare FICO distributions based on credit policy and loan repayment status.
   - Generate a countplot to show the distribution of loans by purpose, colored by loan repayment status.
   - Plot a jointplot to observe the relationship between FICO score and interest rate.
   - Use lmplot to analyze the relationship between FICO score, interest rate, loan repayment status, and credit policy.
4. Prepare the data for modeling.
   - Transform categorical features using dummy variables.
   - Split the data into training and testing sets.
5. Train a Decision Tree classifier on the training data.
6. Evaluate the Decision Tree model by making predictions on the test data and calculating classification metrics (classification report and confusion matrix).
7. Train a Random Forest classifier on the training data.
8. Evaluate the Random Forest model by making predictions on the test data and calculating classification metrics (classification report and confusion matrix).
9. Compare the performance of the Decision Tree and Random Forest models.
10. Draw conclusions and discuss the results.

## Usage

1. Download the `loan_data.csv` file from [here](https://www.lendingclub.com/info/download-data.action) or use the provided cleaned version.
2. Place the `loan_data.csv` file in the same directory as the Python code file.
3. Run the Python code.
4. The code will generate various plots and display the classification reports and confusion matrices for the Decision Tree and Random Forest models.

## Results

Based on the evaluation metrics, the Random Forest model outperformed the Decision Tree model in predicting loan repayment status. The Random Forest model's classification report and confusion matrix provide insights into the model's performance.

## Resources

- [LendingClub.com](www.lendingclub.com)
- [Loan Data Download](https://www.lendingclub.com/info/download-data.action)

