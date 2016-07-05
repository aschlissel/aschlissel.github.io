---
layout: post
title: MTA Project
---

# There's Nothing Like Summer in the City!
  
I just finished my first week at Metis, a twelve week data science bootcamp in New York City.  
  
![Alt Text](http://67.media.tumblr.com/761d8443334825b118313eeaded99bb2/tumblr_nwr9axu1je1qddjxro10_r1_250.gif)

My cohort and I just completed our first project based off of subway turnstile data.  
  
## The Premise  
An organization promoting the increased participation of women in tech reached out to us about their summer gala. Using MTA turnstile data, they wanted us to fill the gala space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach. They had planned to place canvassers near subway stations and collect emails of people interested in the event.  
  
## My Group's Approach  
We thought that the best way to increase awareness and attendance was to place the canvassers near the busiest subway stations at peak times and stations near large tech companies. People who work at tech companies will be the most useful demographic to target since people who work in tech are interested in tech and understand the current gender imbalance in the industry. (In other words, people who are most likely to fill the gala room.)  

## Busiest Subways at Peak Times  
Using subway turnstile data available to the public, my group and I calculated the busiest subway times and their peak times. Below are the top 10 busiest subways according to our data:  
![Alt Text](https://files.slack.com/files-pri/T1AJ01YV9-F1N64F1AM/pasted_image_at_2016_07_01_11_10_am.png)  
  
After that, we calculated the peak hours when people go on trains.

![Alt Text](https://files.slack.com/files-tmb/T1AJ01YV9-F1N66UDKN-b8150b28cd/pasted_image_at_2016_07_01_12_21_pm_1024.png)

## Stations Near Tech Offices  
We assumed that the people who would be most interested in the cause were people who worked in tech. Thus, we obtained the latitude and longitude coordinates of some of the largest tech firms in NYC and calculated the closest subway stations using the Haversine forumula. We thought it would be most efficient for the canvassers to place themselves at the top 20 subway stations that correspond to a nearby large tech firm (0.5 km apart or less) at all times during the weekdays.  

Below is an image of some of the largest tech firms mapped: 
![Alt Text](https://files.slack.com/files-pri/T1AJ01YV9-F1N6G4HS4/firms_final.png)

## Our Recommendation  
Our Group recommended that the canvassers should place themselves at the top 10 busiest subway stations at peak hours (8am-12pm, 4pm-8pm) on weekdays and at the top 20 busiest subway stations that correspond to large tech firms at all times on weekdays.  

## Happy Fourth of July!  
![Alt Text](http://67.media.tumblr.com/ed81014194e47986519b049cb429141d/tumblr_o2m5cfi2nT1ssx5o9o6_400.gif)


