# Yulu---Hypothesis-Testing
## Problem Statement:
Yulu, India’s leading micro-mobility service provider, has experienced a noticeable decline in revenue and seeks to understand the key factors influencing the demand for its shared electric cycles. The objective is to identify the most significant variables—such as season, weather, weekdays and holidays that affects the user demand. This analysis aims to build a predictive model to estimate demand patterns and guide data-driven business strategies for growth.

## Insights:
#### **EDA based insights -**
* Total 10,886 rows were present in the data set.
* Dataset didn't have any missing values or duplicate values.
* temp and atemp columns are highly correleated hence we dropped one column 'atemp'
* 'casual' and 'register' columns total is equal to 'count' column hence they are highly correleated. Hence we dropped 'casual' and 'registered' columns.
* Outliers were found in the count column but we didn't remove it since we want to keep the originality of the dataset. 

### **Insights from Hypothesis Testing**
* The demand for bikes on weekdays are higher than demand on weekends.
* The demand for bikes on regular days was higher than demand on holidays.
* The demand for bike rides for different seasons are not the same.
* Demand is higher on the Sunny days followed by Cloudy days and low on Rainy days.
* The demand for bike rides for different weather are not the same.
* There is a significant interaction between the seasons and the weather on the avg bike rides
* We have also proved that Weather conditions and seasons are dependent.

### **Recommendations for Yulu**
* Ensure high availability on weekdays, especially on office hours
* Optimize bike redistribution at high traffic locations such as metro, bus stand, offices etc
* Launch weekends and holidays packages to boost weekends and holidays sales
* bike rides are less on rainy seasons hence we can launch discount prices on the rainy seasons and offer accessories(rain coats, mobile cover) for riders
* partner with cafe, parks and event venues for launching ride and rewards program and promotions
* Introduce loyalty programms for daily users
* reward frequent users with cashbacks 
* lauch referal program to increase the logins/new customers
* we can build model to show real time demand/ weather based suggestions in the App

