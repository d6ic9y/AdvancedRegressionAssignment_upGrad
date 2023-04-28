# Advanced Regression Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein you have to build a advanced regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- What is the dataset that is being used? Please refer the data_definition.txt for the detail data definition

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Optimal value of lambda for Ridge Regression = 6
- Optimal value of lambda for Lasso = 0.001
- Going by the common predictors in the top 10 in both the model:
  - GrLivArea: an increase of 1 square foot of house area above ground, the price will increase by 20% to 46%.
  - TotalBsmtSF: an increase of 1 square foot of house total basement area, the price will increase by 12% to 14%.
  - OverallQual_8 & OverallQual_9: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 9% to 15%.
  - Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 9%
  - Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by nearly 8%.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.9.12
- Excel 2021
- Word 2021
- Windows 11

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by...
- Linear Regression assignment in Executive PG Programme in Machine Learning & AI - December 2022


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
