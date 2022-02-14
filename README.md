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
### 1. Logistic Regression
 - **With 0.5 Threshold** : Recall 0.67, Precision 0.88, Accuracy 0.96
 - **With 0.12 Threshold** : Recall 0.89, Precision 0.53, Accuracy 0.91
 - **With 0.27 Threshold** : Recall 0.81, Precision 0.72, Accuracy 0.95
 - **With Sequential Feature Selector** : Recall 0.59, Precision 0.89, Accuracy 0.95
