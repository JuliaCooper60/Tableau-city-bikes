
# Tableau-city-bikes

# Introduction

![citi-bike-station-bikes](citi-bike-station-bikes.jpg)

### Background and Context:

The purpose of this report is to visualize the Jersey City rental bike data for 2019 to 2020 to understand the impact of COVID on riding patterns and identify changes post-COVID and search for trends that can lead to actionable insights. A key insight is that since COVID, the number of rides around Jersey City has increased, and the key finding is that there are an increased number of people choosing to ride bikes in New York City. In a large city such as Jersey City, a diverse array of transportation options will always be necessary to serve the population and keep traffic congestion to a minimum. Bike rentals are one option of many and should be encouraged because of the availability of bike lanes and the benefit of being an environmentally friendly selection.

### Overview of the Data              

The citibike data was downloaded from citibikenyc.com. For this analysis, the time period chosen is January 2019 to August 2022. It is noted that the data set changed in February 2021 and fields such as trip duration, gender and age were removed. New fields such as 'ride types were introduced. The fields used in the analysis are listed below.

Trip Data:

Trip duration: integer representing the total length of the trip in minutes was created in a pandas data frame 

Started at: Start of trip date and time e.g. 1/24/2018 7:31:33 PM

Ended at: Stop of trip date and time e.g. Stoptime1/24/2018 7:41:08 PM

Start Station Id

Start Station Name

Start Station Latitude

Start Station Longitude

End Station Id

End Station Name

End Station Latitude

End Station Longitude


Usertype: User type for this trip (Member or Casual)

Started At (Time Stamp date and time)

Ended At (Time Stamp date and time)

Distance: Miles travelled 

Weekend vs. Weekdays

### Limitations of the Data :

Tableau public has a limitation in terms of the number of rows and size of the data sets. The original data sets 

The data set has significant anomalies with end and start dates missing; dates recorded incorrectly. 

Merging data from 44 csv files in two different data formats was challenging. 

### Methods 

The data aggregations and cleaning steps are set out in the Jupyter notebooks 

### Key Findings: 

## More people are riding bikes in Jersey City since COVID and usage is increasing year on year- especially in the summer months.

## Number of rides and customer membership Profile 

* Overall, the number of rises has increased year on year from 2019 to 2022
* The number of casual customers has increased
* in 2020, the number of members using bikes decreased. This could be due to COVID  

Image of chart: ![Number_of_Rides_and_Customer_Profile](Number_of_Rides _and_Customer_Profile.png)

## Number of Rides by Month and Year: shows the difference in the number of rides from the previous year and as a percentage of all rides over all years

* The number of rides reduced significantly during COVID lockdown
* There was some recovery back to 2019 numbers over the summer/fall months of 2020
* The number of rides continued to increase in the summer /fall months of 2021. This trend increased even more  significantly in 2022

Image of chart: ![Number_of_rides_by_month_and_year](Number _of_rides_by_month _and_year.png)

## Number and Average Duration of Rides by Month by Year

* While the number of rides was higher in 2022, the average Trip Duration reduced compared to 2021
* The average distance travelled has steadily increased over the four years 

### The number of people riding from Jersey City to NYC has increased significantly since COVID and continues to do so, especially in the summer months.
Image of chart: ![Map_Start_and_End_Stations_by_Year](Map_Start_and_End_Stations_by_Year.png)

## Top Stations by Year 

* The top station has been Grove St Path across all Years 
* There has been variation in terms of business by Station between 2019 and 2022 

Image of chart: ![Top_Start_and_End_Stations](Top_Start_and End_Stations.png)

## Deeper Exploration of Ride Pattern - deeper exploration is required to better understand the drivers behind the variation in trends - this would be important for future planning 

* The Average duration of rides increased in 2021 but has trended down since April 2022
* The average duration by day of the week has varied significantly inn 2021 and 2022  
* The average distance travelled has steadily increased year on year 

Image of charts: ![Average_Duration_by_ride_by_month_by_year](Average_Duration_by_ride_by_month_by_year.png)
Image of charts: ![Average_Duration_Time_for_rides_by_Day_of_Week](Average_Duration_Time_for_rides_by_Day_ of_Week.png)
Image of charts: ![Avereage_Distance_by_WeekDay_vs._Weekend.png](Avereage_Distance_by_WeekDay_vs._Weekend.png)



