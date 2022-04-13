# Telecom Churn Prediction
 ## Business Case
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business
goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. 

- Objective:
	To build multiple models and evaluate them to select the best suited model for the prediction of churn customers

## Steps Followed
* Business Case
* Data cleaning (Missing values and outliers Treatment)
* Feature Engineering
* Scaling
* Building the Model using Logistics Regression and Random Forest with and without PCA
* Model Evaluation

## Model Interpretation
No of days since last recharge has more impact on the cutsomer churn rate. Focusing on this will help to retain the customers
As the recharge amount is decreased in order of 6,7,8, the likelihood of churning is high. Recharge offers can be provided to customers where there is decline in recharge amount is obsorved
3g volume drop also is an indication of customer to churn. 3G data plans can be improved
As the age of the customer increases(no of days the customer using the network), they are more likely to stay. So focusing more on new customers will help to reduce the churn rate
Model has sensitivity of 86% (would predict the 86% of customers who are likely to churn)
High important features are 'aon', 'no of days since last recharge', '3g data volume', 'avg revenue','avg recharge amt'

## Result

Comparing the logistics Regression model and Random Forest with & without PCA,
Accuracy is higher for Random Forest but the sensitivity score is more in Logistics regression

## Technologies Used
- pandas- version 1.0.1
- numpy- version 1.18.1
- seaborn- version 0.11.2
- skilearn
- stats models

## Contact
Created by [@sindhus123] - feel free to contact me!
