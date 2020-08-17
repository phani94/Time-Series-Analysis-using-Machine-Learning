Data Science Exercise

The objective of this exercise is to gain insights out of a new dataset, provide several statistics about the data and to train and test a regression model. This means following a typical data science process, from data cleaning and inspection to model building and evaluation.

Requirements
Python 3 environment with jupyter notebook / jupyter lab installed
Use common, open-source data science libraries such as numpy, pandas and scikit-learn (or tensorflow) to solve this exercise.
Provide the results and documentation in one executable jupyter notebook.
If lesser known libraries were used, provide a requirements.txt file to quickly install them.
Problem Definition
The data for this exercise mimics the data from a real-world manufacturing machine. The variables are continuously measured and include numerical and categorical features. One of the variables is a product property of the produced good, marked as the label in the dataset.

The objective is to analyze this variable and to train a model, which is able to predict the value of the label 5 minutes in the future.

This makes this task a supervised regression machine learning task.

Data
Features:

13 numerical
4 categorical
Label:

1 label
Additional columns:

1 timestamp (utc)
27504 rows

The numerical features are continuously measured machine parameters. The categorical features include two columns, which contain status information about machine components. These columns have an integer data type. The other two categorical columns have a string data type and contain information about the manufactured product. Together they fully describe which product is being manufactured. The label can be interpreted as a measure for the product quality, where a low value corresponds to high product quality.

Although the dataset is synthetic, it includes common artifacts such as missing values and anomalies.

Steps
Data cleaning and formatting
Exploratory data analysis
If outliers and anomalies exist, decide on how to treat them.
Compute descriptive statistics (mean, std, median, min, max) for each numerical features in respect to every manufactured product.
(bonus) What are the machine parameters, that lead to the best product quality for each product?
Tip: Keep in mind that there are weekdays without production when computing the statistics.

Base model

Choose a performance metric for the regression task and argue your choice. Then train a base model (e.g. linear regression or naive prediction).
Train and compare several machine learning models on the performance metric

Evaluate the best model on the testing set

Draw conclusions and document work

If you have questions feel free to ask.
