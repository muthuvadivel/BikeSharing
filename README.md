# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

This assignment is a programming assignment to build a multiple linear regression model for the prediction of demand for shared bikes. Need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. The model will be a good way for management to understand the demand dynamics of a new market

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions

Bike Rent is impacted by below features:
1. Bike Rent/Sharing is heavily influenced by temperature
2. Bike rent varies based on the year on which it is done though it needs further analysis to see how a specific year impacts Bikes rent
3. Seasons like winter have more rents than summer or other Seasons
4. Also weather factors like lightsnow influence the bike rent, rentals get improved by clear weather
5. Rent seems to be high on week ends like Saturday compared to Working days thought not huge difference

Total Count of Bike Rentals given by below equation of these independent variables:
cnt = 0.232 * yr + 0.058 * workingday + 0.575 * temp + 0.082 * summer + 0.139 * winter + 0.079 * mist + 0.303 * lightsnow + 0.103 * Sep + 0.065 * Sat + 0.011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python==3.12.4
json==2.0.9
pandas==2.2.2
platform==1.0.8
numpy==1.26.4
seaborn==0.13.2
statsmodels.api==0.14.2
statsmodels==0.14.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
This project was inspired by Upgrad and completed by Muthuvadivel Balasubramanian (Email: muthuvadivel@gmail.com)
The Upgrade content on linear regression really helped in completing this assignment

## Contact
Created by [@Muthuvadivel Balasubramanian] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
