# Forecasting-cash-demand-in-ATMs
Using KNN regression to analyse withdrawal behaviour and manage cash quantities in ATMs

An important task for every bank is to optimise cash management, making smarter decisions abour reloading its ATM network. 
Supplying ATMs with insufficient cash runs the risk of customers being unable to withdraw funds, leading to customer dissatisfaction, reputational damage, and lost revenue.
Supplying ATMs with too much cash and the bank begins to incur the opportunity cost related to capital and potential interst income.
Thus, it is necessary maintain a good balance in ATM cash levels. 

Dataset

Variable
Withdraw : The total cash withdrawn a day (in 1000 local currency)
Shops    : Number of shops/restaurants within a walkable distance (in 100)
ATMs     : Number of other ATMs within a walkable distance (in 10)
Downtown : =1 if the ATM is in downtown, 0 if not 
Weekday  : =1 if the day is weekday, 0 if not
Center   : =1 if the ATM is located in a center (shopping, airport, etc), 0 if not
High     : =1 if the ATM has a high cash demand in the last month, 0 if not

The objective of the model is to precisely forecast the response variable 'Withdrawal' based on relevant covariate variables. 
By predicting the amount withdrawn from each ATM, banks can effectively determine the optimal level of cash to supply the ATM with.

1. Exploratory Data Analysis:

   Examining patterns and trends within the data which justify the use of KNN regression techniques

2. KNN Regression:

   Implementing KNN regression tuning parameters and testing on training data
