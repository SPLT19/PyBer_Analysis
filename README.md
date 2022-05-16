# PyBer_Analysis

## Overview of the analysis:

### Objective 
- The purpose of the following analysis was to understand the behaviour of data collected from Python based ride sharing app company PyBer. 
- We studied variables like type of city and number of drivers and riders percentage of total fares drivers and riders by type of city in order to try to improve access to ride sharing services and affordability under certain neighbourhoods.

### Methods
 We used Pandas to create a summary frame, analyse it and create a visual description with graphs and the help of matplotlib library as well as pandas as platform to have a clean visualisation of the story that the data is telling in order to support decision-makers at PyBer. 

## Results:

### General description and similarities
City types were urban, suburban and rural types. As shown in the first bubble graph, ride sharing data as reported in 2019, showed that the highest fares were mainly in the urban area, followed by suburban and lastly rural areas. 
![RideSharingData](analysis\Fig1.png)
Here one can also appreciate that most of the fare seem to come from Urban areas followed by suburban and lastly rural.
This was also evident both in the [Pie chart](analysis\Fig5.png) and line graph shown below. 
Regarding the behaviour along the timeframe between January 2019 to April 2019, the three city types seem to have a constant fare range each. The lowest fare range was seen in rural areas with a range around 1 to 500 USD; next range in the middle of the three was suburban areas with a range of around 700 USD to 1500 USD; and the highest range was seen in Urban areas with a fare range of 1800 to 2500 USD. 
![Total Fare by City Type](analysis\total_fares_by_city_type.png)
In general the behaviour seem to follow a constant linear plateau with a slight rise in fares between February and march that returned to a lower or similar fare range by the next month, however, neither of the three reach the other ranges that are clearly different between one another. Lines never seem to touch. 


### Differences in ride-sharing data among the different city types.
 Overall, the percentages between this tree types have disparities. Overall Urban areas seem to have the higher concentration, percentages, and rates in general of the three types. Following this suburban type overall showed to be second and lastly rural area rides, drivers and fares seem to be the lowest of the three. This seemed quite evident when analysing the percentages of total fares. ![Totalfarepercentage](analysis\Fig5.png).

 As described before in the [Line chart](analysis\total_fares_by_city_type.png) it seems that in general the highest fares where the last week of February as seen in the line graphs with what seems to be peeks in the three although rural areas showed the highest fares in April compared to the other two. In this month Urban fares started to rise again after a slow decrease seen in the previous month whereas suburban fares reach the lowest point and slowly recovers by the end of the month. 



### Ride-sharing data 

- Total rides: ![Total rides](analysis\Fig2.png) Regarding total rides per city type we could observe that there seem to be a difference in the amount of rides done in urban suburban and rural areas being the highest in the first one and the lowest in the last. 
![Total rides percentage by city Type](analysis\Fig6.png) The percentages as presented in the following pie chart shows 68.4% for urban rides, 26.3% for suburban and 5.3% for rural. In general urban areas have a high percentage of given rides. 


- Total drivers 
Total drivers as presented in the following graph ![Total drivers](analysis\Fig3.png) seem to follow the same discrepancy between city types with a bigger amount in urban areas, and lower in rural. 
 The percentages as presented in the following pie chart shows 80.9% for urban drivers, 16.5% for suburban drivers and 2.6% for rural drivers.  ![Total rides percentage by city Type](analysis\Fig7.png)
 When one compares the total percentage of drivers with the percentage of total rides,  [Total rides percentage by city Type](analysis\Fig6.png), there’s an interesting behaviour where urban shows a percentage of drivers 80.9% and lower percentage of rides (68.4%). Suburban show a percentage of drivers of 16.5% and 26.3% of total shared rides, while rural has a total percentage of drivers of 2.6% and a percentage of shared rides of 5.3%. This findings seem to hide an interesting correlation and behaviour, however for objective conclusions further statistical analysis would be needed, perhaps to deny or verify and underlying correlation. It does seem that almost all drivers in rural areas share more drives than urban considering the higher percentage of drivers found there. The drive share seem to be more prone to happen than urban areas. 

- Total fares 
 
The highest fares rates reside in urban areas compared to rural, while suburban is in between as previously described and clearly seen in the [Line chart](analysis\total_fares_by_city_type.png).
The total percentages of fares are as shown in the graph, ![Total fares percentage by city Type](analysis\Fig5.png). The percentages as presented in the following pie chart shows 62.7% for urban fares, 30.5% for suburban fares and 6.8% for rural fares.

- Average fare per ride and driver
The total fares averages show to be higher in urban areas compared to suburban in the middle and urban in the lowest. Average fare for Rural was 55.49%, for suburban 39.50% and for rural 16.57%
![Table1](analysis\avgfareperdriver.png)


- Total fare by city type. 
As seen in [Table1](analysis\avgfareperdriver.png), Total fares by city type was from highest to lowest in US Dollars, 39.854.38$ for urban areas, 19,356.33$ for suburban and  4,327.93$ for rural areas. 

## Summary:
According to the following analysis the following recommendations are addressed

- Urban areas have a high percentage of drivers and the highest averages fares per ride, however despite a bigger amount of drivers in that area, the shared rides are not as frequent per driver. This could be related to a diversity of factors, including security or other means of mobility within the population. Discovering the probably factors could clarify strategies to increase the service use where the highest density of drivers and higher fares reside as it is in the urban area. The lowest fares seem to be starting the year in January, perhaps seasonal promotions and offers might increase the use of the service in the less active months.

- Suburban areas seem to have a balanced behaviour of all the factors. The use of shared rides as well as fares  seem stable. Lowest fares are seen in march but overall there are less hills and peeks compared to the other two. [Line chart](analysis\total_fares_by_city_type.png). Programs designed to increase the amount of drivers and users could provide a good option. Promotional programs could be implemented around the first 2 weeks of march, and at the beginning of January according to the current data, where the lowest fares are seen. However obtaining a longer period of time to understand the activity or use of the service is needed to prepare a clear plan. 

- Rural areas despite having a low percentage of drivers sharing drives, seem to be more active per driver. Fares however are the lowest, perhaps doe to low traffic and clearer paths. Knowing if the fares depend on the time or the distance could be useful information to recommend different strategies. For example, if fares are dependent on the distance, the low average fare per ride, might be because users choose to use the service for short distance rides only; here plans to promote longer distance rides might be helpful.  On the other side, if fares depend on time of the ride and not the distance withe lack of obstacles or traffic in the rode’s might explain the fares in play. 
Total fares in rural areas show the more stable of the three it stays in a range of 500$ behaving more less constant along the months. As seen in [Line chart](analysis\total_fares_by_city_type.png) the lowest fares are seen in the second week of January and another drop in the second week of February and the highest in April. It seems new years promotional options might be helpful. 

- Apart of what’s been recommended in general, further analysis would be helpful to understand the use of the service by city type in the whole year and design programs and offers to promote the service. 



