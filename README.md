# NYC CitibikeNYC Data Exploration

## Dataset

The data is about individual rides made in the bike-sharing system CitibikeNYC covering New York City, NY. It includes tripduration, starttime, usertype, birth year, gender and other fields that were not used in this analysis.
The data is providied in monthly batches. This analysis combines the data from all 12 months of 2018. The data and feature documentation can be found [here](https://ride.citibikenyc.com/system-data).

Data of population distribution by age from the new york department of health is used too. This data includes Age Group, All (all genders) population, Male population, and Female population. This data can be found [here](https://www.health.ny.gov/statistics/vital_statistics/2018/table01.htm).

## Summary of Findings

Exploratory analysis of the data found that usage rates were affected by both rider (gender, age, user type) and time factors (time of the day, day of the week. and month of the year). Rides distribution by age is left skewed as expected. It was surprising to find that males had three times more rides when adjusted by population than females. Customer user types recorded only 11% of the total rides. Bike usage fluctuated throughout the year suggesting temperature and weather sensitivity of riders as usage peaked during summer months to more than 2 times the winter low. The general usage rates throughout the day had a bimodal distribution consistent with commuting hours (9A.M and 5 P.M) that became a normal distribution during the weekend. Customer user types showed a normal distribution of rides by hour of the day all along the week as opposed to subscribers.
Trip duration analysis showed that the bikes were mainly used for short trips but usage over longer trips were still common. Customers had a more varied and evenly distributed trip duration between 10 and 30 minutes. Subscribers had a high concentration below 10 minutes. Trip duration varied by month with the warmer month having more long trips. It also varied by the time of day with most long rides being recorded between 9 A.M and 6 P.M.


## Key Insights for Presentation

The presentation will focus on the different usage patterns between subscribers and customers. I will look at the portion of rides by each user type. Next we will look at the different usage patterns by looking at trip duration distibutions and finally look at the distribution of rides over the week and weekends. This will allow us to get an idea of the likely components of each group and their likely use of the bikes.
