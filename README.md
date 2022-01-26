# PyBer_Analysis

## Overview of the analysis

The purpose of this analysis is to analyze all rideshare data from January 2019 to early May 2019 focusing in on city type(Urban, Suburban, Rural). We'll look at this data to determine whether or not there are differences in each city type and how that data can by used Pyber to make decisions.

## Results

Many of the results we see are as expected such as demand for Pyber is greater in the urban cities than the suburban and rural cities. We saw urban rides reach 1,625 during the aforementioned time period while we saw rides of 625 and 125 for suburban and rural rides respectively during the same time period. Also, the average fare per ride for each city type is in line more or less with what might be expected. The higher average fare in rural areas indicates that the length of ride is longer. This makes sense based on the density of those areas. 

It is worth noting that the allocation of drivers is fairly skewed, particularly between urban and rural. There are too many urban drivers while we see a shortage of rural drivers based on the number of trips. This is definitely an area to be looked at for enhancing the revenue of the company. The first thing to do would be to adequately staff the rural areas with an appropriate amount of drivers. This skewed allocation also affects the average fare per driver. Average fare per driver in rural areas is much higher than what we see in urban and suburban areas. This suggests that the length of ride in rural areas is even longer one might expect. It could also be inferred that there is demand in the rural areas not being met due to this fact. 

The image below is a graphical representation of the PyBer data dataframe. It backs up one item that has already been discussed above. Urban is by far the biggest generator of revenue. One thing that the graph represents well is the spikes and dips for each city type. Across the board between February and March we see an uptick in all three city types. From my perspective they all follow a general trend but there are a few anomalies such as the dip in suburban around mid april wouldn't hurt to look at. 

![image](https://github.com/dannybarto/PyBer_Analysis/blob/main/Resources/TFCT.png)

## Summary
My first recommendation is to work on acheiving a better driver to customer ratio. It appears the rural areas are significantly underserved while the urban areas could stand to have a few less drivers in the mix. Another recommendation would be to look at the fares in rural areas as they are higher on average. Maybe adjusting the fares could lead to more ridership. Suburban city types seem be the most stable and efficient model. I would recommend studying suburban a little more in depth to see exactly what's working there. 


