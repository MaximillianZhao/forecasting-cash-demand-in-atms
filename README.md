# Forecasting-cash-demand-in-ATMs
Using K-Nearest Neighbors (KNN) regression to analyse withdrawal behaviour and manage cash quantities in ATMs

Efficient cash management is important for every bank, involving strategic decisions regarding ATM network reloads. 
Insufficient cash supply to ATMs increases the risk of customer dissatisfaction, tarnished reputation, and revenue loss. 
Conversely, over-supplying ATMs incurs opportunity costs tied to capital and potential interest income.

Dataset

| Variable | Description                                                             |
|----------|-------------------------------------------------------------------------|
| Withdraw | The total cash withdrawn a day (in 1000 local currency)                 |
| Shops    | Number of shops/restaurants within a walkable distance (in 100)         |
| ATMs     | Number of other ATMs within a walkable distance (in 10)                 |   
| Downtown | =1 if the ATM is in downtown, 0 if not                                  |
| Weekday  | =1 if the day is weekday, 0 if not                                      |
| Center   | =1 if the ATM is located in a center (shopping, airport, etc), 0 if not |
| High     | =1 if the ATM has a high cash demand in the last month, 0 if not        |


The objective of the model is to precisely forecast the response variable 'Withdrawal' based on relevant covariate variables. 
By predicting the amount withdrawn from each ATM, banks can effectively determine the optimal level of cash to supply the ATM with.

1. Exploratory Data Analysis:

   Examining patterns within the data which justify the use of KNN regression.
   
3. KNN Regression:

   Implementing KNN regression and evaluating results.
