Uber Trips Data Visualization R Markdown File
--
R Markdown File: 
--
http://rpubs.com/drucilal/564248

Density Based Clustering: Visualize the areas in New York that had at least 25 or more trips.
--

Objective: 
--
Inspired by: https://data-flair.training/blogs/r-data-science-project-uber-data-analysis/

Visualize Uber Picks Ups taken from April - September 2014 to gain an inner insights to craft better decisions. 

Data Set Description 
--
Shape: 4,534,327 observations & 12 variables

Variables Include
--
- Date.Time: Date and Time of Pickup
- Day
- Year
- Day of the Week
- Hour
- Minute
- Second
- Lat: Pick-up Latitude
- Lon: Pick-up Longitude
- Base: The TLC base company code affiliated with the Uber pickup

DataSet Source
--
https://github.com/fivethirtyeight/uber-tlc-foil-response

Observations
--
1: The number of trips increase during the 5 and 6 pm each day during the month of April. 

2: The highest number of trips were taken in September (~ 1,000,000) with the highest pickups occuring on Tuesdays.

3: In regards to the five bases in New York City, Base 02617 had the highest number of trips.

4: Looking into the same base (B012617), its highest number of trips occured in September.

Desity Based Clustering
---

Dig deeper into the month with the highest number of trips (September) and visualize the area that had at least 25 or more trips. 
----
Inspired by: https://www.kaggle.com/lambertosu/exploratory-analysis-with-density-based-clustering
 
 Procedure and Findings
 --
 - Data Set: September 2014 Uber Trips Dataset
 - Explanatory Data Analysis on the hourly averages of trips on each weekday
 - Saturday had the highest number of trips. 
 - Visualized the locations of the hot spots for uber drivers on a Saturday.
 - Visualized the average pick up rate vs hour of the day.
 - Findings: Increase in trips on Friday and Saturday evening and night.
 - Findings: Variation in afternoon through evening hours( 1-7 pm) September 6 and 13th.
 - September 13 contained the largest cluster (59) of locations. 
 - Day: September 13, 2014, Hours: 3 pm to midnight Using this map, we visualized 59 locations which had at least 25 pickups. ( map displayed in html link above)
 - Recommendation for Uber Drivers: Hot Spots to obtain more pick ups.
 
 
 

