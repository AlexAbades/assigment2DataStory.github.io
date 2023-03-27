---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div style="text-align: justify;">
We investigated and analysed the crimes reported in San Francisco from 2003 to 2017. Firstly, we created a monthly time series plot for each category of the 14 most important crimes over the years to investigate their trends. 
</div>
<div style="text-align: justify;">
Generally, Larceny/Theft and Assault are the categories with the highest number of crimes. Namely, the Larceny/Theft crimes have doubled compared to the beginning of the period. In contrary, the most significant decrease of less than half of the number of incidents compared to the beginning of the period is observed in the Vehicle Theft, Drug/Narcotic and Prostitution categories.
We highly believe that vehicle theft decreased drastically due to the fact that security technology improved during this time, making it more difficult for thieves to steal cars. For example, many vehicles manufactured after 2004 have built-in immobilizer systems, which prevent the engine from starting without a key that contains a microchip. This could have made it more difficult for thieves to steal newer cars, leading to a decrease in overall auto theft.
One possibility of the decrease on Drug/Narcotic and Prostitution crimes is that law enforcement agencies implemented targeted strategies to reduce this crimes since this time period. For instance, they may have increased police presence in high-risk areas, implemented sting operations to catch this crimes in the act, or provided education campaigns to raise awareness about how to prevent them.
</div>

<center>
<embed 
       type="text/html" 
       src="time_series_plot.html"
       width="900"
       height="1700"
       >
<center>

<div style="text-align: justify;">
Starting with the Assault category over the years, the number of reported crimes fluctuates significantly from month to month and from year to year. Furthermore, we can notice that lower numbers of incidents reported in the winter months from December to February. In August 2017, we see the highest number of ASSAULT crimes which is equal to 1101 incidents.
According to Robbery category, from 2003 to June 2005, the number of reported robberies remained relatively stable, with a few spikes in certain months. However, from the aforementioned period onwards, there was a clear upward trend, with the number of reported robberies steadily increasing until peeking in June 2006 (429 crimes). After that, there was a rapid decrease in the number of reported robberies for six months, followed by fluctuations until the end of the period with the smallest spike in March 2016 (215 crimes).
In terms of Vandalism, the overall trend shows a gradual increase in the number of reported incidents over time reaching a peak at 976 incidents in June 2017.



In the next plot, the number of reported burglaries reached a peak at 696 incidents in January 2005. However, from August 2006 onwards, there was a clear downward trend, with the number of reported burglaries steadily decreasing until hitting a low of 309 incidents in February 2011. Afterwards, there was a slight increase in incidents until November 2012, followed by a relatively stable period until the end.

In Stolen Property graph, the number of reported crimes remains stable at roughly 50 incidents until 30 April 2011. Then, there was a clear upward trend, with the number of reported incidents steadily increasing until October 2013 (119 incidents), followed by a steadily decrease until the end of the period (56 incidents).

According to vehicle theft category, we notice that number of crimes increased from the beginning of the period, reaching a high at 1714 incidents in November 2005, followed by a sharply decrease at 567 crimes in February 2006. Then, the number of reported incidents of this category remained relatively stable for the rest of the period.

The trend in Drug/Narcotic graph showed an increasing trend at the beginning of the period from April 2007 to March 2009 (high of 1242 crimes). Then, the number of Drug/Narcotic incidents began to decrease steadily until the end of the period reaching at only 301 incidents.
According to the Prostitution crimes, the trend follows similar pattern with Drug/Narcotic category having more fluctuations with bigger spikes at the beginning of the period. In July 2008, there were the high of 223 prostitution crimes, and this number steadily decreased over the next few years to reach a low of 53 in November 2011. However, after this year, the number of prostitution incidents remained stable around the 50 incidents until the end of the period.

The monthly analysis of Weapon Laws trend shows that the number of weapon laws incidents fluctuated over the years, but generally showed a slightly increasing trend from the middle of period. Specifically, the Weapon Laws crimes reached a low of 55 incidents in February 2011, followed by an increase reaching at 171 incidents at the end of the period.
Regarding to the Larceny/Theft incidents graph, the number of crimes remain stable around 2000 incidents from the beginning of the period to March 2012, followed by a steadily increase to 4457 incidents in October 2017.
</div>

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
       height="700"
       >

Almost every plot (except for the Tenderloin District) has two mysterious sudden changes. The first one is a sharp increase of the number of crimes at 12 am (about 25% increase), and the other one is a sudden decrease of the number of crimes at 1am (more or less 50% decrease). After doing some research online, nothing was found that could describe these behaviors, so we tried to come up with some plausible scenarios that could explain these trends. So these could either be a human error (rounding the reported time towards 12 am) or there were shift changes happening during those hours, or it could just be a regular thing that crime rises (or drops) during those hours.


