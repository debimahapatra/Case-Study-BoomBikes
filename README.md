# Project Name
> Boom Bikes Case Study


## Table of Contents
* [Problem Statement](#problem-statement)
* [Assumptions](#assumptions)
* [Technologies Used](#technologies-used)
* [Final Model](#final-model)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contacts](#contacts)


## Problem Statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Assumptions
- As the users are regular people, the weekends are supposed to on Saturdays and Sundays...The Data shows weekend as Mondays and Tuesdays
We have fixed the data as it was misleading


## Technologies Used
- Language - Python
- library - Numpy
- library - Pandas
- library - matplotlib
- library - seaborn
- library - math
- Library - statsmodel
- Library - sklearn

## Final Model
- Linear Regression Equation - y = 0.1129 + (0.2378	* yr) + (-0.0985	holiday) + (0.5511 * atemp) +(-0.1523 *	windspeed) + (0.1018 *	IsSummer) + (0.127 *	IsWinter) + (-0.0695 * IsWeatherOk) + (0.07	* IsAug) + (0.1105	* IsSep)

## Conclusions

-   r2score of 0.74 while evaluating the model indicate a good fitting model on test data as well
-   These are the key variables that boombike need to give more focus

Below is the equation that came up after executing the manual approach for model building

y = 0.1129 + (0.2378	* yr) + (-0.0985	holiday) + (0.5511 * atemp) +(-0.1523 *	windspeed) + (0.1018 *	IsSummer) + (0.127 *	IsWinter) + 
(-0.0695 * IsWeatherOk) + (0.07	* IsAug) + (0.1105	* IsSep)
    
    'yr' - as the company grows we can expect more usage and more revenue in future
    'holiday' - holidays on weekdays sees a decline.So, have discounts during such holidays falling on weekdays
    'atemp' - temperature has a direct and strong impact on count of boombike users.Target your marketing accordingly
    'windspeed' - windspeed impacts the weather.Higher the windspeed, bad is the weather, negative correlation with boombike user counts.As,it has a direct and strong impact on count of boombike users.Target your marketing accordingly
    'IsSummer' - Summer sees good count
    'IsWinter' - so, is winter
    'IsWeatherOk' - Good weather, higher the chances of usage, bad weather lesser the chances of bike usage
    'IsAug' - Aug shows decent count
    'IsSep' - Sep, too has decent count


## Acknowledgements
- This project is part of a case study from Upgrad for identification of key parameters affecting boom bike usage


## Contacts
- Created by [@debimahapatra]
