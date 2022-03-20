# PyBer_Analysis
UCSD Data Science bootcamp module 5

*Overview of the analysis* 

The purpose of this analysis is to demonstrate how the revenue of Pyber's ride-sharing service is impacted by different city conditions that can be summarize thanks to Matplotlib & dataframes. By providing a line graph & a dataframe of the different type of living areas over a period of time, the CEO can quickly see which areas generated the most amount of revenue for the business. 

*Results*

**Images**
![pyber_summary_df](https://user-images.githubusercontent.com/99565016/159142876-0a614b82-bf70-4c15-a79d-4e67c96c971f.PNG)

***figure 1: From the image above, Dataframe that shows the different criterias for different living conditions.***

We can see from figure 1 that the Urban conditions generated more revenue ($39,854.38)  as opposed to Rural conditions ($4,327.93), which can be expected as there more people in the area to use Pyber services. However, the average fare per ride & driver goes down as more people are present (Rural to Urban). This observation can be expected as there are far more drivers and customers in the Urban area than Rural area. 
On another note, we can see an upward trend from Rural to Urban: Total Rides, Total Drivers, & Total Fares. furthermore, a downward trend is noted from Rural to Urban: Average Fare per Ride & Average Fare per Driver.

![PyBer_fare_summary](https://user-images.githubusercontent.com/99565016/159142878-fe6ea7c4-9978-4d5b-be1c-b8bb259288a1.png)

***figure 2: From the image above, Line graph showing how the revenue is generated over time by different living conditions.***


From figure 2, all three living conditions have simliar trends over the course of time. An interesting observation is that there must've been an event that caused a spike in revenue from some point in time between February 15th and March 1st. However, the key take-away is that as more people live in a certain part of the city, the more revenue is generated. 


*Summary*

**Recommendations to the CEO**

First recommendation is to focus on Urban fares as they have almost 10x more revenue than the Rural counterpart. Perhaps minor focus on the Suburban as well as they generated almost 5x more than the Rural part too.
Second advice is to focus on total fare and disregard average fare per ride/driver alone but consider all criterias as a whole. For example, if one were to make $500/hr, an impressive hourly wage rate, but only works two hours a month, they're not generating a lot of annual income. 
Last recommendation is to reduce the number of drivers in the Urban setting since the number of rides (1625) is a lot less than the total drivers (2405). This is key in order to maximize Urban profit as riders can only have a single driver per ride. 






