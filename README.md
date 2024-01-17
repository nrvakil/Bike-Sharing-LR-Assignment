# Bike Sharing Linear Regression Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19 and to come up with a mindful business plan to be able to accelerate its revenue.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company wants to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

We are using a dataset with filename 'day.csv'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Equation
Count = 0.3814 * temp - 0.0896 * windspeed - 0.1079 * season_spring + 0.0755 * season_winter + 0.2383 * yr_2019 - 0.0663 * mnth_dec - 0.0568 * mnth_jan - 0.0640 * mnth_nov + 0.0567 * mnth_sep - 0.0717 * holiday_yes - 0.2469 * weathersit_rainy

NOTE: As seen, some coefficients are negative, they show an inverse relation with the target variable

#### Conclusions
1. Highest positively affecting variable is 'temp'.
2. Company should expand in Winter instead of Spring Season as the coefficient for Spring is negative.
3. Company should avoid Nov, Dec and Jan months for expansion.
4. Company should avoid Rainy weather and Holidays.
5. Company should increase expansion every year since year 2019 coefficient is very high.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
1. numpy
2. pandas
3. matplotlib
4. plotly
5. seaborn
6. statsmodels
7. sklearn