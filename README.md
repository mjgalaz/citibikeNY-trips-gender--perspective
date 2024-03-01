# Citibike NY - Gender Perspective Analysis
This analysis delves into understanding gender-based disparities in Citibike usage patterns, routes, station preferences, and trip durations. The insights are derived from an extensive examination of a publicly available dataset hosted on Google BigQuery. Data processing, cleaning, and organization were meticulously executed using SQL within BigQuery's robust environment. Subsequently, visualization of the findings was facilitated using LookerStudio.

### Dataset Overview
The dataset, publicly accessible and hosted on Google BigQuery, offers extensive insights into Citibike bicycle trips spanning from July 2013 to May 2018. It comprises crucial trip details, such as trip duration, start and end stations, user gender, subscription type, trip timestamps, and others.

### Analysis Highlights
#### 1. Overall Trends
   - Trips exhibit a seasonal pattern, with a decrease in winter, likely due to adverse weather conditions.
   - Male users constitute the majority of trips (67.1%), followed by females (21.4%), with 11.5% of users having unknown gender.
   - The public bike-sharing system analyzed has experienced sustained growth in trip volumes over the years, potentially supported by the implementation of the "Sustainable Streets" strategic plan, initiated in 2008 and ongoing to date. This plan has enhanced bicycle infrastructure across the city, fostering the popularity and accessibility of biking as a mode of transportation.
  
#### 2. Insights by Gender
- Common Trends:
  - Both male and female users exhibit consistent trip patterns on weekdays.
  - The majority of users, both male and female, mainly hold annual subscriptions.
  - Male and female users show consistent trip patterns on weekdays
  - Peak travel hours coincide with both morning and evening rush hours on weekdays.
  - The distribution of the age curve indicates a skew towards younger adults, with a higher concentration of trips made by younger users.

- Women:
  - Most utilized departure and arrival station: Flatiron district and Chelsea, suggesting that women primarily engage in activities during business hours in this area.
    
- Men:
  - Predominant use of Pershing Square North station, often as a hub for connecting to Grand Central Station or spending business hours in the surrounding area (insufficient data to understand predominant use).
    
- Unknown Gender:
  - Mayor use of Central Park and 6th Ave station.
  - Number of travels peaks on weekends.
  -Predominantly opt for daily customer passes and tend to use the system more frequently between 2 and 5 pm on weekends, indicating tourist behavior.

 ### Recommendations
  - As the usage decreases on weekends among subscribed groups, there are available bicycles to further encourage tourist usage of this mode of transportation.
  - There is potential for growth in female users. One growth opportunity is to incentivize the use of the system. It is recommended to interview current female users to inquire about aspects for improvement that may have been overlooked due to cultural gender bias, and to advance proposals to make this system more inclusive.
  - Finally, it is suggested to incorporate more gender identity options (in addition to female and male) to better understand the user and embrace diversity.
    
 ### Dashboard
  ![](https://raw.githubusercontent.com/mjgalaz/citibikeNY-trips-gender--perspective/main/dashboard.png)
  
 For a more in-depth view of the analysis results, click [here](https://lookerstudio.google.com/reporting/09c6e4ad-9c1b-455a-92fc-b7c22eeef7c1) to access the interactive dashboard.


