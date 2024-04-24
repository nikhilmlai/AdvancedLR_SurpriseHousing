**Problem Statement**
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. This project builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know the following things about the prospective properties:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

**Business Goal**
> Business Requirement is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project explores the given dataset to idenify driving factors for price of a in Australia
- This project also describes top 10 variable effecting price of a house
- This project helps the firm to manipulate the strategy accordingly
- This project also help company to identify areas that will yeild high returns

## Conclusions
- Out of 50 features in the final model, top 10 features which the form should focus on are:
  1 : 1stFlrSF - First Floor square feet
  2 : 2ndFlrSF - Second floor square feet
  3 : OverallQual - Rates the overall material and finish of the house
  4 : OverallCond - Rates the overall condition of the house
  5 : SaleCondition_Partial - Condition of sale is Partial
  6 : LotArea - Lot size in square feet
  7 : SaleCondition_Normal - Condition of sale is Normal
  8 : BsmtFinSF1 - Type 1 finished square feet
  9 : MSZoning_RL - Residential Zone with Low Density
  10: Condition1_Norm - Normal Proximity to various conditions

## Technologies Used
- Pandas - For Data Manipulation
- seaborn - For Data Visualization
- matplotlib - For Data Visualization
- sklearn - For Model Building & Selection

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@nikhilmlai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
