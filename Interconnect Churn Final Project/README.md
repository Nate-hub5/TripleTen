# Problem Description:
https://github.com/Nate-hub5/TripleTen/blob/main/Interconnect%20Churn%20Final%20Project/Interconnect%20Churn%20Project.ipynb 

Interconnect wants to forecast the churn of clients. If we find clients that plan on leaving, they will be offered promotional codes and other special plan options.

# Table of Contents
1. Download the data
2. Explore each data set to understand how to apply preprocessing
3. Perform preprocessing for the data
4. Perform Feature Engineering
5. Perform EDA to further understand our data
6. Model Preparation
7. Model Training and Evaluation
8. Insights and Conclusion



# Project Instructions:
1.Download the data

2.Explore each data set to understand how to apply preprocessing

3. Perform preprocessing for the data:
   
* Merge the data into one dataframe
* Convert datatypes
* Change column names / format.
  
4. Perform Feature Engineering
* contract types: Hot encode featues like type, payment method, and PapperlessBilling
* duration feature: Calculate the contract duration based on BeginDate and EndDate
* Check the seasonalilty for BeginDate(Month, Day of week, hour a day)
  
5. Perform EDA to further understand our data.
* Analyze the distribution of churn vs non-churn customers
* Investigate the relationship between finanical metrics, contract types, and churn
* Visualize correlations and potential predictors.
* Balance the Dataset
  
6. Model Preparation
* Train-Test spilt
* Apply scaling to numerical features if needed.
* Create a basic model for classification (Logistic Regression)
  
7. Model Training and Evaluation
* Train models: Logistic Regression, Random Forest, Gradient Boosting
* Optimize models using cross-validation
* Evaluate model using AUC-ROC and Accuracy
  
8. Insights and Conclusion
* Identify key drivers of churn
* Provide actionable business recommendations
