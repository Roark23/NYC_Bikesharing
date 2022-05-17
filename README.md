# NYC Citi Bike
## Purpose and Overview
Using Tableau, I have created data visualizations outlining the bike sharing program in New York City. The purpose is to analyze the data to better understand the operations of the business and how a bike share venture operates in NYC. The goal is to see if there is potential to expand this business in other cities. 

Tableau is widely used for data visualization in today’s professional world. Tableau is uniques in how it allows data visualization professionals to create visually appealing data stories that are visually appealing and easy to comprehend for a non-technical user. Moreover, Tableau provides the tool to create powerful analytic dashboards and tell a clear story.

I've created a Tableau story of the NYC Citi Bike manipulating real raw data from the [!NYC Citi Bike Website](https://ride.citibikenyc.com/system-data) 

To manipulate this data, I needed to use Pandas to convert the integers to a datetime datatype.

My Tableau story can be viewed here: [!NYC Citi Bike Story](https://public.tableau.com/app/profile/roark.segler/viz/NYCCitiBikeStory_16528051154600/NYCCitiBikeStory?publish=yes)

## Results
#### Basic Info
I have provided a general overview for the first page of my Tableau story for users to better understand the data and results: 

[!General_Overview_for_Citi_Bike_Customer_Info](/Resources/General_Overview.png)

This image outlines the total number of rides, customer type, and the peak hours highlihted by gender.

#### Checkout Time for Users
The number of trips is on the y-axis and trip duration is on the x-axis. The X-axis is divided into hours (at the top) and minutes (at the bottom) highlighting more detailed information about trip duration.

[!Checkout_Time_for_Users](/Resources/Checkout_time_for_users.png)

 From the graph, it is evident the most frequent trip duration is between 3 hours to 9 hours (about 1,101,425 trips), followed by longer trip duration of 9+ hours (about 1,021,670 trips). The shortest trip duration (less than 3 hours) account for about 236,526 trips.

#### Checkout Time by Gender
The graph shows the trip duration on the x-axis and the number of checkout bikes on the y-axis. The X-axis is divided into hours (at the top) and minutes (at the bottom) just like before for more detailed information about trip duration.

[!Checkout_Time_by_Gender](/Resources/Checkout_time_per_gender.png)

The three different colors represent the classification of genders. Green represents male, purple shows female and grey outlines an unknown gender. From the graph, we can see that males checkout far more bikes compared to females or unknown genders. This difference is evident especially between an hour and 9 hours of trip duration. However, it is important to note the trip duration trend is similar among all genders.

#### Trips by Weekday per Hour

[!Trips_by_Weekday_per_Hour](/Resources/trips_by_weekday.png)

The graph shows number of trips per hour and per weekday. The graph has hours on the y-axis and weekdays on the x-axis. The color indicates the number of trips. Darker color indicates more trips, while lighter color indicates less trips. Form the graph we can see that the busiest times are in the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm. On weekends (Saturday and Sunday) the busiest times are in the middle of the day approximately between 10 am and 6 pm.

#### Trips by Gender (Weekday per Hour)

[!Trips_by_Gender_weekday_per_hour](/Resources/trips_by_gender.png)


#### User Trips by Gender by Weekday

[!User_Trips_by_Gender-by_Weekday](/Resources/Trips_by_gender_by_weekday.png)

#### Bike Utilization

![Bike_Utlilization](/Resources/bike_utilization.png)

#### Top Starting Locations

![Top_Starting_Locations](/Resources/top_starting_locations.png)

#### Top Ending Locations

![]