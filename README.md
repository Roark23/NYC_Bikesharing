# NYC Citi Bike
## Purpose and Overview
Using Tableau, I have created data visualizations outlining the bike sharing program in New York City. The purpose is to analyze the data to better understand the operations of the business and how a bike share venture operates in NYC. The goal is to see if there is potential to expand this business in other cities. 

Tableau is widely used for data visualization in today’s professional world. Tableau is uniques in how it allows data visualization professionals to create visually appealing data stories that are visually appealing and easy to comprehend for a non-technical user. Moreover, Tableau provides the tool to create powerful analytic dashboards and tell a clear story.

I've created a Tableau story about NYC Citi Bike by manipulating real raw data from the ![NYC Citi Bike Website](https://ride.citibikenyc.com/system-data) 

To manipulate this data, I needed to use Pandas to convert the integers to a datetime datatype.

My Tableau story can be viewed here: ![NYC Citi Bike Story](https://public.tableau.com/app/profile/roark.segler/viz/NYCCitiBikeStory_16528051154600/NYCCitiBikeStory?publish=yes)

## Results
#### Basic Info
I have provided a general overview for the first page of my Tableau story for users to better understand the data and results: 


![General_Overview_for_Citi_Bike_Customer_Info](/Resources/General_Overview.png)


This image outlines the total number of rides, customer type, and the peak hours highlihted by gender.

#### Checkout Time for Users
The number of trips is on the y-axis and trip duration is on the x-axis. The X-axis is divided into hours (at the top) and minutes (at the bottom) highlighting more detailed information about trip duration:


![Checkout_Time_for_Users](/Resources/Checkout_time_for_users.png)


 From the graph, it is evident the most frequent trip duration is between 3 hours to 9 hours (about 1,101,425 trips), followed by longer trip duration of 9+ hours (about 1,021,670 trips). The shortest trip duration (less than 3 hours) account for about 236,526 trips.

#### Checkout Time by Gender
The graph shows the trip duration on the x-axis and the number of checkout bikes on the y-axis. The X-axis is divided into hours (at the top) and minutes (at the bottom) just like before for more detailed information about trip duration:


![Checkout_Time_by_Gender](/Resources/Checkout_time_per_gender.png)


The three different colors represent the classification of genders. Green represents male, purple shows female and grey outlines an unknown gender. From the graph, we can see that males checkout far more bikes compared to females or unknown genders. This difference is evident especially between an hour and 9 hours of trip duration. However, it is important to note the trip duration trend is similar among all genders.

#### Trips by Weekday per Hour
This graph outlines the number of trips per hour and per weekday. The trips by hour is labeled on the y-axis while the various days of the week is labeled on the x-axis. The color indicates the number of trips. Darker color indicates more trips and lighter colors indicate less trips:


![Trips_by_Weekday_per_Hour](/Resources/trips_by_weekday.png)


It is evident that most trips happen at times that are in the morning hours. Specifically, weekdays from 6am until 9am and in the evening on weekdays between 5pm and 7pm. For weekends, the busiest times are in the middle of the day from 10am to 6pm.

#### Trips by Gender (Weekday per Hour)
This graph shows the number of trips per hour and per weekday. It is very similar to the the graph above, except I have included another variable (gender) to better visualize the data. The graph is labeled with hours on the y-axis and weekdays on the x axis. The color indicates the number of trips. Darker color indicates more trips and lighter colors indicate less trips:


![Trips_by_Gender_weekday_per_hour](/Resources/trips_by_gender.png)


We can draw the same conclusions from the visualization before. We can see the distribution of the checkout times for all genders is similar. Additionally, we can see the graph divided by different genders. Males account for a significant number of the total trips.

#### User Trips by Gender by Weekday
This graph displays the number of trips by weekday, gender and user type (subscribers and customers). Gender is placed on the x-axis while weekdays and user type sit on y-axis:


![User_Trips_by_Gender-by_Weekday](/Resources/Trips_by_gender_by_weekday.png)


 It is evident that males have the highest number of the trips with the busiest days being Thursdays and Fridays. Females have a similar distribution of trips. Weekday trips are mainly conducted by subscribers while weekend trips are mainly booked by customers.

#### Bike Utilization
Here we can analyze all the bikes by their unique ID and their accumulated trips utilization. If you hover over any data points in the grap, you can view the bike id and time units for every bike:


![Bike_Utlilization](/Resources/bike_utilization.png)


Management can use this visualization to categorize bikes that are needed for maintenance etc.

#### Top Starting Locations
This visulaization highlights the top starting locations. The red represent subscribers and the blue shows the customers. Larger bubbles indicate more trips in its respective location:


![Top_Starting_Locations](/Resources/top_starting_locations.png)


We can see which stations are more popular and compare these locations amongst subscribers and customers. Specifically, the Downtown area is much more popular than the other areas in NYC.

#### Top Ending Locations


![Top_Ending_Locations](/Resources/top_ending_locations.png)


This visualization is the same as the one above. The only difference is that the data points represent the ending locations while the visualization before displayed the starting locations.

## Summary
By analyzing the visualizations above, we can start to make data driven reccomendations regarding the operations for NYC Citi Bike. 

For example, it is evident that most trips happen at times that are in the morning hours. Specifically, weekdays from 6am until 9am and in the evening on weekdays between 5pm and 7pm. For weekends, the busiest times are in the middle of the day from 10am to 6pm. We can schedule maintenance around the busy times to maxmize the trips. 

Also, the bike utilization graph outlines every unique bike ID and their respective number of trips. Management can plan rotations of the higher usage bikes and replace them in areas with lower bike usage.

There are always additonal visualizations we can use for further analysis. To better understand this data set, I would suggest:

1. A visualization highlighting the trip duration of checkout times per user types.

2. A visualization with more color filters in the top starting and top ending locations to see which stations are more popular amongst the different user types (subscribers and customers).

