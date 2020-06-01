# Project: Communicate Data Findings Using Python
## by Song R.

## Date Created:
> 11 May 2020

## Dataset

> The dataset is about individual rides history in the greater San Francisco Bay recorded in a bike-sharing system named 'Lyft'. (renamed from Ford GoBike System Data). Only March 2020 database is used in this analysis. The dataset can be found in the following url: https://s3.amazonaws.com/baywheels-data/index.html


## Summary of Findings

> There are 3 main questions that I focused on this dataset:
- Whether Lyft subscriber or normal customer make longer ride duration in minutes ('user_type', 'duration_min')
- Which rental access methods are used the most ('rental_access_method')
- Which time period of the day that bikes are rented the most ('period_day' or 'start_hour')

> In the exploration part there are additional questions that can be found along the main questions as well. I found that most are Lyft subscribers and most access bike sharing system via application more frequent. Highest bike duration in minutes (470.83 minutes) is made from normal customers. The most visited start and end station name is the same which is San Francisco Caltrain (Townsend St at 4th St), near SF Oakland Bay Bridge. Afternoon is the highest time period that bike users rented a bike (highest start hour: 5 p.m.) while most bike rent durations is less than 1 hour. One of the main variable of interests --  'duration_min' has weak correlation with other numeric variables. Geolocation numbers like latitudes and longitudes are negatively correlated as the number signs of these two variables are opposite to each other.

## Key Insights for Presentation

> Note that I do not make any major changes in my graph design except adding graph title as I want to go for simple designs just like in exploration part. So in my presentation I focus on the 3 main question and pick only some visualizations from the first part.

> Following are main insights in my presentation:
- Customer who rent the bike longest (470.83 minutes) is also the one that access Lyft bike rent service via application.
- Subscribers access bike service via application. Another type of rental access method, Clipper is not as popular as Lyft application.
- Bike users usually rented the bike in rush hour period: in the late afternoon (4-5 p.m.), morning (8-9 a.m.) and evening (6 p.m.) respectively.
- Afternoon is the period that has the longest duration per ride (in minutes) and period with highest number of bike rents. 