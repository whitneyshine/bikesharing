# Bikesharing<br><br>

## Background<br>
Now that we've gotten a good idea of how to create our story, there is still work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, I will use Pandas to change the ["tripduration"](https://github.com/whitneyshine/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb) column from an integer to a datetime datatype. Then, using the converted datatype, I will create a set of visualizations to:

   * Show the length of time that bikes are checked out for all [riders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CheckoutTimesforUsers) and [genders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CheckoutTimesbyGender).<br>
   * Show the number of bike trips for all [riders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/TripsByWeekdayPerHour) and [genders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CreatetheTripsbyGenderWeekdayperHour) for each hour of each day of the week.<br>
   * Show the number of [bike trips](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/UserTripsbyGenderbyWeekday) for each type of user and gender for each day of the week.<br>
 
 Finally, I will add these new visualizations to the two I created in this module for the [final presentation](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/NYCChallengeStory?publish=yes) and analysis to pitch to investors.<br><br>
 
## What I Have Created<br>
This assignment consists of two technical analysis deliverables and a written report to present the results. I have submitted the following:

  * **Deliverable 1: Change Trip Duration to a Datetime Format**<br>
      *  Using Python and Pandas functions, I have converted the ["tripduration"](https://github.com/whitneyshine/bikesharing/blob/main/NYC_Citibike_Challenge.ipynb) column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After I converted the "tripduration" column to a datetime dataytpe, I have exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.<br>
  * **Deliverable 2: Create Visualizations for the Trip Analysis**<br>
      *  Using Tableau, create visualizations that show:<br>
              * How long bikes are checked out for all [riders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CheckoutTimesforUsers) and [genders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CheckoutTimesbyGender).<br>
              * How many trips are taken by the hour for each day of the week, for all [riders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/TripsByWeekdayPerHour) and [genders](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/CreatetheTripsbyGenderWeekdayperHour).<br>
              * A [breakdown](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/UserTripsbyGenderbyWeekday) of what days of the week a user might be more likely to check out a bike, by type of user and gender.<br>
  * **Deliverable 3: Create a Story and Report for the Final Presentation**<br>
      * For this part of the Challenge, I have created a story in [Tableau](https://public.tableau.com/profile/whitney.shine#!/vizhome/NYCCitibikeChallenge_16218973329460/NYCChallengeStory?publish=yes) as well as a report that describes the key outcomes of the NYC Citibike analysis I did in the [module](https://public.tableau.com/profile/whitney.shine#!/vizhome/Module14-NYCCitibike/NYCStory) and in Deliverable 2. <br><br>

## Results<br><br>

### Checkout Times For Users<br>
In this visualization, I graphed the length of time that bikes are checked out for all riders.<br>
![checkout_times_for_users](checkout_times_for_users.png)<br><br>

### Checkout Times By Gender<br>
In this visualization, I graphed the length of time that bikes are checked out for each gender.<br>
![checkout_times_by_gender](checkout_times_by_gender.png)<br><br>

### Trips By Weekday For Each Hour<br>
In this visualization, I graphed the number of bike trips by weekday for each hour of the day as a heatmap.<br>
![trips_by_weekday_per_hour](trips_by_weekday_per_hour.png)<br><br>

### Trips By Gender (Weekday Per Hour)<br>
In this visualization, I graphed the number of bike trips by gender for each hour of each day of the week as a heatmap.<br>
![trips_by_gender_weekday_per_hour](trips_by_gender_weekday_per_hour.png)<br><br>

### User Trips By Gender By Weekday<br>
In this visualization, I graphed the number of bike trips by gender for each hour for each day of the week as a heatmap.<br>
![user_trips_by_gender_by_weekday](user_trips_by_gender_by_weekday.png)<br><br>



### 

## Summary

