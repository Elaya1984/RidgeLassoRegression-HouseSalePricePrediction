# Regularization -Housing price prediction using Ridge and Lasso Regression
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Regularization -Housing price prediction using Ridge and Lasso Regression
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal

Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?


## Technologies Used

- python - version 3.10.0
- pandas -version 2.0.2
- numpy -version 1.24.3
- seaborn -version 0.12.0
- matplotlib -version 3.4.0
- scikit-learn 1.3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions


RIDGE	LASSO
 	 

Ridge Regression Model:

 Train data:
R2 score: 0.8937809012072492 
RMSE score: 0.03958866748353199

 Test data:
R2 score: 0.8740921714800556 
RMSE score: 0.04417766528950032 

![image](https://github.com/Elaya1984/RidgeLassoRegression-HouseSalePricePrediction/assets/56072675/b6586b76-ee22-44a3-806e-92a2c7643a69)

Conclusion We have a good train score 85% and good test score as well 83%. That means what the model learnt in the train set it performed well in the test set.
	Lasso Regression Model 

   Train data:
R2 score: 0.8069457722085366 
RMSE score: 0.05337147880821713

 Test data :
R2 score: 0.800881671942512 
RMSE score: 0.05555613339120312 

![image](https://github.com/Elaya1984/RidgeLassoRegression-HouseSalePricePrediction/assets/56072675/c7bee118-6000-477f-a99a-204dcd5f356c)

•	The R2 test score on the Ridge Regression Model is better than Lasso Regression Model. 
•	RMSE on the Ridge Regression Model is better than Lasso Regression Model. 



## Acknowledgements

- This project was inspired by Upgrad

## Contact
Created by [https://github.com/Elaya1984/] - feel free to contact me!
