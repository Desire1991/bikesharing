<<<<<<< HEAD
=======
**Citi Bike Sharing**


**Overview:**


In this project, I created a bike trip analysis to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To achieve it, firstly, I used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations to:


•	Show the length of time that bikes are checked out for all riders and genders
•	Show the number of bike trips for all riders and genders for each hour of each day of the week
•	Show the number of bike trips for each type of user and gender for each day of the week.
The analysis for this project has been published to Tableau Public (https://public.tableau.com/views/NYCCitiBikeAnalysis_16184009000370/CheckoutTimesforUsers?:language=en&:display_count=y&publish=yes&:origin=viz_share_link


**Results:**


•	Customer Types: from the pie chart, we can see that most of the users, 81% (1,900,359 users) of them, are the app's subscribers. 

![Gender_Breakdown](https://user-images.githubusercontent.com/74233163/114800541-87290b00-9d5f-11eb-82d5-28e5fd9cb6f3.png)

•	Checkout Times for Users: most of the trip lasts around 15 minutes, and then the trip duration steadily declines after that time  mark. 

![Checkout_Time_for_Users](https://user-images.githubusercontent.com/74233163/114800824-120a0580-9d60-11eb-8a37-9cb7ee6d831e.png)

•	Checkout Times by Gender: following the analysis of the trip duration, we can see Male uses the bike the most in terms of Gender Type.  

![Checkout-Time_by_Gender](https://user-images.githubusercontent.com/74233163/114800878-2bab4d00-9d60-11eb-9ccf-6e78c89fc5c6.png)

•	Trips by Weekday for Each Hour: we see a trend that during Weekdays, except Wednesday, most users use the bike from 5 pm to 6 pm. The second most usage hours during Weekdays are at 8am.  

![Trips_by_weekday_perHour](https://user-images.githubusercontent.com/74233163/114800978-69a87100-9d60-11eb-9c84-ce13a4e87035.png)

•	Trips by Gender (Weekday per Hour): adding up with the above analysis, we can see that Male use the bike program more than any other Gender Type. 

![Trips_By_Gender(weekdayperHour png)](https://user-images.githubusercontent.com/74233163/114801050-8fce1100-9d60-11eb-9d24-12d8fd88d026.png)

•	User Trips by Gender by Weekday: subscribers who are male use the bike program more than anyone, especially during Thursday.  ![User_Trips_by_Gender_byWeekday](https://user-images.githubusercontent.com/74233163/114801381-33b7bc80-9d61-11eb-8094-a99b0af240c3.png)



•	August Peak Hours: the bar graph shows us that the peak hours are in the morning when they start going to work (7 am), and in the evening when they get out of work (from 5 pm to 7 pm, with 6 pm is the most popular time slot).  

![August_Peak_Hours](https://user-images.githubusercontent.com/74233163/114801463-59dd5c80-9d61-11eb-9c5a-f61a81e71738.png)

**Summary:**


In conclusion, I think the program can be successful when deploys in Des Moines. From the results of this analysis, we can see that users are willing to subscribe to the program. Besides, the majority of the customer base is male, so we can focus our marketing effort on them.
I would recommend for future analysis, to make two visualizations that focus on the user's demographic information:

•	The Average Age of the customer base.

•	The population density of the Des Moines area to understand where we should install the bike station.

•	My other recommendation is to investigate winter months further to see if we still see to same hourly trends and volumes.
August is probably a very popular time to be outside in New York City but how would those numbers compare to December when commuting to and from work would be more challenging by bike.


Also, I will say, most of our users (~65%) happen to be male subscribers to CitiBike. The average duration of rides are about 5 minutes with females having a slightly longer trip duration per ride then males. Both males and females follow the same trend of most rides occurring at 8AM in the morning and 5PM to 6PM in the afternoon on weekdays. This appears to be related to morning and afternoon work commutes. During weekends, we see a different story with most rides occurring between 10AM to 6PM. Thursdays between 5PM to 6PM seem to be our most popular day for both males and females which is worth further investigation. Bike repair will be a necessity for the company, and I would recommend bike repairs to occur at 2AM to 4AM because we see our lowest volume of riders during that time window.


After reviewing our findings from the CitiBike data, I realized two additional visualizations would be helpful for future analysis. First, I noticed that the highest volume of rides was occurring on Thursdays by male subscribers. It would be interesting to see if a specific area within the city was seeing higher volume of rides on Thursdays and if it was related to an event. Perhaps a sporting or musical event was occurring every Thursday night in August that was driving up the volumes for that day. 

>>>>>>> 981c76751ac8ea0e6c44bda81232eec389581933

