# Bikesharing Project


## Project Overview

New York City is a city full of historic landmarks, like Central Park, the Statue of Liberty and the Empire State Building. 
It's even a more magical experience if you use a bike sharing program, like Citi Bike, to travel around everywhere.
You can really get to know the city and interact with the peple who live there and who are using bikes for their commutes.

What if you could start a similar bike share business in your home town: Des Moines, Iowa?
In order to know if this is a feasible project, it's due to understand the mechanics of a bike sharing service.
Even though it'll be quite different, we'll start to analyze data from New York City, given that it is accessible from the following link:
https://s3.amazonaws.com/tripdata/index.html


## Results

To show the potential market and use of bike sharing in Des Moines, we've analyzed data from Citi Bike, a bike sharing compay operaing in New York City, which provides actual information of its widespread use. Tha analysis made is performed on the data of august, 2019, since it's expected to have a wider use in the summer, due to the number of visitors as well as the accomodating weather on that particular month of the year.

There were 2,344,224 trips in august, 2019. Over 75% of them were made by subscribers, while the rest were made by occasional customers.
This is an important point to notice: while it was assumed that August would be a great month to analyze, due to the assumption that tourists would use the service, it seems that it is used more as a means of transport than a city-landscaping type of tourism.
![NYC Citi Bike - Customers](https://user-images.githubusercontent.com/113773420/224546005-032d1d06-f9cd-432f-a7ff-6f7b73582a45.png)

The location of bike stations is crucial for this program's success. Citi Bike provides information of its bike stations and also its frequency of use. In the next map, it can be viewed where are located the top starting bike stations. Manhattan has the concentrates the most bike stations and, obviously, the most frequently visited.
![NYC Citi Bike - Top Starting Locations](https://user-images.githubusercontent.com/113773420/224557579-c253063f-e898-4c53-8b42-9d02df6c32b2.png)

As it is expexted, most of the trips' durations are less than an hour long; the most frequent time duration is 5 minutes, with 146,752 trips taken during August, 2019.

![NYC Citi Bike - Checkout Times for Users](https://user-images.githubusercontent.com/113773420/224544386-f1062dd2-b496-4c64-aff2-5e932e5d3a21.png)

Information provided by Citi Bike shows the gender of the rider. While there are some cases that is declared "unknown", it can be affirmed that most of the users are males. However, the trips' duration carries the same trend, for shortes trips being the most frequent.
![NYC Citi Bike - Checkout Times by Gender](https://user-images.githubusercontent.com/113773420/224546316-7bbaaa7e-097d-47c6-925d-c77f42799345.png)

As for the time of the day where there is the most use, the highest rates of use are found on workdays, between 6-10 a.m. and 5-7p.m.
On weekends, bikes are mostly used during the day: from 10 a.m. until 6 p.m.
![NYC Citi Bike Trips by Weekday per Hour](https://user-images.githubusercontent.com/113773420/224555966-2cc55313-3fe0-46fe-952b-33286bbc0054.png)

Data mining into the use by gender, even though trips taken by women are fewer than men, pattern of use is still roughly the same, just as shown in the analysis of trip duration.
![NYC Citi Bike - Trips by Gender](https://user-images.githubusercontent.com/113773420/224556165-e736b4ec-af18-489a-b8a9-4ca0c4cb0cc8.png)

To further proofing of the preferred use od bike sharing in New York City, the analysis of use by day of the week between subscribers and casual customers show that the highest concentration of rides are on weekdays taken by male (and to a lesser degree, to women too) subscribers.

![NYC Citi Bike - User Trips by Gender](https://user-images.githubusercontent.com/113773420/224556358-48b8930c-37e4-49a3-9bdc-be611bfa9241.png)

Previous graphs and data can be analyzed further in the following link:
https://public.tableau.com/shared/88GKDSNRN?:display_count=n&:origin=viz_share_link


## Summary

Even though bike sharing might seem as a way of means of transport for sightseers and/or tourists, it's more commonly used by ususal customers -subscribers- who use the service for their daily commutes all around the city.

When comparing Des Moines to New York City, the number of visitors are not anywhere close. Yet, people who are likely to prefer using a bike to their usual commutes are.

Considering this as a starting point, it would also be useful to analyze:
* The average distance traveled by trip (measuring the distance between the starting and ending bike stations).
* The age of subscribers, considering that students may use more this bike service rather than middle-aged working people.

In the end, this is the starting point of the project.
Operating costs adn maintenance mechanics are yet to be analyzed.
In the meantime, there is enough evidence to continue on it.
