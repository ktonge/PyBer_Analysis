# PyBer_Analysis
## Overview of Analysis
The purpose of this activity was to dive into combiming and working with data using pandas and matplotlib.  

We initially started with two separate data sets (city_data.csv and ride_data.csv) both with their own information about ride-shares. I created a dataframe of ride-sharing data by city type to focus on data in the contect of rural, suburban, or urban cities.  

## Results 

### Differences betweeen city types

![stuff](https://github.com/ktonge/PyBer_Analysis/blob/main/analysis/summary_stats.png)


As we can see in the graphic above, the highest average fare per ride is in Rural areas, with Urban areas having the lowest.  Most significantly, the average fare per driver varies dramatically between Urban ($16.57) and Rural ($55.49) communities.  This could be in part because in the Urban areas there were more total rides than total drivers, whereas the opposite was true for Rural communities in the data. 


### Rural Communities: less drivers, higher fares  
This trend continues if we look at other aspects of the data.  Rural riders made up 6.8% of total fares, a greater portion than their 5.3% of total rides.  Drivers in Rural cities made up 2.6% of total drivers.  

![pietwo](https://github.com/ktonge/PyBer_Analysis/blob/main/analysis/Fig5.png)

![pieone](https://github.com/ktonge/PyBer_Analysis/blob/main/analysis/Fig7.png)

On the other side whereas Urban riders make up 66.4% of all rides, they make up 62.7% of all fares.  Suburban riders are sort of inbetween.  They make up 30.5% of all of the fares, and only 16.5% of all drivers.  Rural communities have about half the total percentage of drivers as they do total percentage of rides, Suburban communities also had more riders than drivers.  Both of these communities also had a greater proportion of fares.  

### Fares over time

![fares over time](https://github.com/ktonge/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

The graph above shows weekly total fares over time.  We see alot more variance and up-and-downs with the Rural data, whereas Urban rideshare usage steadily increased from January through March.  We saw a similar increase in Suburban communities.  Suburban and Urban communities had their peak usage in Feburary, whereas Rural communities had their peak fares in March.  

## Summary and recommendations
As the purpose of this analysis was to look for information that could support or help a rideshare company, there are two different ways we could look at it: either you could increase the number of drivers in rural areas, bringing in more fares but potentially lowering price, or you could look to decrease drivers in urban areas, bringing up fares but potentially lowering overall rides.   There are also many reasons why fares in rural or suburban areas might be more expensive, it could be interesteding to invest further in research about what types of trips are being taken (work, home, school, etc), as well as the distance of those trips, and the fare per mile.  Another interesting area too look into would be average driver trip duration.  







