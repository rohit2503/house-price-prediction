# House Price Prediction Assignment

* A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

    The company wants to know:
    - variables are significant in predicting the price of a house, and
    - How well it can describe the price of House.
    - Also, determine the optimal value of lambda for ridge and lasso regression.
 

* Business Goal:
  You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the     prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will   be a good way for management to understand the pricing dynamics of a new market


Data Analysis:

SalePrice vs OverallQual

![download](https://user-images.githubusercontent.com/5464884/192383028-98eee219-ca65-4f7b-b2d6-ac6bb33616ec.png)

Housestyle:

![download](https://user-images.githubusercontent.com/5464884/192383254-e0d1dbf5-472a-462c-9f39-769bb624d286.png)

HeatMap:

![download](https://user-images.githubusercontent.com/5464884/192383162-e57213d8-e0d7-4799-bb12-e341b96ac9b5.png)


### Observation and Conclusion for the predicting the price of houses¶
* Lasso performs better than Ridge
* Number of parameters are way too less than in lasso as compared to ridge

The Best estimator for Lasso and Ridge are as follws
* Lasso - 0.001
* Ridge - 10.0

The Mean Squared Error in case of Lasso and Ridge are 
* Lasso - 0.15534978053646922
* Ridge - 0.21135697057387653

### Based on Lasso the following features will impact the prices of house
- MSSubClass
- LotArea
- OverallQual
- OverallCond
- YearBuilt
- YearRemodAdd
- BsmtFinSF1
- TotalBsmtSF
- 1stFlrSF
- 2ndFlrSF
- BsmtFullBath
- FullBath
- HalfBath
- KitchenAbvGr
- TotRmsAbvGrd
- Fireplaces
- GarageArea
- WoodDeckSF
- ScreenPorch
- PoolArea
- YrSold
- MSZoning_RL
- MSZoning_RM
