# Employee Attrition Analysis

The cost of replacing an employee is quite large and we want to use data science to strategize around employee rentention. We picked an employee dataset that captures various factors of their working conditions. We have a column called `Attrition` that recorded whether an employee quit or not. Using this data, we want to identify the crucial factors that make an employee quit. 

For our INFO6105 final project, we came up with a common notion as our hypothesis. Using [IBM's Employee Attrition data](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset), we will be testing this hypothesis. 

<br/> Additionally, we want to identify key drivers of attrition. We want to analyse the relation of other parameters like number of years worked at this company, monthly pay, the employee's age to attrition.


### Hypothesis
People who are satisfied with their job are less likely to leave the company. 


#### Contents

1. Importing Libraries & Data Cleaning
2. Exploratory Data Analysis
    * Correlation Matrix
    * Data Encoding
3. Model Training & Testing
    * Predict whether a person will leave (Probability of leaving)
4. Compare various models and their accuracy
    * Logistic Regression
    * Random Forest
    * SVMs
    * Artifical Neural Networks
5. Feature selection — Correlation and P-value
    * Figuring out the most significant parameters that contribution to a person leaving
6. Hypothesis Testing 
7. Conclusion
