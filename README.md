# PyBer_Analysis

## Overview of Project

PyBer is a Python based ride sharing application company. Using pandas library, jupyter notebook, and matplotlib, we will showcase the relationship
between the type of city (urbran, rural, or suburban) and the number of drivers, average fares, amount of rides, and more. This will allow PyBer to see
their data at a quick glance to help make adjustments that will improve the company and benefit as many riders as possible in a variety of communiities. 

### Challenges

My biggest challenge was at the very end, when I had to reconfigure the dataframe to focus just on 1/1/19-4/29/19.  Even though I was doing the process correctly,
something went wrong along the way with my csv files.  For some reason, many dates were missing, which is why you will see "city_data2" and "ride_data2" in the 
"Resources" folder.  I downloaded these csv files again and repated the entire process over, and this time it worked correctly. 

![image](https://user-images.githubusercontent.com/64279232/127413807-d7292ecf-8d2d-4f3d-8f29-22afffaae40f.png)


## Analysis 
The purpose of this new analysis was to create a summary DataFrame and multiple line plot of the data specifically by city type (urbran, suburban, rural).  Instead of finding data for a specific cities in different areas, we were able to focus on each type of city as a whole and compare total rides, total drivers, total fares, average fare per ride, and average fare per driver in rural, suburban, and urban cities.  


## Results

After cleaning the data and sorting it, we are able to create a chart that summarizes the total rides, total drivers, total fares, average fare per ride, and averge fare per driver for rural, suburban, and urban cities.

![image](https://user-images.githubusercontent.com/64279232/127414083-63d31940-cedd-4d8e-8e24-01ec39d23a37.png)

We are also able to create a multiple line plot that shows the total weekly fares for each type of city. 

![image](https://user-images.githubusercontent.com/64279232/127414152-3ab1b80d-29e9-4939-a120-258a9501e033.png)

The most rides and drivers occur in urban areas, and the least rides and drivers occur in suburban areas, which also meaans the total fares in urban areas are the highest, followed by suburban, and rural.  The total fares for urban citeis was $39,854.38, the total fares for suburban citeis was $19,356.33, and the total fares for rural cities was a low $4327.93.  However, the average fare per ride is the highest in rural areas and the lowest in urban areas.  The average fare per ride in rural cities is $34.62 and is only $24.53 in urban cities.  Because of this, drivers also make more money in rural areas compared to urban areas. The average fare per driver in rural cities is $55.49 and is only $16.57 in urban cities.  


## Summary

I can't help but wonder if the average fare per ride for rural riders is the highest due to the demand of drivers or possibly the distance and duration of the drive.  However, I do have a few reccomendations for the CEO based on my data analysis.  
In rural and suburban areas, there were more rides then there are drivers, but in urban areas there were more drivers than rides, meaning some drivers did not get any work during this time period.  This can definitely be a cause for the average fare per driver being so low.  I would suggest giving incentives for some of these city drivers to work in more of the suburban areas near by, especially if they would make more money. 
I would also suggest decreasing the rate in rural areas, so the average fare per ride also decreases.  This would probably encourage more people to take advantage of PyBer in rural areas if it was more affordable. 
Lastly, I would suggest a further analysis on other factors that could be involved resulting in this current data, especially duration of ride and distance traveled.  Are rural rides more expensive because they are longer and take more time, or is it due to the lack of drivers?  And vice versa, are urban rides cheaper because they are traveling shorter distacnes, or is it because there is not as much of a demand.  Also, I would like to see more analysis on the day and time of day these rides occur.  Are rides more expensive during rush hour and late at night?  Do prices differ from weekends to weekdays?  All of this information can take this analysis much further. 
