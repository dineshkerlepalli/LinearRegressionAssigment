# Project Name
> Bike Sharing demand prediction using Multiple Linear Regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Bike Demand(measured as cnt) is majorly influenced by the feature variables temp, Light Rain, yr, windspeed, winter
-  cnt exhibits positive correlation with temp, yr and winter and negative correlation with Light Rain, Windspeed 
- The computed Linear Regression Model is able to explain approximately 78% of variance in bike demand
- The error/residual terms(Yactual - Ypred) follow normal distribution which satisifies the assumption needed for Linear Regression Modelling
- The error terms follow homoscedasticity which satisfies another assumption needed for Linear Regression Modelling

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Language: Python
- Libraries: Scikit Learn, Pandas, Seaborn, Matplotlib
- Functions: MinMaxScaler, LinearRegression, RFE, OLS
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was assigned by Upgrad for learning purposes


## Contact
Created by @dineshkerlepalli - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->