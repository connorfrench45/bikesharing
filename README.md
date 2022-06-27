# Bike_Sharing
## Overview
Explore what Des Moines user habits might look like for Bike Sharing by examining bike sharing user habits in New York. The link for the Tableau story is [here](https://public.tableau.com/app/profile/connor.french/viz/Challenge_16562961192440/CitiBikeStory)
## Results
#### Customer Breakdown
[customer breakdown](Resources/Slide_1.PNG)

Before figuring out how the new Bike Sharing program should work, it's best to look at other successful programs and find out what makes them work. A great way of finding best practices is looking at the customer base: who they are and what they do. Here, we can see that in New York, most (>75%) of the rides come from subscribers, or people that pay a monthly rate to rent the bikes. Gender-wise, a big majority (~2/3) of the customers are male, about a quarter are female, and the remaining are unknown. With this information, lets breakdown the different user's habits:
#### Trip Duration by Gender
[slide 2](Resources/Slide_2.PNG)

Immediately, it is obvious that no matter the gender of the user, trips rarely last longer than an hour, and infrequently last longer than 30 minutes. For short trips, a huge number of users are Male, but for trips greater than 20 minutes, the gender breakdown evens out a lot more.

#### Trip Duration by Usertype
[slide 3](Resources/Slide_3.PNG)

When the rides are split by usertype, we can see that subscribers are the type that push the spike of short (< 10 minute) rides. For Customers (non-subscribers), there's a pretty even amount of rides lasting from 10-30 minutes. That split suggests different uses for different customer types. That follows an idea that customers are more likely to be those who live out of town, while subscribers are those who live in downtown. Out-of-towners likely would use the bikes to see the city, where residents would use the bikes for a purpose, like to and from work.

#### Trip Duration by Age
[slide 4](Resources/Slide_4.PNG)

This graph shows a slight, but significant slope upwards as the users get younger, meaning the younger you are, the longer your bike rides are on average. This makes sense. Biking is an active physical activity, and those that are younger are more in shape, or at least physically able/inclined to bike longer distances.

#### Time-of-Day Rental Breakdown by Gender
[slide 5](Resources/Slide_5.PNG)

This heatmap clearly shows a big jump in rentals during rushhour on the weekdays. It also shows a more generalized boost of use across the whole weekend during the days. This would make sense, given the conclusioons from the other graphs: the two big groups of customers are those who use the bikes for work and those who want to explore the city. Let's see if we can see that breakdown in the usertype heatmap:

#### Time-of-Day Rental Breakdown by Usertype
[slide 6](Resources/Slide_6.PNG)

Non-subscribers almost never use the bikes during the weekdays and Subscribers use them during the weekdays far more than the weekends. This is great news! The data follows a clear line and now its clear that there will be two different groups to target: Those that need the bikes for work, and those that want to sightsee on the weekends.

#### Weekday Breakdown of Usage
[slide 7](Resources/Slide_7.PNG)

Here we can see that although usertype usage behavior differs, the usage doesn't change much between gender (aside from the vast user amount difference). Also this heat map shows that the bikes need to be available each day of the week, even if the reason for renting is different on the weekends.
## Summary
The next steps would be marketing the bikes to a receptive audience: those that would use the bike to commute to work and those visiting the downtown. This is a great start, but also incomplete. Although we know the customer base and usage habits, we don't have a great idea of where to put the bikes to reach that audience. New, useful visualizations would be to compare the locations of the journeys for weekend and weekday riders and then use that information to find the best station locations. Des Moines is a smaller, less dense town. Bike trips will be longer, and there for that might exclude an older customer base entirely. Another visualization that would be useful is a population map of Des Moines and look at the average age of different neighborhoods.