# **bikesharing**
---
## Project Overview
The purpose of this analysis was to convince investors that a bike-sharing program in Des Moines is a solid business proposal by showing the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each hour of each day of the week, and the number of bike trips for each type of user and gender for each day of the week. This bike trip analysis utilizes Pandas for data conversion and Tableau for data visualization. 

Please follow this link to view the published Tableau story: [NYC CitiBike Story](https://public.tableau.com/app/profile/christina.galley/viz/NYCCitiBikeStory_16417795923720/NYCCitiBikeStory?publish=yes)

---
## Results
The map below displays the top starting locations of bikesharing users. The darker the circles, the more bikes are being rented in that location. The most popular tourist attractions in Des Moines seem to also be the areas where the most bikes are rented. Many tourists have limited transportation and bikeshaing is an easy way to get around to see the attrations quickly and efficiently. So, it would be beneficial to place more bike rental stations in that area.
    **Top Starting Locations**
    ![picture alt](https://github.com/ChristinaGalley/bikesharing/blob/main/Resources/Top_Starting_Locations.png)
    
The graph below dipslays the number of bikes rented per hour of the day in the month of August. The highest amount of rentals is around 8AM and 5/6PM.
    **August Peak Hours**
    ![picture alt](https://github.com/ChristinaGalley/bikesharing/blob/main/Resources/August_Peak_Hours.png)

The graph below dipslays the length of time the bikes were rented for by gender of customer. Bikes are only cheked out for less than an hour by all customers since they are not traveling far within the city. The peak checkout time for female customers is 6 minutes, and the peak time for male customers is 5 minutes. It is also notable that there are significnatly more male customers than female customers.
    **Checkout Times by Gender**
    ![picture alt](https://github.com/ChristinaGalley/bikesharing/blob/main/Resources/Checkout_Times%20by_Gender.png)
    
The heatmap below dipslays the number of trips each customer by gender checks the bikes out for at the time of day throughout the week. Again, we see an increse in rentals around 8AM and 5/6PM as well as more male customers than female customers.
    **Trips by Gender (Weekday per Hour)**
    ![picture alt](https://github.com/ChristinaGalley/bikesharing/blob/main/Resources/Trips_by_Gender_Weekday_per_Hour.png)
    
The heatmap below dipslays the number of trips each customer by gender checks the bikes out for each day of the week. Again, we see signfiicantly more male subscribers than female subscribers. There are also significantly more subscribers renting bikes then random customers. Overall, the number of rentals seem to stay pretty consitant throught the week with perhaps a slight increase on Thursday, Friday, and the weekend.
    **User Trips by Gender by Weekday**
    ![picture alt](https://github.com/ChristinaGalley/bikesharing/blob/main/Resources/User_Trips_by_Gender_by_Weekday.png)

---
## Summary
In conclusion, bikes are rented thgrough the week most frequently in the morning around 8AM and in the evening around 5/6PM and most frequently by men. This suggests that the majority of rides may be related to commute taking into consideration that the lengths of the rides average less then 10 minutes. The rest may be short trips around town by tourists. The data also suggests that bike sharing is more popular with men than women. Taking these conslusions into consideration, I would recommend the additional visualizations for further analysis:

-creating a graph that displays length of checkout time to user type (customer/subscriber) to determine any difference in ride time between tourists and locals, granted that locals using bikeshare for cummute will likley be subscribers compared to tourists who are only staying in town short term and less likley to buy a subscription.

-adding the user type (customer/subscriber) as a filter on the "Top Starting Locations" map to identify a possible difference in locations tourists bikeshare versus the locals.
