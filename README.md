# Project Name

> Boom Bikes Linear Regression Assignment

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- **Background of the Project**: Boom Bikes, a US-based bike-sharing company, has experienced a significant decline in revenues due to the ongoing pandemic. With the easing of lockdowns, the company aims to better understand post-pandemic demand for shared bikes, to develop strategies that will support business recovery and growth.
- **Business Problem**: Boom Bikes needs to predict the demand for shared bikes in order to optimize their service offerings, pricing, and operations based on variables such as weather, season, and day type (working day vs holiday).
- **Dataset**: The dataset used contains daily bike rental data including both casual and registered users. The variables include features like temperature, humidity, wind speed, season, weather conditions, and more. The target variable for the model is the total number of rentals (`cnt`), which includes both casual and registered users.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- **Conclusion 1**: The model shows that **demand increases over time**. The positive coefficient for the year variable (0.24) suggests that, as the years progress, bike rental demand increases. This could be due to rising popularity or other external factors contributing to higher demand.

- **Conclusion 2**: **Demand is higher on working days**. The positive coefficient for working days (0.086) indicates that people are more likely to rent bikes on weekdays, likely driven by the need for transportation or commuting.

- **Conclusion 3**: **Temperature has the strongest influence on demand**. With the highest positive coefficient (0.647), temperature plays a significant role in increasing demand. Warmer weather encourages outdoor activities, which translates to higher bike rental demand.

- **Conclusion 4**: **Weather conditions significantly impact demand**. Light rain or snow, indicated by the large negative coefficient (-0.289), substantially decreases demand, while misty and cloudy weather also slightly reduces demand (-0.069). This highlights that bad weather, particularly precipitation, deters people from engaging in outdoor activities like bike rentals.

- **Conclusion 5**: **Seasonal patterns and months affect demand**. While Spring tends to have slightly lower demand due to cooler temperatures (-0.031), Winter and September see an uptick in demand (0.107 and 0.052, respectively). Saturdays also experience a positive demand spike (0.097), suggesting that weekends attract more bike rentals, likely due to leisure activities.

- **Conclusion 6**: **Certain months like July** see a drop in demand, possibly due to holidays or vacations, as indicated by the negative coefficient for July (-0.089).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- **pandas** - version 2.2.2
- **numpy** - version 1.26.4
- **matplotlib** - version 3.9.2
- **seaborn** - version 0.13.2
- **sklearn** - version 1.5.1
- **statsmodels** - version 0.14.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@vaishalimakwana] - feel free to contact me!

<!-- This project is open source . -->
