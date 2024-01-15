# Credit_Risk_Classification_Supervised

Instructions
The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
- Open the starter code notebook and use it to complete the following steps:
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
- Use your knowledge of logistic regression to complete the following steps:
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model’s performance by doing the following:
    - Generate a confusion matrix.
    - Print the classification report.
- Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
- Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

![image](https://github.com/flopezco12/Credit_Risk_Classification_Supervised/assets/141666916/c6df47e0-9a89-4ea8-9a03-8d1ce316710e)

Outcomes Summary:
An overview of the analysis: I will generate a supervised learning machine algorithm, with the help of linear regression, to asses the risk of lending money to various clients, and subsequently quantify the risk of those borrowing money.

The results: Based on the results, it appears that with the original data, the algorith was able to predict and classify the risk of loans with 95.20% accuracy. While, the addition of radom data to create an oversampeld data source, it lead to a higher accuracy of 99.36%. Therefore, this model is an accurate tool for businesses/companies to know what to expect in reagards to clients ability to repaym their loan.

