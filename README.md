# Project Name
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.  

The company wants to know:  
* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

This assigment builds a Ridge and Lasso regression model that helps predict the sales price of a house based the independent variables that influence it . It can be used to understand how exactly the how the different features influence the Sales Price.  

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The primary Objective of the case study is to understand how the factors (variables)in the provided data set influences the Sales Price of the houses in the Australian market. 

The study should enable the company to -
   - to understand how exactly the prices vary with the variables.
   - They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
   - Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The following steps are followed -
1. Data Understanding the Exploration
   * Data Visualization using - histograms, pairplots, regplots, countplots
   * Co-relation checks
2. Data Cleaning
   *  Missing Value Treatment
   *  Outlier Treatment
4. Data Preparing for modelling
   *  Dividing data into X & Y sets for model building
   *  Dummy variables creation
   *  Scaling of numerical independent and response variables
   *  Splitting data into Training and Test Sets
5. Model Building and Evaluation using Lasso and Ridge regression model
   *  Building Linear Regression reference model
   *  Building Ridge Regression model
   *  Building Lasso Regression model
   *  Prediction and evaluation on the test set
   *  Comparing the performance metrics across all the three models
   *  Observing the key coefficients after regularization
   *  Conclusion
6. Subjective Questions resolution


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

* The top 10 positively impacting attributes on SalePrice are -
      MSZoning_FV    :    0.32026
      MSZoning_RM    :    0.27907
      MSZoning_RL    :    0.277144
      MSZoning_RH    :    0.268782
      BsmtFullBath_2    :    0.201671
      Condition2_PosA    :    0.167606
      OverallQual_9    :    0.142449
      Neighborhood_Crawfor    :    0.134168
      Neighborhood_StoneBr    :    0.128639
      OverallQual_8    :    0.104344

* The top 10 negatively impacting attributes on SalePrice are -
      Foundation_Wood    :    -0.087882
      MSSubClass_160    :    -0.092979
      SaleCondition_Alloca    :    -0.099889
      OverallCond_4    :    -0.108293
      Neighborhood_MeadowV    :    -0.147343
      Functional_Maj2    :    -0.150363
      OverallQual_2    :    -0.158484
      OverallCond_3    :    -0.206903
      LandSlope_Sev    :    -0.255343
      Exterior1st_BrkComm    :    -0.256029

* Lasso Regression model has about 91 variables less as compared to Ridge model making it a simpler and preferred model to interpret in comparision to Ridge.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Panda
- Numpy
- seaborn
- matplotlib
- Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Kaggle
- This project was based on courses taken from upgrad.


## Contact
Created by [@abe-twistedtech] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->