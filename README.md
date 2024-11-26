# Bike Sharing System
Problem Statement: A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due. It has decided to come up with a mindful business plan to be able to accelerate its revenue. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

- cnt is the target variable


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
Issues to Address:

 - Revenue Decline: BoomBikes faces substantial revenue declines due to the ongoing pandemic, necessitating a strategic solution.
 - Market Sustainability: The company struggles to sustain itself in the current market scenario, demanding a mindful business plan.
 - Post-Lockdown Strategy: BoomBikes aims to accelerate revenue post-lockdown, requiring an understanding of post-quarantine bike demand.
 
Objectives:

- The objectives include predicting significant variables influencing American market shared bike demand, determining the crucial predictors, developing a model to understand demand variations, facilitating adaptive business strategies, and exploring demand dynamics for effective decision-making.
- This case study aims to achieve this goal by building a multivariate linear regression model using the provided dataset.

## Conclusions
- There are more users using bike sharing when the weather is clear, or partly cloudy.
- Bike sharing usage increases when the wind speed is between 8 and 15.
- Bike sharing is more popular on working days (not holidays).
- Bike sharing usage is higher when the temperature is between 10°C and 30°C.
- There are more bike-sharing users when the humidity is between 50% and 80%.
- Users tend to use bike sharing more during the fall season, while the spring season sees the least usage.
- Most bookings occur between May and September.
- The year 2019 saw a higher number of bike usage compared to the previous year.
- The 'temp' and 'atemp' variables show the highest correlation with the target variable (cnt).
- The model created is
 > 0.131 + 0.234 * yr + 0.512 * temp - 0.154 * windspeed + 0.103 * summar + 0.125 * winter - 0.082 * misty - 0.284 * snow + 0.035 * Oct + 0.059 * Aug + 0.119 * Sep
 - The close alignment of R2 and adjusted R2 values between the training and test sets (R2: 0.810 vs. 0.800 and Adjusted R2: 0.83 vs. 0.81) in a linear regression model indicates effective generalization. This similarity suggests the model avoids overfitting to the training data and is likely to perform consistently on new, unseen data.

## Technologies Used
- [Python](https://www.python.org/) - version 3.13
- [Matplotlib](https://matplotlib.org/) - version 3.9.0
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
- [Statsmodels](https://www.statsmodels.org/stable/index.html) - version 0.14.4
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.5.2


## Acknowledgements



## Contact
Created by [@anandtv04](https://github.com/anandtv04) - feel free to contact me!
