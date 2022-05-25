# PyBer Analysis

## Overview of Project

We are working at PyBer, a Python-based ride-sharing app company. Our job is to analyze and create several types of visualizations to best illustrate data contained in large CSV files.

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

Analysis of Ride Count Data can start to inform whether PyBer activity in an area is limited by driver availability or by the number of rider requests, but does not fully answer the question. It would be helpful to have information on ride requests received versus ride requests completed to gain a better picture.

The figure below is a pie chart illustrating where PyBer rides are occurring.

![Fig6](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig6.png)

![Fig2](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig2.png)

### Ride Fare Data

![Fig3](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig3.png)

![Fig5](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/Fig5.png)

### Total Fare by City Type

![PyBer_fare_summary](https://github.com/cewarkentin/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

## Summary

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
