# bikesharing
Citi Bike program in New York

## Resources

- Tableau Public 2022.1
- Jupyter Notebook 6.4.8

## Overview

We want to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solify the proposal I have created a bike trip analysis using NYC Citibike Data. 

- In Deliverable 1 I used Jupyter Notebook to change Trip Duration to the Datetime Format.
- In Deliverable 2 I created Visualisations for the Trip Analysis.
- In Deliverable 3 I will use visuals from the module and the challenge to create a story in Tableau.

## Results

### Deliverable 1

Converted tripduration to datetime and created a new CSV file without the index:

![image](https://user-images.githubusercontent.com/96445453/162527915-982bdfe7-9130-4836-9434-0e986404eb96.png)

### Deliverable 2

The first thing we analysed shows checkout times for users. The data indicates users check out citibikes for about 10-15 minutes at peak and at maximum about an hour. See below:

![image](https://user-images.githubusercontent.com/96445453/162528229-c1044305-c3a6-4025-bc87-70ce25eca84b.png)

The next thing we analyzed is checkout times by gender. This shows males tend to check out citi bikes more frequently. See below:

![image](https://user-images.githubusercontent.com/96445453/162653346-d7133023-2c11-44ad-b4f9-53eeb21f9297.png)

Next we analyzed trips by weekday per hour. This is a heatmap showing bikes are frequently checked out around 7AM-8AM and 5PM-6PM during the weekdays. See below:

![image](https://user-images.githubusercontent.com/96445453/162653473-3c8cd0e8-f499-4318-95b3-74423ab75b73.png)

Next we analyzed trips by gender (weekday per hour). A heatmap showing males checkout citibikes more frequently then females but also shows they check them out at the same time. See below:

![image](https://user-images.githubusercontent.com/96445453/162653679-67e8b954-5ed9-4a6a-84e9-d3ac548846bc.png)

Next we analyzed user trips by gender by weekday. This shows male subscribers are the majority and thursday has the highest trips. See below:

![image](https://user-images.githubusercontent.com/96445453/162653849-5f47bd17-a760-4885-b45f-c31430ead95e.png)

We also found out where most of the citibikes are checked out below:

![image](https://user-images.githubusercontent.com/96445453/162654017-c8e85318-4ee5-4349-87f0-3a6f14d669e9.png)

We found the average trip duration based on the birth year of the rider. This shows later generations tend to take out bikes more frequently than older as shown below:

![image](https://user-images.githubusercontent.com/96445453/162654350-784a8c17-17a8-42d2-907d-b8baec19c38d.png)

## Summary

After reviewing all the data we can surmize that the Citibike would be a good idea to impliment in Des Moines. Bikes are typically checked out around 7AM-8AM or 5PM-6PM which we can assume is due to working hour commuting. On the weekends the checkout time of the bikes is stretched throughout the day. Males tend to checkout bikes more frequently then females as shown in this pie chart:

![image](https://user-images.githubusercontent.com/96445453/162654695-3bfde59e-07da-4c3c-b422-dcddca187d81.png)

Repairs should be done from 2AM-5AM if able and the bikes can be tracked by usage amount to see when they may need repairs as shown below:

![image](https://user-images.githubusercontent.com/96445453/162654856-95c0256d-3b60-44d1-824c-d439b619d91a.png)

The Tableau Story for the challenge and modules can be seen here:

https://public.tableau.com/app/profile/reilly.thompson/viz/CitibikeStory_16494500567710/Story1
https://public.tableau.com/app/profile/reilly.thompson/viz/bikesharing_module_16492991476870/Story1
