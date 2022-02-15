# Customer-Loan-Campaign-Targetting
Predicting whether a targeted customer for campaign would buy a loan

## Problem Description
A bank is in the US that has a growing customer base. The majority of these customers are liability customers (depositors) with varying sizes of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, we have to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors).
A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio.
Building a model that will help the marketing department to identify the potential customers who have a higher probability of purchasing the loan

## Objective
* To predict whether a liability customer will buy personal loans.
* Which variables are most significant.
* Which segment of customers should be targeted more


## Results
### Trained Logistic Regression model with varying thresholds and feature selection
 
`On the Training Set`
- The best balance between Recall and Precision of 0.77 and 0.71, respectively, has been given by Logistic Regression with threshold of 0.27 
- The best accuracy score of 0.95 has been given by Logistic Regression with threshold of 0.27


`On the Test Set`
- The best balance between Recall and Precision of 0.81 and 0.72, respectively, has been given by Logistic Regression with threshold of 0.27 
- The best accuracy score of 0.95 has been given by Logistic Regression with default threshold of 0.5
