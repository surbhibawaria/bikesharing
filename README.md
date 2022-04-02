# NYC Citi Bike Analysis

## Overview of the Statistical Analysis

An analysis of NYC Citi Bike data to figure out how the the bike-share business actually works in New York City in order to start a similar bike-share program in Des Moines.

### Purpose

The purpose of this analysis is to create multiple visualizations from NYC Citi Bike bikesharing data (from August 2019) for the final presentation and analysis to pitch to the potential investors, to convince them that a bike-sharing program in Des Moines is a solid business proposal.

## Result

Visualizations for the NYC Citibike analysis:

#### 1. Number of Rides, Gender and Customer Breakdown

<img width="644" alt="Number of Rides, Gender and Customer Breakdown" src="https://user-images.githubusercontent.com/95826875/161343689-2355a144-5906-4e76-92ca-3f39ddfde049.png">

_Description_ :  This visualization shows results for Number of Rides, Gender Breakdown, and Customer Types.

                 - The total number of trips recorded during the month of August were 2,344,224.
                 - The gender breakdown pie chart shows 225,521 'UNKNOWN' riders (red), 588,431 'FEMALE' riders (blue), and 1,530,272 'MALE' riders (orange), which shows that Male riders are 65%, Female riders are 25% and the rest 10% are unknown riders approximately.
                 - The number of short-term customers (blue) and annual subscribers (orange) to the Citi Bike service were 443,865 (~19%) and 1,900,359 (~81%) respectively.

#### 2. Top Starting Locations

<img width="1182" alt="Top Starting Locations" src="https://user-images.githubusercontent.com/95826875/161343782-08b5d202-4da9-4ca2-948f-21ce4d5de9a5.png">

_Description_ : This visualization shows the top locations for starting a bike journey among Citi Bike customers. The size of the circles and darkness of the color in the symbol map indicate the relative number of trips started at those locations. Apparently, most of the bike rides are starting from the lower Manhattan area.

#### 3. Top Ending Locations

<img width="1182" alt="Top Ending Locations" src="https://user-images.githubusercontent.com/95826875/161343897-1e6c3137-9a73-4b78-b4f7-7e54eacd73ac.png">

_Description_ : This visualization shows the top ending locations for ending a bike journey among Citi Bike customers. The symbol map for both the _Top Starting Locations_ and _Top Ending Locations_ virtually looks the same, which suggest that the top starting location is also the the top ending location for the bike riders making it the busiest location among others.

#### 4. August Peak Hours

<img width="1185" alt="August Peak Hours" src="https://user-images.githubusercontent.com/95826875/161343977-72019cc4-6b14-4d07-bb34-dcd0fd07d257.png">

_Description_ : This visualization shows the peak usage hours for the month of August to help get a better idea of how many bikes might be needed in Des Moines, as well as to figure out during which parts of the day most bikes will be needed. Based on the bar chart, it seems that the top riding hours during August in New York City are from 5:00 p.m to 7:00 p.m. And based on the visualization, bike maintenance could be performed from 2:00 a.m. to 5:00 a.m.



#### 5. Checkout Times for Users

<img width="943" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/95826875/161344086-4c87e77d-c9f4-4361-a15e-6b77c0c0ca95.png">

_Description_ : This visualization shows the length of time that bikes are checked out for all riders. The line graph show that the vast majority of Citi Bike trips are under an hour in length.

#### 6. Checkout Times by Gender

<img width="1059" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/95826875/161344138-d281e397-b364-458c-859b-ccca29f98bc8.png">

_Description_ : This visualization shows the length of time that bikes are checked out for each gender. The line graph with gender breakdown show that male riders take three times more rides than female riders. 

#### 7. Trips by Weekday per Hour

<img width="900" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/95826875/161344193-a6af02ff-65db-4ef9-929e-907dcb3ef152.png">

_Description_ : This visualization shows the number of bike trips by weekday for each hour of the day. The heatmap shows that the Citi Bike are mostly active during the morning from 7:00 a.m. to 9:00 a.m., during the evening from 4:00 p.m. to 7:00 p.m. on weekdays and all day long on weekends.

#### 8. Trips by Gender (Weekday per Hour)

<img width="1261" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/95826875/161344605-f169e456-ecf0-4835-b305-6bceb3009bf7.png">

_Description_ : This visualization shows the number of bike trips by gender for each hour of each day of the week. Although the total numbers for males riders are higher than the female and other riders, the heatmap shows almost the same pattern as in _Trips Weekday per Hour_ regardless of the gender.

#### 9. User Trips by Gender (by Weekday)

<img width="1182" alt="User Trips by Gender (by Weekday)" src="https://user-images.githubusercontent.com/95826875/161344729-0172defa-6f68-49ef-87d1-fa33d2b76b9d.png">

_Description_ : This visualization shows the number of bike trips broken down by gender for each day of the week by each Usertype. The heatmap shows how much of the Citi Bike userbase is predominated by Male Subscribers.


## Summary

The visulaizations shows that the Citi Bike bike sharing program in New York during the month of August 2019, is higly active and a source of regular income to the program. The user base is made up mostly of Male subscribers active making majority of rides in lower Manhattan area, contributing a good amount of income to the program. Most of the rides were taken in the peak morning and evening hours, making it an alternative commute. In conclusion, based upon these outcomes, bike sharing will be a great success in Des Moines.

Although these visualization gathered good amount of information for the analysis, but additional visualizations can be performed with the given dataset. For example:
- Finding the correlation between the weather data and rides for different months to determine trends across the year.
- Determining average trip duration with respect to gender and birth year to explore if there is any trend in male, female or unknown riders as they age.

#### Link to Dashboard: 

LINK GOES HERE  "https://public.tableau.com/app/profile/surbhi.bawaria/viz/NYCCitiBikeAnalysis_16488587294270/NYCCitiBikeAnalysisStory"
