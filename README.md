# citibike analysis June 2023
# Exploratory Data Analysis - June 2023 Bike Ride Data

![Cover Image](https://www.nyc.gov/assets/home/images/press_release/2018/November/pr576-18.jpg)

## Introduction

This repository contains the results of exploratory data analysis performed on the June 2023 bike ride data. The analysis aims to answer various questions about the bike ride patterns, user behavior, and overall trends.

## Analysis Overview

In this analysis, we focused on answering the following questions:

1. **Distribution of Ride Durations**: A notable concentration of ride durations is observed within the 1-minute range. This pattern suggests the possibility that users might be quickly returning the bike to the same station. It could indicate a behavior where users are testing multiple bikes available at the station before selecting one for their ride.

2. **Mean Ride Duration**: The mean usage is approximately 15 minutes, from the analysis it can be infered that the average ride duration is approximately 15 minutes, it can be attributed to the peak summer season in June which is why users usage of the bike is less. To support this statement we need to check the mean usage during other months 

3. **Most Used Start and End Stations**: The most used station is [W 21 St & 6 Ave](https://www.google.com/maps/place/6th+Ave+%26+W+21st+St,+New+York,+NY+10011/@40.7414137,-73.9974347,17.06z/data=!4m6!3m5!1s0x89c259a359223d75:0xad366760d8a26086!8m2!3d40.7416224!4d-73.99375!16s%2Fg%2F11gf4d5fx3?entry=ttu) since this station is surrounded by 3 metro stations and in the financial district, we can assume that most users have used citibike to commute to work during the summers, this can be corroborated by visualizing the usage by hour  

4. **Most Used Route**: the most used route are near the [Rockefeller Park](https://www.google.com/maps?sca_esv=560358764&rlz=1C1VDKB_enUS1046US1046&output=search&q=rockefeller+park+nyc&source=lnms&entry=mc&sa=X&ved=2ahUKEwjo_rqk9fqAAxWskYkEHXzuDSQQ0pQJegQIDRAB) region, it provides a secnic view by the river and seems to be a good spot to hang out during the summers, PS I have never been to new york but looking at the place through google maps street view seemed like one I would love to visit 😄

5. **Rides per Day**: Analyzed the count of rides for each day to spot usage trends.

6. **Weekdays vs. Weekends**: Explored the differences in user activity between weekdays and weekends, but there isn't any co relation or spike in usage, during the weekends when compared to weekdays, the weather on weekends could also be a affecting factor and since we have only 4 weekends we need to analyze the data over previous months to find inference. This corroborates our statement that citibikes are used for commute for work

7. **Membership Distribution**: The fact that 80% of the users are Citibike members suggests a strong level of customer loyalty and engagement with the Citibike service.
   
8. **Bike Type Distribution**: Explored the distribution of different types of bikes used by riders, we observe that 80% of users ride classic bikes, this needs to be co releated with the number of classic bikes available vs electric bikes 

## Future scope
1. Co relate the usage with weather to understand whether usage is more on weekends when compared with weekdays
2. Co relate results with usage by hour to find if users prefer citibike for commute to work
3. Exclude rides with duration less than 1 minute to perform analysis as they could be CAN data 

## Conclusion

The exploratory data analysis of the June 2023 bike ride data provided valuable insights into user behavior, popular routes, and usage patterns. This analysis can be used to make informed decisions for improving bike ride services and user experience.

For detailed code and findings, please refer to the [Jupyter Notebook](https://github.com/mihirajgaonkar/citibikeanalysis/blob/main/Citibike%20June%20data%20first%20draft%20.ipynb) in this repository.

