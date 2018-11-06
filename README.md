# How do Taxis move in NYC?
### Algorithmic Methods for Data Mining - Homework 2
##### Group #25 - Guilherme Vescovi Nicchio, Amirhossein Rajabi Shizari, Mario Raimo
##### 07/11/2018

Introduction
======
In this assignment we perform an analysis of Taxis in NYC. In particular, we are curious to answer to some specific research questions (RQs) that may help Taxi drivers in planning their movements throughout the city and the Taxi's users to have hints about the convenience of enjoying this service.

For this purpose we use the open data of Taxi's trips in NYC. In order to answer to the RQs we take into account the data related to Yellow cab for the year 2018.

Download sets of data
======
The data used are available on [New York City - Taxi and Limousine Comition](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) page. Once you are on the Web Site you can download the data from Janury to June of 2018, for this click on the link "Yellow" on the table. It is also necessary to download the Zone Lookup Table, which is a table with reference to the zone codes of the main data set, for downloading it click [here](http://www.nyc.gov/html/exit-page.html?url=https://s3.amazonaws.com/nyc-tlc/misc/taxi+_zone_lookup.csv). For plotting the maps it is necessary to download the json file in the repository, click [here](https://github.com/guilhermevescovi/ADM_HW2/blob/master/taxi_zones.json) and download it. 

With this data we have the necessary to run the analysis.

Repository files description
======
`Main_pipeline.ipynb`	
Main file with the code to perform the analisys

`drop_off_map.html`
Choropleth map of the drop-offs locations.

`pick_up_map.html`
Choropleth map of the pick-ups locations.

`taxi_zones.json`
Json file with NY zones mapping.
