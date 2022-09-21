# Bike Sharing

# Overview 

This analysis uses the data of __“New York Citi Bike “__ trips during month of August to build a business proposal for a bike-sharing program in __Des Moines__ using the analytic tool __Tableau__ to create __data visualization__ that is easy to use and understand.

# Results

August is a beautiful time of the year to rent a bike, let’s have a look at analysis performed on that data and its visualizations.

1.	__Trips and Customers__

    Lets have a look at total trips and customers and their types using following visualization.
    
    ![no_of_trips](https://user-images.githubusercontent.com/107717882/191593813-e5e3a072-ddec-42c9-8559-e8fea8a34c97.png)

    As you can see total  trips are __2,344,224__.  There are two user types: __customers__ and __subscribers__ . There are 443,865 customers and 1,900,359                 subscribers. Subscribers are more and they are regular bikers which stabilizes  business. Also, looking at Gender Breakdown pie chart, there are ¼ of the females ,      2/3 of males and 1/8 of unknown genders, more males are using bike-sharing program. 

2.	__August Peak Hours__ 

    ![aug_peak_hours](https://user-images.githubusercontent.com/107717882/191593873-e872d574-78db-460e-bd8d-0872816df7bc.png)

    From above visualization we can see that evening 5pm and 6pm are peak hours of August as its summer time, as well as morning 8am. 

3.	__Checkout Times for Users__

    Let’s have a look at visualization the length of time that bikes are checked out for all users. 
    
    ![users_checkouts](https://user-images.githubusercontent.com/107717882/191593970-615fc9fe-8684-46dd-ac24-d35aa850b104.png)

    Maximum number of bikes are checked out for duration 5 to 7 minutes. As duration increases checkouts decreases. We can see that highest checkouts happened for 5 to     30 minutes trips. That means people uses bikes to go short distance. 

4.	__Checkout Times by Gender__

    Now, look at the following graph the length of time that bikes are checked out for each gender.

    ![checkouts_gender](https://user-images.githubusercontent.com/107717882/191594061-d7bbb9d1-a5b4-4fa4-9234-56064320e085.png)

    All genders,  checkout bikes for mostly 5-15 minutes of duration. As there are more male subscribers and customers than females so they have more checkouts. 

5.	__Trips by Weekday for Each Hour__

    Let’s visualize number of bike trips by weekday for each hour.
    
    ![weekday_trips](https://user-images.githubusercontent.com/107717882/191594106-fac0240a-8189-468a-aa39-3e45ddbd4af6.png)

    From the visualization we can see that __Thursday__ is the favorite day for biking! Peak hours for all weekdays are 5pm, 6pm and 8am. During weekend, most of the       trips are made between 11am to 5pm. 
    
6.	__Trips by Weekday for Each Hour (by Gender)__

    Now, add gender to weekday visualization. 

    ![wekday_trips_gender](https://user-images.githubusercontent.com/107717882/191594191-cddcfb34-b881-41f9-a8ff-9a71f5b6e843.png)


    From the visualization we can see that males are dominating bike sharing program. Morning 6am to 8am and evening 5pm to 7pm are their favorite bike time and of         course favorite day is Thursday. Also, females trips are almost same as males, peak hours are 8am, 5pm and 6pm and Thursday is favorite day. For unknown users,         weekends are favorites, Saturdays and Sundays from 10am to 6pm. 

7.	__User Trips by Gender By Weekday__

    Let’s have a look at heatmap that shows number of bike trips broken down by gender for each day of the week by each user type.
    
    ![weekday_usertype](https://user-images.githubusercontent.com/107717882/191594285-3d607128-8b33-4013-b7c5-9492bc8260b9.png)

    As we can see Subscribers are loyal customers, they have more trips all the days. Now look at customers, they have more trips on weekends. They are mostly like         visitors, tourists. 
 
# Summary

*   August is the summer month plus vacation period so its best to analyze data of that. Here we are building a business proposal for a bike sharing program in Des         Moines form the results of Nee York Citi Bike data. The results might be same or different but we present some visualizations to convivence investors. 

*   Peak hours are 5pm to 7pm and morning 8am during weekdays. More subscribers use bikes during weekdays than customers, for their commute, business or daily             routines.   More customers use bikes during weekends from 10am to 5pm. 

*   Most of the trips are of 5 to 30 minutes long, but there are longer trips but not significant. 

*   In addition, we should also consider top start locations and bottom start and end locations to identify which stations are busy and needs more bikes and how to         manage bike repairs and rotation. 

    ![top_bottom_stations](https://user-images.githubusercontent.com/107717882/191594610-a9ea455c-42b0-435f-95aa-b35f818ec9a6.png)

    The above dashboard shows top 20 start and end station names and bottom 10 start and end station names. 
  
*   Also, we can make visualization which station has max rides per weekday per hour. 

    ![stations_max_trips](https://user-images.githubusercontent.com/107717882/191594692-1bc793a8-84de-4a3a-a74e-b81e3e86d4c4.png)

    The above visualization shows stations that had max trips during weekdays per hour. This visualization helps us to decide busy stations and how to manage bikes         over   there. 
    
    Folowing are few results from Tableau story. You can check here https://public.tableau.com/app/profile/nishita.sapra/viz/NYCitiBike_Challange/NYCitiBikesStory
    



