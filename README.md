# Tableau
## Data
New York City CitiBike Data from January to August 2020 was aggregated and analyzed.The selected timeframe was chosen to visualize changes in the CitiBike demographics and utilization resulting from Covid-19.

https://www.citibikenyc.com/system-data

## Data Cleansing
Outliars were removed on birth year (those equating to age over 100 years old and those with counts that did not fit the distribution).
[![Image from Gyazo](https://i.gyazo.com/d06f093f0cc9196f16422ea391a6a2fc.png)](https://gyazo.com/d06f093f0cc9196f16422ea391a6a2fc)
Outliars were removed on trip duration (trips longer than 2 hours).
Bad data was removed on station latitude and longitude (where one station had more than one lat/long combination with only one or few occurances.

## Analysis:

### Station Traffic Patterns over Time
Traffic Patterns were analyzed by month, weekday and hour.
An interactive dashboard was created that allows the used to click on any station on the map.  When a station is clicked all the other charts' data is filtered to display only results relevant to the selected station.
[![Image from Gyazo](https://i.gyazo.com/654bbfcb332b4a6b8cea69175a048a79.gif)](https://gyazo.com/654bbfcb332b4a6b8cea69175a048a79)
[![Image from Gyazo](https://i.gyazo.com/932abfce815dedb697a13877b8e41e83.gif)](https://gyazo.com/932abfce815dedb697a13877b8e41e83)


### Station Demographic Patterns over Time
A second interactive dashboard was created to visualize how the demographics of users vary over time.  Demographics assessed include age, gender, user type (customer or subscriber).  Most fields are interactive and update other charts with filters or highlights when the mouse hovers over something.
[![Image from Gyazo](https://i.gyazo.com/d295bf80438e52951edeb18684d845e4.gif)](https://gyazo.com/d295bf80438e52951edeb18684d845e4)



### Official City Map
An interactive dashboard was created for an official city map.  This dashboard contains two map animations showing all stations and their popularity over time (each month).  The first map shows the popularity of starting stations, and the second map shows the popularity of ending stations.  An interesting observation is that covid-19 changes which stations are popular.  Before covid, the most popular stations appear to be in locations related to commuting- in the flat iron district, by the major train stations, and in the South-central area of Manhattan.  During covid, no stations appear to be significantly more popular than the rest, and overall ridership declines.  As time goes on many riders are still not commuting to work but getting ore comfortable going out, the season is getting warmer, more people are using bikes- but instead of commuting for work, they appear to do so for leisure. The most popular stations begin to be those at the perimeter of the island.

[![Image from Gyazo](https://i.gyazo.com/733c80061f5b884f521313a520303304.gif)](https://gyazo.com/733c80061f5b884f521313a520303304)

### Story
A tableau story was created to present all this information.
[![Image from Gyazo](https://i.gyazo.com/3c29602dc32313b33171bd9a6d3c3500.gif)](https://gyazo.com/3c29602dc32313b33171bd9a6d3c3500)
[![Image from Gyazo](https://i.gyazo.com/66ecd1bc88bb5efd8dea1a582a73d102.gif)](https://gyazo.com/66ecd1bc88bb5efd8dea1a582a73d102)

