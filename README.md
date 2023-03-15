# Linear Regression Model - Bike Sharing Case Study
Requirement is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)




## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- understand the factors on which the demand for these shared bikes depends. Specifically, tunderstand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
        Which variables are significant in predicting the demand for shared bikes.
        How well those variables describe the bike demands

- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. It contain 2 Year data for bike sharing demand, along with weather data, date etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The 80% Demand of Bike Shares can be primiarily described by a linear model consisting of 8 variables: 
['const', 'temp', 'hum', 'windspeed', 'yr', 'holiday', 'season_summer', 'season_winter', 'mnth_sep']

The linear Equation looks like: 
𝑐𝑛𝑡(demand) = 
0.3114 
+0.5977 × 𝑡𝑒𝑚𝑝 
−0.3425 × ℎ𝑢𝑚 
−0.2361 × 𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑 
+0.2291 × 𝑦𝑟
−0.0853 × ℎ𝑜𝑙𝑖𝑑𝑎𝑦
+0.0908 × 𝑠𝑒𝑎𝑠𝑜𝑛𝑠𝑢𝑚𝑚𝑒𝑟
+0.1398 × 𝑠𝑒𝑎𝑠𝑜𝑛𝑤𝑖𝑛𝑡𝑒𝑟
+0.1031 × 𝑚𝑛𝑡ℎ𝑠𝑒𝑝


## Technologies Used
python 3.10 
Python Libraries: 
numpy
pandas
matplotlib
seaborn
sklearn
statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was part of assignment for upGrad MS in AI-ML. 

## Contact
Created by [@sghoshca] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->