# RIDE SHARING ANALYSIS
_Analyzing Ride-Sharing data from 3 types of Cities across a 5-month period_


## Overview of the Project

PyBer, a ride sharing app company seeks to improve its services in all the cities it operates in. The aim of this project was to analyze rideshare data from all the cities categorized into citytypes namely; rural, suburban and urban with the aim to provide the CEO of the company with vital information to make the right decision.
The project used data collected from January to May in the year 2019.

Key objectives of the project include:
- Produce the total number of rides per city type
- Determine the total number of drivers in each city type
- Get the total fares for each city type
- Generate a dashboard showing the performance of each city type based on the total of rides,fares, drivers as well as average fare per ride and average ride per driver.
- Produce a line chart that gives a vivid presentation of the trends uncovered in the analysis. 


## Results of Analysis

* **Total Rides**

In the analysis, the total rides for each city type was produced using the groupby function to obtain a series and then derived all the rides per city using the count method. The results showed that 1,625, 625, 125 was the total rides recorded for urban, suburban and rural cities respectively. This meant that there was a high patronage of Pyber in the urban cities than the remaining city types. 

* **Total Drivers**

The output of the analysis of PyBer_data to reveal the total driver count per city type showed that PyBer had more drivers in the urban cities than other categories of cities it operated in. The results showed 2,405 drivers in the urban cities, 490 in the suburban and 78 in rural cities.

* **Total Fares**

In order to get the total fares per city type, the count method was applied on the "fair" column of the pyber datatframe after the groupby funtion had been used to generate a series with "type of city" as it index. The suburban city type recorded $19356.33 during the period. However though this was more than 4 times the total fares generated by the rural type, the Urban cities continued to contirbute the highest amount of fares. By the end of May, 2019 a total of  39854.38 was recorded as fares from the Urban cities.

* **Average Fare per Ride and Average Fare per Driver**

The analysis also showed that the average cost of using PyBer service was high in the rural cities than the suburban. The cost of riding in the urban city was relatively cheaper. The average ride in the urban city cost $24.53 during the period under review.
Following the same trend was the average fare per driver. The average fair per driver in the rural type was high and was less in the urban cities. 


_*Example of code used to generate the total_votes of the election*_

![Alt text](https://github.com/emmanuelbrim/Election_Analysis/blob/main/Resources/Total%20Votes.PNG)



* **Visualization using line chart**

A clear description of the trends uncovered in the analysis was displayed using the multiple-line chart. 
The lines show how each city type performed during the period and gives support the results produced in the analysis.
On the chart the yellow line representing urban cities was high above all the other lines since it recorded the highest in total fares, whiles suburban and rural types followed respectively.
The blue line shows how rural cities performed showing the highest increase in fares during the last week of March only to drop back in early April.
On the otherhand the red line on the chart also show how the fares generated in the Suburban group began to increase in mid April after a decline earlier that same month.


_*Example of code used to generate the total_votes of the election*_

![Alt text](https://github.com/emmanuelbrim/Election_Analysis/blob/main/Resources/Total%20Votes.PNG)



## Summary

From the analysis it is evident that the largest market for PyBer serives was in the urban cities due to higher driver count and rides.
It is therefore recommended that intensive campaigns to get more users to sign onto the app should target especially the rural city population.
The average fare per ride in the rural city type was high compared to all the other types, hence management must seek inovatie ways of reducing this cost to users to encorage patronage. 
On the chart all city types significant increase fares in febuary, further anaysis is required to determine what caused the surge and make decisions that will trickle that increase to other months of the year. 

 
