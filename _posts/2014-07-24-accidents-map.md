---
layout: post
title: 'Map: Airplanes accidents in 2014 around the world'
---

![Imgur](http://i.imgur.com/GXeGbyE.png)

The  world is still in shock because of the [Malaysia Airlines flight MH17](http://www.newsweek.com/what-brought-down-flight-mh17-over-eastern-ukraine-259630) catastrophe and the truth of who are the responsables is unknown yet. 

<!-- more -->

Immediately, after reading about the plane crash on the news, I went to the Aviation Safety Network [website](http://aviation-safety.net/index.php) to get the data of the accidents or other occurrences, resulting in a total loss of the plane, registered so far this year.  To extract the data from the website, I used the google chrome extension [Table Capture](https://chrome.google.com/webstore/detail/table-capture/iebpjdmgckacbodjpijphcplhebcmeop?hl=en)  that allows me to create a google spreadsheet from the table in just seconds. 

I had to clean the table a little bit to keep only the columns I needed. I also add manually the latitude and longitude of the accidents locations, because I didn’t want to have problems to geolocalized the places in [CartoDB](http://cartodb.com/).

##Making the map

I imported the data from google drive to CartoDB.com (they have the option to connect with your gdrive tables). Once I had [my table](https://kathy.cartodb.com/tables/aviation_accidents_in_2014/public), I went to my map view and I choose the Torque option in my visualization wizard and voilà I got a animated map.

I used the “date” column to animate it. Remember, If you have a column with years or days you have to change the “data type” to date in your table first. 

![Imgur](http://i.imgur.com/57qGENW.png)


The final result was this one: 

<iframe width='100%' height='520' frameborder='0' src='http://team.cartodb.com/u/kathy/viz/29f41030-0e76-11e4-af72-0e230854a1cb/embed_map' allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

See this [tutorial](http://vimeo.com/79115503) to know more about how to make an animated map in CartoDB. 



