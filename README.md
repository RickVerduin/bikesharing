# Citi Bike Analysis

## Overview
This project uses Tableau to visualize data of August 2019 City Bike trips in New York City in order to create a high-level summary that can be presented to potential investors in other cities.

## Results
[Link to dashboard](https://public.tableau.com/app/profile/rick.verduin/viz/CityBike_16460773138230/CityBikeStory)

#### Duration of trips
The line chart shows the number of trips on the Y-axis, and the duration of trips on the x-axis. It is obvious that Citi Bikes are most frequently rented for short periods of time, with the peak of the graph around 5 minutes. 

![image](https://user-images.githubusercontent.com/93882635/156627078-4f2f9cd8-66b7-417e-999c-5c0ae63b3255.png)

#### Duration of trips by gender
This line chart is similar to the previous one, but adds insight about how usage differs by gender. As we can see, although the amount of women that use Citi Bike is lower than the amount of men, both lines show a similar distribution, indicating that there is not much of a difference in the duration of trips between men and women. The curve is flatter among the riders that we don't know the gender of, but this line too shows a similar pattern.

![image](https://user-images.githubusercontent.com/93882635/156627644-695efe9c-8ecd-43aa-994d-7d86e73d46b5.png)

#### Usage heatmap
This heatmap shows Citi Bike usage per hour and per day of the week. The darker the color, the more bikes are used at that particular time. The pattern shows heavy usage on weekdays between 7am and 10am, as well as between 5pm and 7pm. On weekends bikes are used throughout the day, but mostly in the late morning and afternoon hours.

![image](https://user-images.githubusercontent.com/93882635/156628293-f6e22722-0cb1-40ae-91ae-fa52b0c72909.png)

#### Usage heatmap by gender
The following two heatmaps compare usage between men and women. Just like the duration of the trips, the hours that bikes are being used are very similar for both genders. Fewer women use the bikes than men, resulting in lighter colors on the heatmap for women, but the distribution of lighter and darker colors, is practically identical to that of the heatmap for men.

![image](https://user-images.githubusercontent.com/93882635/156629353-932aa7e4-7e6b-4210-b9f5-5253d1da274f.png)

#### Usage by user type
This next heatmap compares usage between the two types of City Bike users. As indicated by the darker colors, bikes are far more likely to be rented by users that have a Citi Bike subscription, than by users that use the service without a subscription.

![image](https://user-images.githubusercontent.com/93882635/156629616-702a1515-71c1-4dce-8b0a-f115d4b29660.png)

#### Gender distribution
As we saw before, men make up the larger part of the total users of Citi Bikes. This pie chart confirms this: 65% of users are male, 25% are female. Gender data is missing for the remaining 10% of users.

![image](https://user-images.githubusercontent.com/93882635/156629828-f52102c0-1ded-455e-b525-a931f12dd6d2.png)

#### Daily usage per hour
This bar chart looks at usage of bikes per hour. It is important to maintain the bikes, and this is best done during hours where usage of bikes is low. As we can see in this chart, early mornings before 6am would be best to perform maintenance!

![image](https://user-images.githubusercontent.com/93882635/156630642-db6d85bc-4295-454a-8ef5-bf8882b9030c.png)



## Summary
- Citi Bike is most polular for short trips, with the largest number of rides being 5 to 6 minutes long.
- Bikes are rented most on weekdays during morning and evening commutes and on weekends.
- Men are more likely to use Citi Bike than women.
- The majority of Citi Bike users have a subscription.

### Further Analysis
Our data suggests that many Citi Bikes are used to commute to and from work. In order to see how popular Citi Bike is among tourists, a distinction needs to be made between usage during commute hours and usage outside of those hours, such as:
- A comparison between the ratio of subscribers versus non-subscribers during peak hours and non peak hours. How many users that use the service to commute to  and from work have a subscription, and how does that compare to users that use the service outside of commute hours on weekdays and on weekends?
- A comparison between the most popular stops during peak hours and non peak hours to show when users ride the bikes to and from residential and office locations versus popular tourist attractions.
