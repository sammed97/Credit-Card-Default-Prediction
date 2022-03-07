# Credit_Card_Default_Prediction
## Problem Statement

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

## Project Overview
### 1. Understanding Data-
After loading the dataset, explored the data, features, head, tail, data types, info of dataset, descriptive statistics. Then we checked for null values and duplicated values.

### 2. Data Cleaning-
In our dataset there are zero null values as well as zero duplicated values, so we have nothing to worry because it won’t affect our dataset.We have to deal with some columns to merge some values into them for sake of simplicity.

### 3. Data Visualization-
Plotted different features against target variable as well as credit limit for getting some insights from it.

### 4. Feature Engineering-
After data visualization, we did some data pre-processing using encoding some of the important categorical variables like education, gender, marital status, age group and converting them into numerical binary format.

### 5. Model Training-
For modelling we tried different classification algorithms like:
a.	Logistic Regression
b.	Random Forest Classifier
c.	XGBoost classifier


### 6. Hyperparameter Tuning-
Hyperparameters are sets of information that are used to control the way of learning an algorithm. Their definitions impact parameters of the models, seen as a way of learning, change from the new hyperparameters. This set of values affects performance, stability and interpretation of a model. Each algorithm requires a specific hyperparameters grid that can be adjusted according to the business problem. Hyperparameters alter the way a model learns to trigger this training algorithm after parameters to generate outputs.

### 7. Conclusion-
a. We are heading towards end of the project. In this experiment we firstly explored the data tried to get insights from that data which is EDA, then we visualized the data by using various tools after that we did Feature Engineering part and then we splits our data for model building and after that we fitted 3 models on our final dataframe name Logistic Regression, Random Forest Classifier, XGBoost Classifier respectively.
After that we also performed hyperparameter tuning, and used respective hyperparameters for getting best possible results.


b. Logistic Regression Model has highest precision but lowest recall, if our business cares more for precision then this model would be the winner.

c. XGBoost classifier has the highest recall but lowest precision.

d. Random Forest has a good precision and recall score that means it has a good balance of precision and recall which is higher F1, hence we will recommend the Random Forest Classifier Model.

e. From feature imporance we get that last 2 months repayment status will helpful in deciding whether the customer will default or not.

f. Marital status and Gender are also fairly important features.

## Future Scope
1.Other models can run effectively

2.We can use more labelled data

3.We can get more computatonal resources to tune XGBoost parameters.

# Thank You

