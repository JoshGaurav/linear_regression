# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


In such an attempt, ****BoomBikes**** aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


- Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Train R^2 :0.840
  Train Adjusted R^2 :0.836
  Test R^2 :0.798
  Test Adjusted R^2 :0.789
This seems to be a really good model that can very well 'Generalize' various datasets.
- Demand of the bike depend on -
yr, holiday, workingday, temp, windspeed, season2, season 4, mnth8, mnth9, weekday6, weathersit2 and weathersit3
out of these windspeed, holiday, weathersit2 and weathersit3 negatively impact the demand of the bike
- cnt = 0.090297 + (yr × 0.232711) - (holiday × 0.056011)+ (workingday × 0.046317) + (temp × 0.518828) − (windspeed × 0.150835) + (season2 × 0.100362) + (season4 ×0.138202) + (mnth8 × 0.050952) + (mnth9 × 0.113626) + (weekday6 ×0.056927) - (weathersit_2 × 0.083049) − (weathersit3 × 0.287225)
- The Residuals are normally distributed. Hence our assumption for Linear Regression is valid.
- Homoscedasticity - No visible pattern observed from the plots for residuals and Independence of residuals Durbin-Watson value of final model lr_4 is 2.074, which signifies there is no autocorrelation.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.9.2
- sns - version 0.13.2
- pandas - version 3.10.2
- numpy
- sklearn
- statsmodels


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@JoshGaurav] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->