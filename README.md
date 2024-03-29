# credit-risk-classification

## Module 20 Challenge:

### Requirements

#### Split the Data into Training and Testing Sets (30 points)

To receive all points, you must:

- Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame. (5 points)
- Create the labels set (`y`) from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns. (10 points)
- Split the data into training and testing datasets by using `train_test_split`. (15 points)

#### Create a Logistic Regression Model (30 points)

To receive all points, you must:

- Fit a logistic regression model by using the training data (`X_train` and `y_train`). (10 points)
- Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model. (5 points)
- Evaluate the model’s performance by doing the following:
  - Generate a confusion matrix. (5 points)
  - Generate a classification report. (5 points)
  - Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)

#### Write a Credit Risk Analysis Report (20 points)

To receive all points, you must:

- Provide an overview that explains the purpose of this analysis. (5 points)
- Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)
- Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points)

#### Coding Conventions and Formatting (10 points)

To receive all points, you must:

- Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
- Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
- Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
- Use concise logic and creative engineering where possible. (2 points)

#### Code Comments (10 points)

To receive all points, your code must:

- Be well commented with concise, relevant notes that other developers can understand. (10 points)

### Steps Completed:

- First, I imported essential modules like NumPy, Pandas, and scikit-learn's `confusion_matrix` and `classification_report`.
- Next, I loaded the `lending_data.csv` file into a Pandas DataFrame to start working with the data.
- Then, I separated the dataset into labels (`y`) from the "loan_status" column and features (`X`) from the remaining columns.
- After that, I split the data into training and testing sets using the `train_test_split` function from scikit-learn.
- I then created a logistic regression model using scikit-learn's `LogisticRegression` class.
- I trained the logistic regression model on the training data using the `fit` method.
- Following that, I used the trained model to make predictions on the testing data using the `predict` method.
- To evaluate the model's performance, I generated a confusion matrix and a classification report.
- Finally, I analyzed the confusion matrix and classification report to assess how effectively the logistic regression model predicted both healthy and high-risk loans.
- In my analysis, I provided a written response summarizing my observations on the model's predictions for healthy and high-risk loans.

### Documentations Used:

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [NumPy Documentation](https://numpy.org/doc/)

### Stackoverflow Article Referenced (this article made the whole assignment click for me):

- [What is the difference between linear regression and logistic regression?](https://stackoverflow.com/questions/12146914/what-is-the-difference-between-linear-regression-and-logistic-regression)
