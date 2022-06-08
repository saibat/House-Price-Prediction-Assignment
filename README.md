# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. 

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression. 

### Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We see that both Lasso and Ridge regression have given us similar values of R2 for both train and test sets, but we can conclude that Lasso is better as it gives a zero value to all the insignificant features, making it more easy to choose predictive variables/features.

- From the above we can conclude that Surpirse Housing Co has to make sure they look into the predictors of the lasso regression that affect the price of the houses:
    1. Higher the value of positive coefficients, higher is the price if the house.
    2. Higher the value of negative coefficients, lower is the price of the house.

-To conclude, the following indicate higher sale value:
    1. GrLivArea(Above grade (ground) living area square feet)
    2. SaleCondition_Partial(Home was not completed when last assessed)
    3. Neighborhood_Crawfor(Neighborhood like Crawford)
    4. OverallQual(Overall quality is high)
    5. SaleCondition_Normal(Condition of sale is Normal)
    6. OverallCond(OverallCondition is high) and a few more.

- The following indicate lower sale value:

    1. PropAge(Property age is high)
    2. Neighborhood_IDOTRR(Neighborhood is Iowa DOT and Rail Road)
    3. GarageType_none(When no Garage)
    4. KitchenQual_TA(When Kitchen quality is Typical/Average)
    5. BldgType_Twnhs(Type of dwelling is Townhouse) and a few more.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - Python 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@saibat] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->