# House-Price-Prediction-Assignment
# Project name
House Price Prediction using Advance Regression

## Table of Contents
Introduction
Technology used
Conclusion

## Indroduction:
In this case study, Surprise Housing, a US-based housing company that employs data analytics to buy homes for less than they are worth and then sell them for more, has recognised us.

### Problem Statement: Part - 1

Assignment Part - I

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

### Problem Statement: Part - 2

Assignment Part- II

Please limit your answers to less than 500 words per question.
 

Question 1

What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?


Question 2

You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?


Question 3

After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?


Question 4

How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?

Business Goal 

- Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Determine the optimal value of lambda for ridge and lasso regression.
- This model will then be used by the management to understand how exactly the prices vary with the variables.
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
- The model will be a good way for the management to understand the pricing dynamics of a new market.
- 
   
## Technology used:

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- scikit-learn
- warnings

## Conclusion

In the case of Ridge and Lasso, the ideal lambda value is as follows:

- Ridge -  7
- Lasso -  0.0004 

Ridge and Lasso's Mean Squared Error is as follows:

- Ridge -  0.013827
- Lasso -  0.013637

- Ridge's Mean Squared Error is somewhat higher than Lasso's.
- Additionally, Lasso has an advantage over Ridge because it aids in feature reduction (as one of the feature's coefficient values became 0).
- Consequently, according to Lasso, the zoning classification, living area square feet, overall quality and condition of the house, and location are the elements that generally determine the price. the house's type of foundation, Number of vehicles that can fit in the garage, total square footage of the basement, and finished basement square footage Lasso's factors are thus significant variables for predicting the price of a house in the preceding bar chart.
