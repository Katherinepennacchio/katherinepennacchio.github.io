---
layout: post
title: 'CartoDB maps: Muslim population around the world'
---

As we are in the month of Ramadan, ninth month of the Islamic calendar and the moment when Muslims around the world fast during the day, I have decided to make a few maps about the growing Islam religion by country. 

<!-- more -->

The last study about global Muslim population was published in 2011 by the US-based [Pew Forum on Religion & Public Life](http://www.pewforum.org/2011/01/27/the-future-of-the-global-muslim-population/). Even though It’s not a new research, their [data](http://features.pewforum.org/FutureGlobalMuslimPopulation-WebPDF.pdf) is very detailed and it shows the projected number of Muslims by 2030. So, I chose to use it to make three maps with [CartoDB](http://cartodb.com/).


<iframe width='100%' height='400' frameborder='0' src='//kathy.cartodb.com/viz/47f91da0-0c23-11e4-aaff-0e10bcd91c2b/embed_map?title=false&description=false&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20*%2C%20to_char(_2010_est_muslim_pop%2C%20'9%2C999%2C999%2C999')%20AS%20_2010_proj_muslim_pop_mod%2C%20trunc(proj_change_2010_2030_where_pop_more_than_1_000%3A%3Anumeric%2C%202)%20AS%20proj_change_2010_2030%2C%20to_char(_2030_proj_muslim_pop%2C%20'9%2C999%2C999%2C999')%20AS%20_2030_proj_muslim_pop_mod%0AFROM%20muslim_population_by_country_up_to_2030%0A&zoom=2&center_lat=43.32517767999296&center_lon=16.5234375' allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

[Muslim population: 20 years into the future](http://kathy.cartodb.com/viz/47f91da0-0c23-11e4-aaff-0e10bcd91c2b/public_map?title=true&description=true&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20*,%20to_char(_2010_est_muslim_pop,%20%279,999,999,999%27)%20AS%20_2010_proj_muslim_pop_mod,%20trunc(proj_change_2010_2030_where_pop_more_than_1_000::numeric,%202)%20AS%20proj_change_2010_2030,%20to_char(_2030_proj_muslim_pop,%20%279,999,999,999%27)%20AS%20_2030_proj_muslim_pop_mod%0AFROM%20muslim_population_by_country_up_to_2030%0A&zoom=2&center_lat=28.304380682962783&center_lon=6.328125)


The world’s Muslim population is expected to increase by about 35% in 20 years, rising from 1.6 billion in 2010 to 2.2 billion by 2030, according to the projections by the Pew Research Center’s Forum on Religion & Public Life. The Muslim population is forecast to grow at about twice the rate of the non-Muslim population over the next two decades. 

<iframe width='100%' height='400' frameborder='0' src='//kathy.cartodb.com/viz/3cc7e294-0c0b-11e4-8c54-0e230854a1cb/embed_map?title=false&description=false&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20trunc(proj_change_1990_2030_where_pop_more_than_1_000%3A%3Anumeric%2C%202)%20AS%20proj_change_1990_2030%2C%20*%20FROM%20muslim_population_by_country_up_to_2030&zoom=2&center_lat=45.583289756006316&center_lon=4.5703125' allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


[Muslim population growth around the world between 1990-2030](http://kathy.cartodb.com/viz/3cc7e294-0c0b-11e4-8c54-0e230854a1cb/public_map?title=true&description=true&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20trunc(proj_change_1990_2030_where_pop_more_than_1_000::numeric,%202)%20AS%20proj_change_1990_2030,%20*%20FROM%20muslim_population_by_country_up_to_2030&zoom=2&center_lat=49.38237278700955&center_lon=16.875)

On the other hand,  from 1990 and 2030 muslim population increase at an average annual rate of 2,2%, compared with the projected rate of 1,5% for the period from 2010-2030. 


<iframe width='100%' height='400' frameborder='0' src='//kathy.cartodb.com/viz/660eb920-0c29-11e4-8def-0e230854a1cb/embed_map?title=false&description=false&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20*%2C%20to_char(_2030_proj_muslim_pop%2C%20'9%2C999%2C999%2C999')%0Aas%20_2030_proj_muslim_pop_mod%0AFROM%20muslim_population_by_country_up_to_2030&zoom=2&center_lat=36.5978891330702&center_lon=14.414062499999998' allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


[How big will be Muslim population by 2030?](https://kathy.cartodb.com/viz/660eb920-0c29-11e4-8def-0e230854a1cb/public_map?title=true&description=true&search=false&shareable=true&cartodb_logo=true&layer_selector=false&legends=true&scrollwheel=true&fullscreen=true&sublayer_options=1&sql=SELECT%20*%2C%20to_char(_2030_proj_muslim_pop%2C%20%279%2C999%2C999%2C999%27)%0Aas%20_2030_proj_muslim_pop_mod%0AFROM%20muslim_population_by_country_up_to_2030&zoom=2&center_lat=42.553080288955826&center_lon=3.8671874999999996)

According to the population projections data, if current trends continue, Muslims will make up 26.4% of the world’s total projected population of 8.3 billion in 2030. A majority of the world’s Muslims (more than 1 billion people) will continue to live in the Asia-Pacific region, while about 400 million will live in the Middle East and North Africa. Pakistan is expected to exceed Indonesia as the country with the largest Muslim population in the world. Also India, Bangladesh, Nigeria and Egypt will be on the top list of countries with a wide number of Muslims.


I used CartoDB  to make this map, you can check out the [Table](https://kathy.cartodb.com/tables/muslim_population_by_country_up_to_2030/public), clone it in your account and start creating your customized maps. 
