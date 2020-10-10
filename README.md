# Rideshare in different city types, an analysis.

## Overview
Using Python and Pandas, the ride-sharing data of a fictional provider was analyzed by city type. The number of rides, drivers, and fares were part of a detailed investigation into operations in three different city types (urban, suburban and rural).  This report summarizes how the data differs by city type and how those differences can be used by decision-makers at the company.

## Results
In order to identify any differences between the size and density of the operational arena, the ride share data was grouped by one of three city types: 'Urban', 'Suburban', and 'Rural'. The differences in ride-share characteristics between the types of cities was stark.

1. Urban centers had significantly more total rides on average (1,625) compared to suburban (625) and rural ones (125). Urban centres had on average 30 times more drivers than rural centres, 2,405 compared to only 78. Suburban centres averaged 490 drivers. As a result urban cities had a higher average total fares in the time period examined (see table below). Most importantly, there are more drivers than rides on average in urban cities while the opposite is true for rural cities. This drives competition in urban cities lowering the average fare per ride while increasing it in rural cities. 

2. Less fare, larger share. While rural cities averaged fewer drivers, total rides, and total fare, they averaged the highest fares per ride ($36.62) compared to $30.97 in suburban cities and $24.53 in urban cities. The average fare per driver was also more than 3 times higher in rural cities compared to suburban ones, $55.49 and $16.57 respectively. Suburban cities had intermediate average fares per driver with $39.50. 

![summary_table.png](https://github.com/andrej-arsovski/PyBer_analysis/blob/main/analysis/summary_table.png)

3. Higher by week, higher by month. To get a closer look at the ride-share data, the weekly fares for the different city types were examined for a 4-month period between January and April, 2019. Unsurprisingly, the total fares were consistently and significantly higher week to week in urban cities compared to rural and suburban. The week ending Febuary 24 was a spike in total weekly fares in all city types, likely driven by Valentine's day. There is an even higher spike in rural cities for the first week ending April 14th, likely corresponding to Easter celebration. Fares show a distinct trough in the first week of January in all city types. This shows a drop in riding in the days after New Year's eve. Interestingly, in the week leading up to New Year's eve, the suburban cities had a high peak while urban and rural cities showed small drops. This is important insight into the travel habits of people in different city types and could be used to direct resources to different cities at different times.

![Pyber_fare_summary.png](https://github.com/andrej-arsovski/PyBer_analysis/blob/main/analysis/Pyber_fare_summary.png)

## Conclusions

In order to better serve their centres of operation and increase profits there are 3 suggestions based on the data analysis.
1. Incentivize rural drivers to increase total numbers. This could be done with a sign up bonus for example.
2. Set maximum driver numbers for urban cities. This could prevent over-competition and low prices.
3. Set minimum fare amounts. This could ensure driveers are fairly compensated for their work.
