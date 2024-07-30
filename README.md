# Project Name -Demand for shared bikes - Case Study  By Saravanakumar PERUMAL
> Description : 
    This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.  
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. 
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
- The company wants to know: Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors 
- You are required to model the demand for shared bikes with the available independent variables.
- It will be used by the management to understand how exactly the demands vary with different features.
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- Further, the model will be a good way for management to understand the demand dynamics of a new maparation:
- "day.csv" dataset is used in this project.

## Conclusions
- Conclusion 1 : Extensive EDA performed on the data set. There are no missing values. Univariate, bivariate and multi-variate analysis are performed on the data set. It reveals many insigtts about variables. This can be observed using scatter plots.  A linear pattern suggests linearity. By observing the scatter plots, it is concluded that the numerical vairbales (temp, hum and windspeed) are showing linear pattern.
- Conclusion 2 :  Error terms are normally distributed.If we observe the below histogram of error terms they are normally distributed and shows bell shape curve. This confirms the good validity of the predicted model.
 - Conclusion 3 : Error terms are independent of each other : If we compute the errors of the model, they are well distributed along the mean and there are no observed pattern in this plot so this model is well suited for linear regression.
 - Conclusion 4 : Error terms have constant variance (homoscedasticity):The variance should not increase (or decrease) as the error values change. Also, the variance should not follow any pattern as the error terms change. Univariate, Bi-Variate and Multi Variate analysis is done on the data set.
 - Conclusion 5 :  RFE (Recurrsive Feature Elemination) Method by both P-Value and VIF shows very well R-Squared Value, VIFs are < 5 and P values are < 0.05
 - Conclusion 6 :Linear Equation of the Model
   cnt = 0.129072 + 0.128877 * season + 0.236715 *  yr +  	-0.072362 * holiday + 	0.048906 * weekday + 	0.019720	* workingday -0.191626	* weathersit + 0.464158 * temp -0.148376 * windspeed 
 - Conclusion 7 :  Multiple Linear Regression Results 
        R Squared Value during Training : 0.802
        R Squared Value during Test: 0.778
## Technologies Used
- python 3 - Jupyter Note Book
- numpy library - version 1.26.4
- pandas library - version 2.2.1
- matplotlib library - version 3.8.3
- seaborn library - version 0.13.2
- plotly library - version 5.22.0

## Acknowledgements

- This project and the data was provided by [IIITB](https://www.iiitb.ac.in/) & [upGrad](https://www.upgrad.com/) learning platform for Linear Regression case study.


## Contact
- Created by [Saravanakumar PERUMAL](https://github.com/Saravana2u/)- feel free to contact me!
- This project work repository is here : [Demand For Shared Bikes](https://github.com/Saravana2u/DemandForSharedBikes).
