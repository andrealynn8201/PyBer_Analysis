# PyBer Analysis

## Overview

To create a multiple line graph to visualize the ride-sharing-data by type (Urban, Suburban, Rural), so the shareholders can see how each city type compares with each other and their average fares per week.

## Results

I needed to combine the ride and city data into one data set.  Then I needed to retrieve:

* The total number of rides for each city type
* The total number of drivers for each city type
* The sum of the fares for each city type
* The average fare per ride for each city type

I then needed to create a PyBer summary DataFrame and format it.  This is a screen shot of the end result:

<img width="1440" alt="Screen Shot 2021-12-27 at 6 05 45 PM" src="https://user-images.githubusercontent.com/93801125/147514773-3bf981e1-28fa-4469-81ea-b80c7b07069f.png">

This data allows us to see that as a whole, by type, that Urban areas give a significant more total of rides than the other types.  This in turn means more fares.  Even though the average per ride and driver were less, the more rides that were provided, the more revenue for PyBer.

I then created a multiple line graph to show more easily how each type compare with each other. It was broken down into weeks, from Jan 2019 to Apr 2019. Here is that graph:

![pyber_challenge](https://user-images.githubusercontent.com/93801125/147514622-e39969d4-d348-45e8-8dbb-de3f80b26663.png)

Since this is a summary of all the data combined for each type of city, and not by each city alone, this demonstrates the averages as a whole. We can see that the data gave us a clear indication that Urban environments gave a higher total fare per week than Suburban or Rural areas.  Even though the first  summary DataFrame showed the higher fares were given in Rural areas, they don’t do nearly as well as the lower, but more frequent fares of Urban ares.


## Summary

I would recommend charging more for Urban areas, slightly less for Suburban areas and the least per mile for Rural areas.  That way, more people in Suburban and Rural areas are more apt to ride-share for the longer distances they need to go, and allow the drivers in Urban areas take more money in per ride, then they are currently getting.  

I would also continue to monitor how each week does in general, to see when more or less drivers are needed at peak times of the year, such as the end of February.  All areas need more drivers at that time. Urban areas have peaks times more often, and can use the added drivers to compensate for those times

Lastly, I would suggest make slight charge increases during peak times and decreases during lull times to maximize revenue when people are using PyBer services more, and encourage them to use our services more when we aren’t giving as many rides.
