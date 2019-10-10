# Earthquakes
Name
Earthquake Analysis
 
 
 
Aim
The main aim of this project is to analyze and visualize the data collected on the earthquakes that have hit the earth for the time period 1965-2016. 





Description of the data
The data has been collected from two different sources. One data source records the date and the latitude and longitude of the place that had been hit with the earthquake on that particular date and also the magnitude of the earthquake. This data source has been downloaded fron github. Another one of the datasets has been downloaded from bitbucket, it contains the latitude, longitude of the various cities as well as their corresponding country code. The last dataset used in this project contains the cvountry name along with the country code. 

The three datasets has been engineered in such a way(using pandas) that we can find out which countries and their corresponding cities were hit with the earthquakes according to their recorded latitude and longitude.



Data Sources

earthquake datasets: https://github.com/plotly/datasets
geocode and countries csv: https://bitbucket.org/richardpenman/reverse_geocode/src/default/





Description of the Project
Using the data collected, first a general idea of the amount odf damaged caused by this natural disaster over the years has been visualized in the form of a pie chart.

Then, a count of the number of earthquakes that has hit different countries has been recorded and a bar graph is plotted to get an idea of the places on the earth which are more susceptible to have been hit by the earthquakes and which are not.

Lastly,the states in the USA which had been hit by earthquakes over the period 1965-2016 has been mapped to the US map.




Installation
Apart from pandas, matplotlib and the common libraries, the following installations have been done:
geopandas  (conda install -c conda-forge geopandas)
descartes  (conda install -c conda-forge descartes)




References

https://github.com/agalea91/city_to_state_dictionary/blob/master/blog_post_html.txt

https://medium.com/@erikgreenj/mapping-us-states-with-geopandas-made-simple-d7b6e66fa20d

