# Bike Sharing Assigment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
## **Problem Statement**
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.<br>


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. <br>


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.<br>


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

 * Which variables are significant in predicting the demand for shared bikes.
 * How well those variables describe the bike demands <br>


Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


**Business Goal:**<br>
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The equation of the best fit line is:

**cnt** = 4491.30 + 993.88 x **yr** + 1235.10 x **temp** - 438.12 x **hum** - 352.05 x **windspeed** + 309.70 x **Summer** + 506.20 x **Winter** - 120.52 x **July** + 205.06 x **September** - 100.90 x **Monday**

The R² and adjusted R² values for the training and test sets are very close (R²: 0.810 vs. 0.801 and adjusted R²: 0.810 vs. 0.793) and 
the RMSE values of 844.87 in the training set and 844.201. This means our model is doing a good job of predicting new data, not just memorizing the training data. So, we can expect it to work well on new, unseen data too.

Bike demand is influenced by features such as yr, temp, hum, windspeed, Summer, Winter, July, September, and Monday.

Most significant key feature variables yr, temp, and Winter since it exhibit the highest coefficient values.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - 3.11.5
- pandas -  2.1.4
- numpy - 1.26.3
- matplotlib - 3.8.2
- scikit-learn - 1.3.2
- statsmodels - 0.14.1
- seaborn - 0.13.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- upGrad tutorials on Linear Regression on the upGrad learning platform.


## Contact
Created by [@yesgvinayak](https://github.com/yesgvinayak)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
