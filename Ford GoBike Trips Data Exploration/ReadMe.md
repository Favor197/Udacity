## Ford GoBike Data Visualization Project

### Dataset
Ford GoBike is a bike sharing service system and the dataset used for this project includes information about bike trips covering San Francisco Bay area for the month of February 2019. The bike sharing service is for Subscribers, who pay subscription fee, or Customers, who rent bikes on-the-go. The dataset is made of 183,412 bike trips with 16 features and can be downloaded here. The features are:
- Duration (in seconds) 
- Start time
- End time
- Start station id
- Start station name
- Start station latitude
- Start station longitude
- End station id
- End station name
- End station latitude
- End station longitude
- Bike id
- User type  - (Customer or Subscriber)
- Member birth year
- Member gender - (Male, Female, Other)
- Bike share for all trip - (Yes or No)

Additional features I added for the sake of this analysis are:
- age - was gotten by subtracting birth year from 2019
- age_range - age column was grouped into '<20', '21-25', '26-30', '31-35', '36-40', '41-45', '46-50', '51-55', '56-60' and '61+
- start_dates - date trip commenced
- start_times - time trip commenced
- day_of_week - contains 0-6 which represents Monday-Sunday
- time_of_day - hour trip started using 24-hour time
- time - Night, Morning, Afternoon or Evening 

### Summary of Findings
From 183,412 rides made in February 2019, 89.2% was made by Subscribers while 10.8% was made by Customers. Notwithstanding, the average duration of trips by Customers was twice more than that of Subscribers. 
Most rides are done by Subscribers on weekdays between 7 – 9am and 4 – 6pm, with peak usage times at 8am and 5pm. During the week, there is no difference in the bike usage pattern of riders less than 20 years and more than 60 years. For other age groups, especially individuals between 26 and 35 years old, there is a significant decrease in their usage of Ford GoBike on weekends.

### Key Insights for Presentation
For the presentation, I would concentrate on showing the following:
- age group of users and the frequency at which they use Ford GoBike
- daily peak usage time of bikes
- percentage of riders who are either Subscribers or Customers and their average trip duration
- general usage pattern of Subscribers and Customers.



```python

```
