# BikeSharing

## Overview
Kate and I want to use the data from Citibike in New York City to convince investors that a similar program in Des Moines would be a good idea. We used Tableau to generate visualizations of the data we feel is transferrable to Des Moines and helps our potential investors see our vision clearly.

### Purpose
The purpose of this analysis is to show our investors how a bike sharing program similar to the one in New York City can be transferable to Des Moines.

## Analysis

Intially the Citibike data was changed so that trip duration could be represented in minutes as opposed to seconds. This analysis can be found in the following jupyter notebook:

[NYC_CitiBike_Challenge.ipynb](https://github.com/ClaudAMC/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb)

The remaining analysis was done in Tableau where the visualizations to follow were created. The Tableau Public link can be found below:

[Link to Dashboard](https://public.tableau.com/app/profile/claudia.martin7041/viz/TableauChallenge_16602781550120/NYCCitibikeAnalysis?publish=yes)

## Results

The Images below tell the story of our analysis.

### Number of Rides by Gender

![Number of Rides by Gender.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/Number%20of%20Rides%20by%20Gender.PNG)

This image shows us the number of riders in the month of August broken down by genders. This lets us get a sense of how many riders we can expect during a high peak month. Creating a ratio of this based on population in NYC vs that of Des Moines can give us an idea of how many riders proportional to the population of Des Moines we could expect. The breakdown by gender also tells us that males are the highest users of this service; this can inform initial marketing strategies that target males in Des Moines to join the program initally, a following campaign could try and attract more female once the program is up and running.

### August Peak Hours

![August Peak Hours.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/August%20Peak%20Hours.PNG)

This image shows us the bike sharing programs peak hours during the month of August. From this we can see that generally the highest peaks are during the average workday commute times: 7am - 9am and 4pm - 7pm. This tells us that the greatest use users get is when trying to go to work or go home from work. Regardless of being in NYC or Des Moines this should remain the same where our target users will be those looking to use biking to commute.

### Checkout Times for Users

![Checkout Times for Users.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/Checkout%20Times%20for%20Users.PNG)

This image shows us the amount of time bikes were checked out for. We can see here that most users use the bike for 5 minutes; the number of bikes checked out dwindles past 5 minutes and reaches a low plateau at approximately 50 minutes. This low amount of time that bikes are checked out for could be accounted for by the previous information where most bikes are used around commuter times. It is possible that users with shorter commutes prefer biking to work as such the bike checkout times are short. This can also inform us about bike checkout times in Des Moines if we assume most users in 
Des Moines will also opt for biking to work with shorter commutes to work.

### Checkout Times by Gender

![Checkout Times by Gender.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/Checkout%20Times%20by%20Gender.PNG)

This image breaks down the previous visualization by gender. We see here again that the pattern follows across genders where peak check out times for males and female is around 5 minutes. Similar conclusions could be made as to this occuring in Des Moines.

### Trips by Weekday per Hour

![Trips by Weekday per Hour.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/Trips%20by%20Weekday%20per%20Hour.PNG)

This image highlights when the majority of user trips are occuring; the spread shows the time and weekday of these trips. From this we confirm what we assumed from the peak hours graph. The highest number of trips occur Mondays to Friday during commuter times. During the weekends there is a larger spread in the trips time where they occur quite uniformnly between 10am - 6pm; this is likely showing the times users are taking trips for leasure as opposed to the work commute. This information can again be applied to what would likely be happening in Des Moines where the majority of trips would likely be from commuters during the week and throughout the day during the weekends for leasure. 

### Trips by Gender (Weekday per Hour)

![Trips by Gender (Weekday per Hour).PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/Trips%20by%20Gender%20(Weekday%20per%20Hour).PNG)

This image show the visualization above again broken down by gender. We can see here that the pattern described above persists across both male and female users.

### User Trips by Gender by Weekday

![User Trips by Gender by Weekday.PNG](https://github.com/ClaudAMC/bikesharing/blob/main/Images/User%20Trips%20by%20Gender%20by%20Weekday.PNG)

This image shows the break down of trips started by customers compared to subscribers across the weekdays and split by gender. We can see fromt this graph that the majority of trips are taken by subscribers as opposed to customers. this could be due to the higher overall number of subscribers as compared to customers. we can see however, when we focus on male subscribers (the highest population of users) that the highest number of trips are on Thursdays. This could again be due to most of these users using the service for commuting back and forth to work. We can also see that there is a aslight trend where customers tend to majorily use the service on the weekends. Therefore, a potential marketing strategy would be to try and appeal to those no subscribers who would like to use the service for leasure during the weekends.

## Summary

Overall, we can see from the analysis that appealing to male commuters in Des Moines may be essential to get the program up and running. Past that stage investing in marketing towards female commuters and casual customers during weekend leasure hours could prove fruitful. Two additonal visualizations that could be created for further analysis are:

1. User Trips by Birthyear. Using these parameters we could get information on the age of users taking the most trips. This could further inform us on the age of the population that would be more likely to use this service in Des Moines.

2. Checkout times by birthyear. Using these parameters we could further find out which users are most active during commuter times. It is possible that unlike what was assumed above the people using the service are young students as opposed to workers. This could further inform us on the types of populations we want to attract in Des Moines.
