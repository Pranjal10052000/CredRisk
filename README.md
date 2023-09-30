# CredRisk
CredRisk: A Credit Risk Predictor Model Using Machine Learning
LendingClub is a peer-to-peer lending service provider that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub makes historical data available to the public via an API. Financial datasets containing information on credit history, income, employment status, and other relevant data from a sample of individuals or organizations.
Furthermore, by utilizing the most effective machine learning techniques such as regressions, Random Forest, or Neural Networks, we can create models to predict potential borrowers' credit risk. This model can be used to identify patterns and trends that will help financial institutions evaluate the creditworthiness of potential borrowers.
# Problem Definition:
The intention of this project was to identify the best classification model and predictors for correctly predicting borrowers’ credit risk. The intention is to seek how attributes impact classification and how hyper-parameter tunning impacts classification of borrowers.
# Data Cleaning and Data Exploration:
We used the following steps to identify and correct or remove errors, inconsistencies, and inaccuracies in a dataset in-order to improve its quality and usefulness:
The data sets for year 2020-2021 are sourced from the following API’s:

• https://resources.lendingclub.com/LoanStats_2021Q1.csv.zip 
• https://resources.lendingclub.com/LoanStats_2021Q2.csv.zip 
• https://resources.lendingclub.com/LoanStats_2021Q3.csv.zip 
• https://resources.lendingclub.com/LoanStats_2021Q4.csv.zip 
• https://resources.lendingclub.com/LoanStats_2020Q4.csv.zip
This data set contains 110048 instances. There are 143 attributes in total, with 1 target attribute, 'loan status'. There are 107 numerical attributes and 37 categorical attributes. For analysis, the data must be cleaned.
For data cleaning:
• All the rows and columns which had all its values null were removed
• Columns with more than 75 % of missing values are also removed from the dataset.
• For the columns consisting less than 75% missing data, we implemented different
techniques depending the amount of the missing data, and the type of the data (Numerical/Categorical)
