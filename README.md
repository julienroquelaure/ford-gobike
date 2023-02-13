# Ford GoBike System Data Exploration
## by Julien Roquelaure


## Dataset

The dataset consists of 183,412 bike rides.

We had information about:
- the ride: duration, start and end time.
- the stations: id, name, and coordinates of the start and end stations.
- the bike id.
- the user: Consumer/Subscriber, gender, birth year, and whether they bike share for all their trip.


## Summary of Findings

In this exploration, we first found that bike sharing trips tend to be quite short,
around 9 minutes on average, for a distance of about a mile.

On a side exploration, we saw a correlation between the logarithms of duration and distance,
it wasn't the theme of my anaysis, but we may further explore a power law relationship between duration and distance,
in the particular case of biking in urban settings for short distances/durations.

We found that in a typical day, people use the bikes mostly during commute hours: 
8 to 10 in the morning and 4 to 7 in the evening.
Day-wise, customers behavior reflect work patterns: bike sharing is more popular during the work week than during the weekend.
Interestingly, we found a drop in bike sharing during rainy days and holiday compared to a sunny work week.

About our customers, the age range skew towards younger people: an average of 34, and most are between 20 and 45 years old.
Customers are mostly male: there are abour 3 times male customers than female or other.
Most of our customers are subscribers rather than punctual customers.
And bike sharing is only part of their trip.

## Key Insights for Presentation

For the presentation, I focus on the patterns of bike sharing:
First, we look at how long is an average ride and saw it was roughly log-normal distributed, with an average of 9 minutes.
Then, we looked at a typical week and saw the work commute pattern vs the normally distributed weekend around midday.
We end with how was the month of February 2019 for Ford GoBike and saw, thanks to weather information,
that bike sharing is sensitive to weather, and the holiday is consistent with the drop in riding on week ends.



