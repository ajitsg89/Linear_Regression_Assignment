# Linear Regression Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The company wants to know:
-Which variables are significant in predicting the demand for shared bikes.
-How well those variables describe the bike demands

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents

## [General Info](#general-information)
- Analyse bike sharing data and identify significant vaiables for predicting the demand for shared bikes.

## [Technologies Used](#technologies-used)
- Python
- Libraries:
- Numpy	
- Panads
- Matplotlib
- Seabor
- sklearn
- statsmodels

## Conclusions
- Univariate Analysis

1)Most of the days are clear to partly cloudy

2)There are more working days than Holiday/Weekends

3)All month,year,season and weekdays having same days as per calender

- Bivariate Analysis

1)Bike demand more in Fall season followed by summer season

2)In 2019 there are more rental bike users than in 2018

3)There are more rental bike users when wheather is clear to partly cloudy

4)There is not even single day on which heavy rain/snow has occured

5)Usage of bike on weekdays is slighlty highrer than holidays

6)Usage of bike is similiar irrespective of being working day or not

7)There is direct relation between bike demand and temp/atemp

8)There is inverse relation between bike demand and hum/windspeed

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Final Conclusions

1)There are 730 rows and 16 columns present in dataset

2)Most of the days are clear to partly cloudy

3)All month,year,season and weekdays having same days as per calender

4)Bike demand more is in Fall season followed by summer season

5)In 2019 there are more rental bike users than in 2018

6)There are more rental bike users when wheather is clear to partly cloudy

7)There is not even single day on which heavy rain/snow has occured

8)Usage of bike on weekdays is slighlty highrer than holidays

9)Usage of bike is similiar irrespective of being working day or not

10)There is direct relation between bike demand and temp/atemp

11)There is inverse relation between bike demand and hum/windspeed

12)Training Data set Stats - 
                    1)R-squared = 0.832

                    2)Adj. R-squared = 0.829

                    3)Error terms are normally distributed for training data set
13)Testing Data set Stats - 
                   1)R-squared = 0.816

                   2)Adj. R-squared = 0.808

                   3)Error terms are normally distributed for test data set
                   
14)R-squared and Adj. R-squared values for both training and test data is almost same

15)Linear Regression Model (Line of best fit) - Based on Training data set

cnt = 0.2259*yr - 0.0930*holiday + 0.6200*temp - 0.2868*hum - 0.2059*windspeed + 0.0800*season_Summer + 0.1390*season_Winter - 0.0482*mnth_July + 0.0944*mnth_Sept - 0.1914*weathersit_Light Rain or Snow + 0.2682 

## Libraries version
- Pandas: 2.2.2
- NumPy:1.26.4
- Seaborn:0.12.2
- Matplotlib:3.8.0
- Anaconda Navigator: 2.6.0
- sklearn : 1.3.0
- statsmodels : 0.14.0

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad Team
- References if any: None
- This project was based on EDA, Machine Learning modules


## Contact
Created by [ajitgaikwad89@gmail.com] - feel free to contact me!
