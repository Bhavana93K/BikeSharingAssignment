# Project Name
Bike Count Prediction Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- > A US bike-sharing provider <b>BoomBikes</b> has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-The variables which are significant in predicting the demand for shared bikes are:

Demand will increase if below variable value increase

temp (Temperature has co-efficient of 0.5788 meaning demand in bike rental will increase by 0.5788 if there is an increase of 1 unit of temperature).
yr ( Year has co-efficient of 0.2277 meaning demand in bike rental increase by 0.2277 if there is a year change, This shows increase trend by year)
season (Demand in summer and winter will increase by 0.0887 and 0.1419 in those seasons).
mnth_9 (Demand will increase in month of September by 0.1038).
Demand will decrease if below variable value increase

weathersit_3 ( weathersit_3 has co-efficient of -0.2364 meaning bike rental demand will decrease by 0.2364 in weather condition of Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds).
hum ( hum has co-efficient of -0.1166 meaning bike rental demand will decrease by 0.1166 if there increase of 1 unit of humidity).
windspeed ( windspeed has co-efficient of -0.1197 meaning bike rental demand will decrease by 0.1197 if there increase of 1 unit of windspeed).


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-Python
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@bhavana93k] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
