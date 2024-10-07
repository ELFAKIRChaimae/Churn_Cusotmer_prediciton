Churn Customer Prediction for E-commerce
This project aims to predict customer churn for an e-commerce platform using machine learning models. Customer churn refers to the scenario when customers stop purchasing from the platform. By identifying potential churners, the company can take proactive steps to retain customers and increase revenue.



Project Overview
This project uses various machine learning algorithms to predict whether a customer is likely to churn based on their behavior on the e-commerce platform. The main steps of the project include:

Data Collection
Data Preprocessing and Feature Engineering
Model Building and Training
Model Evaluation
Predicting Customer Churn
The goal is to provide the e-commerce business with actionable insights on how to reduce churn rates and improve customer retention.
Dataset
The dataset consists of customer interaction data, which includes:
  CustomerID                   
 1   Churn                       
 2   Tenure                      
 3   PreferredLoginDevice        
 4   CityTier                      
 5   WarehouseToHome              
 6   PreferredPaymentMode        
 7   Gender                     
 8   HourSpendOnApp               
 9   NumberOfDeviceRegistered      
 10  PreferedOrderCat             
 11  SatisfactionScore              
 12  MaritalStatus                
 13  NumberOfAddress              
 14  Complain                     
 15  OrderAmountHikeFromlastYear  
 16  CouponUsed                   
 17  OrderCount                   
 18  DaySinceLastOrder           
 19  CashbackAmount      


 Data Preprocessing
The preprocessing pipeline includes:

Handling missing values.
Feature scaling (normalization or standardization).
Encoding categorical variables (if any).
Creating additional features based on customer behavior (RFM scores, time-based features, etc.).
Splitting the dataset into training and testing sets.

Modeling
The following machine learning models are used for churn prediction:

Logistic Regression
Random Forest
Decision Tree
Adaboost

Evaluation
The models are evaluated based on the following metrics:

Precision
Recall
F1-Score
Confusion Matrix
