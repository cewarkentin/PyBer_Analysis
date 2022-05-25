# PyBer Analysis

## Overview of Project

We are working at PyBer, a Python-based ride-sharing app company. Our job is to analyze and create several types of visualizations to best illustrate relationships between the type of city (urban, suburban, rural) and the number of PyBer drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city.

### Purpose

The analysis and visualizations produced will help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods.

### Process

We used Python, Panda's libraries, Jupyter Notebook, and Matplotlib to create a variety of charts that showcase the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city.

## Results

Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### PyBer Ride-Sharing Data

The figure below represents the total number of rides completed in each city compared to the average fare for those rides. The cicle size correlates with driver count per city. Different colors are used to indicate whether the city is considered urban, suburban, or rural.

![Fig1](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig1.png)

While there is some overlap in total number of rides based on city type, generally the number of rides per city increases as the cities increase in population and activity (i.e. moving from rural cities to suburban cities to urban cities). Additionally, as the total number of rides increases, the average fare generally decreases. Because of the relationship between total number of rides, average fare, and city type, it also appears that as areas progress from rural to suburban to urban, the average fare also generally decreases.

### Ride Fare Data

The figure below is a pie chart illustrating where the majority of PyBer fares come from.

![Fig5](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig5.png)

According to the provided data, 62.7% of PyBer fare is made during rides in urban cities, 30.5% of PyBer fare is made in suburban cities, and 6.8% of PyBer fare is made in rural cities.

It is unclear whether PyBer fares are based on supply-and-demand or a flat rate. If they are based on supply-and-demand, this data could additionally be used to interpret ride demand versus driver availability. However, fare data is further nuanced by the factor of whether there is a relationship between ride length (and therefore ride price) and city type. While this information would be interesting and insightful, it would require much more analysis.

The box-and-whisker plot below can start to parse out a relationship between ride price and city type-- the figure illustrates the range of prices for a PyBer ride depending on the type of city.

![Fig3](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig3.png)

A PyBer ride in an urban city can cost between $4-45, with an average cost of $25. A PyBer ride in a suburban city can cost between $12-50, with an average cost of $30. A PyBer ride in a rural city can cost between $10-59, with an average cost of $37.

The standard deviation for PyBer prices in urban cities is $12. The standard deviation for PyBer prices in suburban cities is $11. The standard deviation for PyBer prices in rural cities is $15.

The average PyBer ride in a rural city is more likely to be more expensive than over 75% of rides in urban cities and more expensive than almost 50% of rides in suburban cities. The prices of PyBer rides in rural cities indicates a potential limiting factor to the rural customer market.

### Driver Count Data

The figure below is a pie chart illustrating what types of cities PyBer drivers are in.

![Fig7](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig7.png)

The majority of PyBer drivers (80.9%) work in urban cities, 16.5% of PyBer drivers work in suburban cities, and only 2.6% of PyBer drivers work in rural cities.

The figure below is a box-and-whisker plot illustrating the number of PyBer drivers at any point in time in a city depending on the type of city.

![Fig4](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig4.png)

At any given point in time, urban cities could have between 3 and 73 drivers, with an average of 37 drivers available. Suburban cities could have between could have between 1 and 25 drivers, with an average of 16 drivers available at any point in time. Rural cities could have between 1 and 9 drivers, with an average of 4 drivers available at any point in time.

Regardless of city type, the minimum number of drivers at any point in time were fairly close (4 in urban cities, 1 in suburban cities, and 1 in rural cities). However, the average number of drivers available increases as human population and activity increases. Additionally, the range of potential available drivers increases as human population and activity increases.

Futher data analysis is required to determine if PyBer activity in an area is limited by driver availability or by the number of rider requests. With said additional analysis, it would be possible to determine if PyBer activity in rural areas could potentially be increased by increasing driver availability.

### Ride Count Data

The figure below is a pie chart illustrating where PyBer rides are occurring.

![Fig6](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig6.png)

According to the provided data, 68.4% of PyBer rides occurred in urban cities, 26.3% of PyBer rides occurred in suburban cities, and 5.3% of PyBer rides occurred in rural cities. Similar to the first figure in the PyBer Ride-Sharing Data analysis section, generally the number of rides per city increases as the cities increase in population and activity (i.e. changes from rural to suburban to urban).

The figure below is a box-and-whisker plot illustrating the number of PyBer rides at any point in time in a city depending on the type of city.

![Fig2](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig2.png)

At any given point in time, between 12 and 39 rides could be occurring in an urban city, with an average of 24 rides at one time. However, the single instance of 39 rides occurring at one time is a statistical outlier. Suburban cities could have between could have between 9 and 27 rides, with an average of 17 rides at one time. Rural cities could have between could have between 3 and 12 rides, with an average of 6 rides at one time.

The fourth quartile of the rural ride count data overlaps with some of the first quartile of the suburban ride count data; 25% of the data on the higher end of the rural data overlaps with less than 25% of the data on the lower end of the suburban data. Additionally, the upper limit of the range of rides in rural cities is the lower limit of the range of rides in urban cities.

The range of rides occurring at any point in time in rural cities overlaps with the range of rides occurring in suburban cities, and the range of rides occurring at any point in time in suburban cities overlaps with the range of rides occurring in urban cities.

Analysis of ride count data can start to inform whether PyBer activity in an area is limited by driver availability or by the number of rider requests, but does not fully answer the question. The overlap in the number of rides completed in rural cities overlapping with suburban cities-- and even almost overlapping with rides completed in urban cities-- could indicate a potential larger market for rides in rural cities. It would be helpful to have information on ride requests received versus ride requests completed to gain a better picture.

### Total Fare by City Type

The line graph below illustrates the weekly total fare in the three city types (urban, suburban, and rural) between 1 January 2019 and 29 April 2019. 

![PyBer_fare_summary](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Without regression analysis, it is hard to tell if there is any significant trend between specific time of year and total fare in any of the three city types (i.e. fare is significantly higher in one month and lower in another). Visually, there appears to be a spike in total fare in the third week of February for all three city types. However, it is clear that regardless of time of year between 1 January and 29 April, total fare is always highest in urban cities, then suburban cities, and always lowest in rural cities. In the time period included, there does not appear to be a "busy season", regardless of city type.

## Summary

Based on the results, I recommend:

- Further investigation into why there are fewer drivers in rural areas.
  - Further investigation into ride requests received versus ride requests completed in the various city types.
  - Further investigation into ride lengths in the various city types.
  - Futher investigation into driver pay in the various city types.
- Increasing driver availability in rural cities to test for an increase in ride requests.
- Decreasing ride prices in rural citites to decrease potential limiting factors to the rural customer market.
