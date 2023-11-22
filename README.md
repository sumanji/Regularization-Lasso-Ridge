# Project Name
> Housing Price case study :
    A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.



 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Recommendation](#Recommendation)
* [Acknowledgements](#acknowledgements)


## General Information
- With this case study we  are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. 
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
-  Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We can clearly see that in the Linear regression we see r2 score is very high in training set where as it is very low in the testing data set.
Hence it clearly indicates that there is overfitting in the model using Linear regression.Hence there is scope of regularization.
- On applying the Ridge and Lasso regularization we see that there is significant improvement in the r2 score of taring set and testing 
- Optimal value of alpha for Ridge Regularization is 5.05050505050505 and Optimal value of alpha for Lasso regularization  is 0.10101010101010101.




## Recommendation

- Figure out the overfitting problem using plain Linear Regression model
- HyperTune the parameter using the GridSearchcsv  with k folds and also select the optimal value of alpha based on the trade off between 
  variance and Bias.
- Measure the Model using different metrics available in scikit-learn library



## Technologies Used
- pandas - version 1.5.3
- numpy - version 1.23.5
- matplotlib - version 3.7.0
- seaborn - version 0.12.2
- scikit-learn - version 1.2.1




## Contact
Created by sumanji.aec@gmail.com  - feel free to contact me!
