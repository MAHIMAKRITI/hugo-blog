---
title: "Cyclistic Case Study | Google Data Analytics capstone project"
date: 2022-09-20T14:18:50+05:30
weight: 10
draft: false
cover:
    image: images/cover1.png
    alt: 'This is about cyclistic'
    caption: 'Electronic vehicles are the future'
tags: ["data science", "python", "matplotlib"]
---
***
 ### Introduction:

Welcome to the Cyclistic bike-share analysis case study! This case study represents course 8 “Capstone project” of the Google Data Analytics Professional Certificate on Coursera

### The Scenario:

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. Cyclistic has flexible pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.


There are three questions that will guide the future marketing program:

- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- How can Cyclistic use digital media to influence casual riders to become members?
Moreno has assigned me the first question to answer: How do annual members and casual riders use Cyclistic bikes differently?

**The business task**: Analyse the Cyclistic data set for the year 2021 to understand how annual members and casual riders use Cyclistic bikes differently.

![alt text for screen readers](/images/cyclistic1.JPG "Daily rides by both categories")

We see that annual members use the cycles more during the weekdays, with the usage being highest on Friday, whereas the casual riders use it more frequently on weekends. Taking an educated guess, I believe our annual members are those who use the cycle for travelling to their work and our casual riders are those who use the bike for leisure purpose like biking around town, sightseeing etc.
 

![alt text for screen readers](/images/cyclistic3.JPG "Monthly rides by both categories")

From the visualization above its evident that people use the bikes more frequently from May to September. July has the highest number of casual riders using the bike services. This monthly pattern can also be explained by 2 predominant reasons:

- Chicago has a warm climate from May to September while it has freezing temperatures and snowfall from December - February. So naturally people choose to use the bikes during the summer months.
- Secondly, December and January are festive months and businesses and offices shutdown for a couple of weeks during the holiday season and since a lot of our annual members use their cycles to commute to work , its understandable that the bike usage dips during those months.

![alt text for screen readers](/images/cyclistic4.JPG "Daily rides by both categories")

Annual riders use the bikes for a much shorter duration than casual riders. Since most of our annual riders use the bikes to ride to work hence the ride_lengths are comparitively smaller. Also we see that since the maximum ride length is approximately 17 mins for annual riders so that translates to 10-15 miles on average.
<br>
<br>
![alt text for screen readers](/images/cyclistic5.JPG "Daily rides by both categories")
From the above histplot we observe 2 things:

- The member category has twin peaks - one at 8 am and the other at 5pm. This clearly proves that members use it for work purposes
- The casual members mainly use the bike between 4pm-6pm.  

Having analysed the data for 2021 these are my **recommendations** :

> 1. Saturday and Sunday should be prioritised when it comes to scheduling ads for the digital online campaign.
> 2. Clark St & Elm St and Wells St & Concord Ln and Kingsbury St & Kinzie St are the 3 stations which experience the maximum footfall by annual members, so we could increase the number of bikes available at these stations. Similarly we need to increase the number of bikes at Streeter Dr & Grand Ave and Millennium Park and Michigan Ave & Oak St in case of casual members. We could also use these stations for advertisements and banners which can act as a catalyst for conversion of casual to annual members.
> 3. May - September are the months when people use these bikes heavily hence marketing should be targeted in these months. Casual riders use the bike most frequently in July hence Cyclistic could run special discounts and offers during this month.
> 4. The digital and physical marketing of Cyclistic should be done more between 3-6 pm because most of our casual riders use the bike at that time of the day.
> 5. Out of the 3 categories , annual members do not use the docked bike at all. This could be a data issue as well but otherwise Cyclistic needs to conduct research as to why annual members do not prefer to use the docked bikes. If we are able to dtermine that then perhaps we can convert more casual docked bike riders to annual members.

To see code please go to my [github](https://github.com/MAHIMAKRITI/Cyclistic_EDA)
***

