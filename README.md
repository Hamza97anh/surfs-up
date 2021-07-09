# surfs-up
### Software
- Flask
- Jupyter notebook
- Python
- VS code 

## Overview
The Purpose of this project is to offer a customer, in the process of openning up a surf shop, some weather data to better determine weather his target location is suitable for his business. The project offers temp data pulled specifically from the month of June and Decemeber, the most popular time for people to travel on a holiday, using the .describe() method via python. For this project we used data pulled from an SQLite file which we then stored in a list then converted to a dataframe to be analyised. 

## Results
- Weather during the month of June is more consistant and is higher by two degrees then it is during december. We can deduce this based on the std and the fact that between the max and min is only a 20 degree gap in temperature. 

![Fig1.png](https://github.com/Hamza97anh/surfs-up/blob/5cf44ecf0289f3ba54663eb6c878370a3afe5a20/Resources/june%20temp%20chart.PNG)
- Weather during the month of December is more unpredictable with a broader range in temp. The std is 3.74 which compared to 3.25 for june is reflective of that fact. The max temp during december is very similar to june at 83 vs 85, but the minumum is much lower at 56.  


![Fig2.png](https://github.com/Hamza97anh/surfs-up/blob/5cf44ecf0289f3ba54663eb6c878370a3afe5a20/Resources/december%20temp%20chart.PNG)


## Summary

June appears more favorable for the surf shop to be open based on our two quaries. However, it is more comlicated then just looking at temperatures. We recommend that there be at least two more additional quaries to include in our analysis which look at things such as wind speeds to help see what kind of waves surfers can expect during the two months, and also how much it rains. More data would need to be gathered to do this. However, with our current data, based on the temps, June is better then Decemeber for surfing, but both are favortable for opening up a surfshop in that location. 
