---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

We investigated and analysed the crimes reported in San Francisco from 2003 to 2017. Firstly, we created a monthly time series plot for each category of the 14 most important crimes over the years to investigate their trends. 

Generally, Larceny/Theft and Assault are the categories with the highest number of crimes. Namely, the Larceny/Theft crimes have doubled compared to the beginning of the period. In contrary, the most significant decrease of less than half of the number of incidents compared to the beginning of the period is observed in the Vehicle Theft, Drug/Narcotic and Prostitution categories.
We highly believe that vehicle theft decreased drastically due to the fact that security technology improved during this time, making it more difficult for thieves to steal cars. For example, many vehicles manufactured after 2004 have built-in immobilizer systems, which prevent the engine from starting without a key that contains a microchip. This could have made it more difficult for thieves to steal newer cars, leading to a decrease in overall auto theft.


<embed 
       type="text/html" 
       src="time_series_plot.html"
       width="1100"
       height="1200"
       >


Generally, Larceny/Theft and Assault are the categories with the highest number of crimes. Namely, the Larceny/Theft crimes have doubled compared to the beginning of the period. In contrary, the most significant decrease of less than half of the number of incidents compared to the beginning of the period is observed in the Vehicle Theft, Drug/Narcotic and Prostitution categories.

<embed 
      type="text/html" 
      src="map_folium_SF.html"
      width="1100"
      height="600"
      >


Below we are presented with the hourly bar plot of crimes committed in the different districts of San Francisco. Starting with the Bayview district, the hourly plot shows that most crimes occur during the late afternoon and early evening hours, with the peak occurring between 4 pm and 7 pm. The number of reported incidents decreases during the early morning hours and reaches its lowest point between 3 am and 5 am.
All the other districts follow a pretty similar trend, with slightly different peaks (e.g. some might have their peaks at 5 pm while others at 6 pm), and slightly shifted lows. However, in some cases the pattern might vary to some degree. For example, in the Northern and Southern districts, although the plots have a similar behavior to the one described above, the number of reported incidents remains relatively high during the late evening hours and early morning hours.


<embed 
       type="text/html" 
       src="bar_plot.html"
       width="1100"
       height="600"
       >

Almost every plot (except for the Tenderloin District) has two mysterious sudden changes. The first one is a sharp increase of the number of crimes at 12 am (about 25% increase), and the other one is a sudden decrease of the number of crimes at 1am (more or less 50% decrease). After doing some research online, nothing was found that could describe these behaviors, so we tried to come up with some plausible scenarios that could explain these trends. So these could either be a human error (rounding the reported time towards 12 am) or there were shift changes happening during those hours, or it could just be a regular thing that crime rises (or drops) during those hours.


