# U.S. Covid-19 Visualization 2020

By Harry Li, April 28, 2022

## Introducation
This project visualizes the distribution of Covid-19 cases in 2020. Specificlly, there are two county level interactive maps illustrating the the spread of pandemic in the U.S., in 2020. One map shows the number of cases in the U.S. by counties, and the other map protrays the Covid-19 case rates. Both maps are created using MapBox in 'Albers' projection. Also, both maps are made on a light style base map in order to highlight the visualization or the layer of the maps. 

## [Covid-19 Case Rates Choropleth Map](map1.html)
![Covid rates map](/img/map1.jpg)
The Covid-19 Case Rates Choropleth Map shows the U.S. Covid-19 case rates for each county where the case rate is define by the total number of covid cases divided by the total population. The unit of the rates is the number of cases in 1,000 people. Each county is categorized into one of eight categories based on their case rates ranging from 0 to more than 200 cases in 1,000 people which is also defined in the legend at the bottom left of the map. From light to dark, the case rates increase from 0 to more than 200. This map gives reader a general look of the distribution of case rates. The color ramp from light to dark visualizes a clear and strong contrast, so that readers can easily identify what areas have relatively high case rates which means people are more likely to expose in these areas, and what areas have relatively low case rates which means that people are safer in these areas. There is also one interactive feature in this map. When your cursor hovers on one of the counties, it will display the name of that county and its state, and the exact case rates of that county. 

## [Covid-19 Counts Proportional Symbols Map](map2.html)
![Covid counts map](/img/map2.jpg)
The Covid-19 counts proportional symbols map shows the U.S. Covid-19 counts for each county. In this map, each county is represented by a dot. The size of the dot indicates the relative magnitude of the counts in this county. Furthermore, the dots are categorized into four categories defined in the legend at the bottom right of the map. From light to dark, the color represent more Covid cases. This map give readers a general overview of the Covid-19 counts in each county. We can easily identify some areas with large count of covid cases by just looking at the relative sizes and colors of the dots. For example, it's very obvious that some areas in California, and areas around the NYC have large amount of Covid cases since there are large and red dots at these areas. Also, there is an interactive feature in this map. When we click on any dot on the map, there will be a pop-up window telling you the exact Covid-19 cases in the particular county. 

## Library 
MapBox

## Data Sources
* The Covid-19 case and death data are from [the New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv)
* Population data for culculating case rates are from [2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true)
* The U.S. county boundary shapefile is from [the U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

## Acknowledgement
The data used in this project are provided by the UW Geography Department, processed by Steven Bao. 
