# Bike_Sharing_LM_Model
This is Bike Sharing Linear Regression Model prepared to Bike Sharing company help to understand the factors impacting the demand.
This would help Bike Sharing company to understand the factors	that impacts the demand for shared bikes.
This will help company to make decisions to meet the demands and increase customer satisfaction which will inturn increase the business.


## Table of Contents
* [General Information]
* [Conclusions]
* [Technologies Used]
* [Acknowledgements]
* [Contact]


## General Information
- This is Linear Regression Model for Bike Sharing System.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
  The company is finding it very difficult to sustain in the current market scenario. 
  So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- We are builing a liner regression model to understand the demand for shared bikes with the available independent variables. 
  It will be used by the management to understand how exactly the demands vary with different features. 
  They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
  Further, the model will be a good way for management to understand the demand dynamics of a new market. 
- day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Following 11 variables are the key variables to impact the demand:
  windspeed, year, season spring,Weather2(Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist) and weather3(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds),
  months (march,may,jun,august,september) and holiday
- Adjusted R2 of Train data is 0.77 and test is 0.74 which are close
- VIF factor for all the variables are less than 5.
- P value for all the variables are less than 0.05.



## Technologies Used
- Python 3.10.9
- matplotlib 3.7.0
- seaborn 0.12.2
- sklearn 1.2.1
- statsmodels 0.13.5


## Acknowledgements
- This project was inspired UPGRAD learning platform
- References : https://learn.upgrad.com/course/4616/segment/27463/221700/677826/3429800
- This project was based on https://learn.upgrad.com/course/4616/segment/27463/219402/670547/3392518


## Contact
Created by https://github.com/KavitaGupta2023 


