# NHTSA TRAFFIC DATA ANALYSIS REPORT

## Overview

  The National Highway Traffic Safety Administration (NHTSA) is a United States government agency that has a very important mission, namely protecting the public by saving lives, preventing injuries, and reducing the economic impact resulting from traffic accidents. To achieve their goals, NHTSA combines a variety of comprehensive approaches.
  
  One of NHTSA's primary roles is to collect, analyze, and publish data about traffic accidents that occur in a given year. This data includes various important information such as the type of accident, location, causal factors, and impact on injured people. Through this in-depth data analysis, NHTSA can identify existing crash trends and patterns, understand their causes, and formulate better solutions to reduce the number of crashes in the future.
  
## Objectives

  Analysis of 2021 data was carried out to identify traffic safety problems. The objective is to develop regulatory recommendations to improve safety and reduce the risk of accidents. The analysis reveals trends in accident types and causal factors such as weather conditions and driver behavior. This allows the development of more specific regulations and more effective prevention strategies. Key indicators have been identified as the basis for regulatory recommendations:
  1. By accident categories (road type, intersection type, lighting conditions and atmosphere conditions);
  2. By regions where the crash occurred (top 10 states, top 10 cities, and rural vs. urban areas)
  3. By the time the accident occurred (by month, day and hour)
  4. By conditions of the driver when the accident occurred (drunk or sober driver and the time of the incident)

  This analysis is not just limited to internal data. To ensure that the resulting regulatory recommendations are well founded, relevant external information is also taken into account.
  
## Analysis

  Data analysis involves a structured process with the use of Google Sheets, Microsoft Excel, and SQL to clean and process data. SQL is used for data aggregation, percentage calculations, and custom queries. Next, the data is transformed into informative visualizations. Analysis of accident type data is an important first step to understanding traffic safety and recommending more effective regulations.
  
### 1. By accident categories

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/crash%20type-all.jpg?raw=true)

  The most common type of accident was not a collision with a motor vehicle, with 21,768 incidents. Apart from that, various other forms of accidents occurred such as angle (6,416), front-to-front (3,618), and front-to-rear (2,424). This data reflects the diversity of situations that cause road accidents. Furthermore, the analysis will examine several factors, namely the type of road, type of intersection, lighting conditions and atmosphere conditions that can influence accidents. Correlations between accident types and these factors will be identified. Apart from that, the findings will be considered based on the conditions when the accident occurred.

- Road type and intersection type

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/road%20type-not%20collision%20with%20motor%20vehicle.jpg?raw=true)

  The highest accident occurred on the Main Arterial - Other road type (5,315 incidents) in a single accident. This also applies to angle (2,691), front to front (1,184) accidents, and several other types. Interstate had the highest accident type front to rear (853) and sideswipe: same direction (208), while Minor Arterial had the highest accident type sideswipe: opposite direction (131). Rear to rear accidents which are less common (2 incidents) are distributed on the Principal Arterial - Other and Major Collector road types. This shows that accidents often occur on long roads, with high volumes, and high-speed motorized vehicles.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/intersection%20type-not%20collision%20with%20motor%20vehicle.jpg?raw=true)

  The highest number of accidents also occurred on straight roads (18,692 incidents) in collisions with a non-motor vehicle. This is an important finding and this type of intersection is also a frequent incident site for other types of accidents, except angle (3.108) which is more common at intersections.

- Lightning conditions and atmosphere conditions

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/light%20condition-not%20collision%20with%20motor%20vehicle.jpg?raw=true)

  The lighting condition that had the highest number of accidents was the daylight category, with a total of 8,208 incidents in single accident types. These findings indicate that collisions with a non-motor vehicle occur in daylight, which is during the day. And, this category also tops the list for other types of accidents.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/atmosphere%20condition-not%20collision%20with%20motor%20vehicle.jpg?raw=true)

  Correlating with the results of lighting conditions, the atmosphere condition that causes the most accidents is the clear category, with a very high total incident, reaching 15,203 in collisions with a non-motor vehicle. This shows that the majority of incidents do not occur due to weather changes such as rain, snow, fog, or the like. These findings also apply to other types of accidents.

### 2. By regions where the crash occurred

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/states-all.jpg?raw=true)

  Further analysis was carried out by observing in which state these accidents occurred as a whole. From these results, ten states with the highest accident rates were selected. The most accidents occurred in Texas (3,513), California (3,484), and Florida (3,091). Demographic [factors](https://datacommons.org/ranking/Count_Person/State/country/USA?h=geoId%2F48) such as population are also considered. California has the highest population (about 39 million), followed by Texas (about 29 million), but Texas has a higher accident rate even though the population difference is not that great. A deeper analysis of cities in each state could provide more detailed insight into accident patterns, although there are some interesting anomalies.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/texas.jpg?raw=true)

  When we look at the accident data for various cities in each of the ten states, it is found that there are cities with a high number of accidents, but specific information about the location of these accidents is not available in the data. For example, in the state of Texas, the highest number of accidents does not have a description of which city the accident occurred in. In addition, the number of these accidents is quite large when compared to those with clear city location information.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/new%20york.jpg?raw=true)

  We can see that the only exception is the state of New York. This shows that in the accident data for Texas, the highest number of accidents cannot be related to a particular city, while in New York, New York City has a total of 117 accidents.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/urban%20vs%20rural-all.jpg?raw=true)

  Analysis was also carried out on data related to the number of accidents that occurred in rural and urban areas. The results of this analysis provide an overview of accident patterns in various types of environments. It was found that more than half of the total number of accidents for all types of accidents were recorded in urban areas, namely around 57.5% of the total incidents (20,101). Meanwhile, the number of accidents in rural areas reached around 42.5% (14,829).

### 3. By the time the accident occurred

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/month-all.jpg?raw=true)

  Data relating to the number of accidents that occurred each month was examined as well. This analysis aims to understand accident patterns during various seasons in 2021. The highest number of accidents occurred in October, with a total of 3,517 incidents. What is interesting is that the accident rate is relatively high and stable from June to October. On the other hand, the lowest number of accidents was recorded in April, with the number of accidents reaching 2,103 incidents.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/day-all.jpg?raw=true)

  The day with the highest number of accidents was Sunday, with a total of 6,342 incidents. This is an interesting finding because Sunday is often considered a holiday and there may be certain factors that influence the accident rate on this day.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/all%20accident-avg%20per%20hour.jpg?raw=true)

  The highest average number of accidents per day was recorded at 12 PM, with an average of 5.9 incidents or, if rounded up, around six incidents. These findings suggest that the midday hour is the time of day when the average risk of accidents is highest. This trend then appears to stable until 3 PM in the afternoon, meaning that during this period, the number of accidents tends to be high and consistent.

### 4. By conditions of the driver when the accident occurred

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/drunk%20vs%20sober-all.jpg?raw=true)

  The number of drivers who were sober dominated, namely around 74.2% of the total accident incidents (26,292 incidents). Meanwhile, only around 25.8% of drivers were drunk when they had an accident (9,120 incidents). This finding is interesting because it indicates that drunk drivers account for almost three-quarters of the total number of recorded accidents.

![](https://github.com/jessie-kusumawardhani/NHTSA-project-EN/blob/main/Total%20Crash%20by%20Hour%20(Sober%20vs.%20Drunk%20Driver).jpg?raw=true)

  The highest number of accidents in one day occurred at 12 PM for drivers who were not drunk with a total of 1,627 incidents. On the other hand, drunk drivers had the highest accident rate at 5pm with a total of 708 incidents.

## Conclusion
  This type of accident generally does not involve motorized vehicles (21,768). The analysis is still in the early stages, looking for correlations with types and conditions such as road types, intersections, lighting and weather. Most accidents occur on large-volume roads such as Principal Arterial - Other, which incidentally are categorized as roads without intersections. Incidents also mostly occur during the day and in sunny conditions. Texas, California, and Florida have the highest accident rates. While the population of the three states is also the highest, there are anomalies such as in many cities where accidents are not identified. Also, more than half of the accidents occurred in urban areas (57.5%). Accidents peaked from June to October and on Sundays, mainly between 12 PM - 3 PM, with about six crashes by 12 PM by sober drivers (74.2%).

## Recommendation
- In the United States, students can [obtain](https://www.policygenius.com/auto-insurance/driving-age-by-state/#:~:text=In%20the%20U.S.%2C%20you%20can%20typically%20apply%20for%20your%20full%20driver%E2%80%99s%20license%20between%20the%20ages%20of%2016%20and%2018.) a driver's license at [age](https://www.rhinocarhire.com/Drive-Smart-Blog/Minimum-Driving-Age-Country/Minimum-Driving-Age-State.aspx) 16-18, with some states granting it at age 17 or 18. Summer break [lasts](https://moonpreneur.com/blog/usa-school-holiday-calendar/#:~:text=among%20all%20individuals.-,Summer%20Break%C2%A0,length%2C%20with%20some%20districts%20offering%20as%20many%20as%20three%20months%20off.,-Labor%20Day) from May/June to August/September. This may indicate the possibility of young drivers undertaking long journeys during the summer holidays. However, more in-depth data is needed regarding the ages of drivers involved in accidents for more precise recommendations, such as special training or special permits for young drivers who travel long distances.
- In the [summer](https://www.ncei.noaa.gov/access/monitoring/monthly-report/national/202108#season-temp:~:text=During%20meteorological%20summer,for%20the%20season.) of 2021, most of the major states in the United States experienced above average temperatures, reaching 74°F or 23°C. This even surpassed the extreme heat of 1936 during the [Dust Bowl](https://en.wikipedia.org/wiki/Dust_Bowl). That same year, California faced wildfires mostly [caused](https://ww2.arb.ca.gov/wildfires-climate-change) by extreme weather and climate change. It is possible for a driver to have a collision with non-motor vehicle due to extreme heat, especially in summer. Therefore, it is recommended to consider the rules of prohibiting driving or limiting vehicle volume during the day, especially on Sundays between 12 PM - 3 PM.
- Extracting data on the types of vehicles involved in accidents (motorbikes, cars, buses, trucks) can be considered for more in-depth analysis to improve road safety and reduce accidents in the future.
