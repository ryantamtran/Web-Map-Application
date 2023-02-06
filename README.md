# Web-Map-Application
GEOG 458 Lab 3

This is the Web Map Application lab for GEOG 458. This includes two thematic maps, one is a choropleth map of the [COVID-19 rates] and the other is a proportional symbols map of [COVID-19 cases]. 

For the [COVID-19 rates] choropleth map, it uses the U.S county boundary shapefile downloaded from the U.S Census Bureau along with population data from the 2018 ACS 5 year estimates in order to calculate the case rates per thousand residents. When hovering a county on the map, the text on the top left window will change to the county you are currently hovering and will show information such as the COVID-19 rates, the county you are currently hovering over, and the state the the county is located in. 

The legend shows a list of 7 different groups of rates starting from 0 all the way up to 140+ and each group will correspond to a specific color. 

> *Choropleth map of COVID-19 rates in the United States*
![choropleth map](https://raw.githubusercontent.com/ryantamtran/Web-Map-Application/main/img/rates2.JPG)

> *What it looks like when hovering over a county*
![choropleth map1](https://raw.githubusercontent.com/ryantamtran/Web-Map-Application/main/img/rates.png)

For the [COVID-19 cases] proportional symbol map, it used the COVID-19 case/death date that was originally from the New York Times in order to track the amount of cases around the Untied States. Instead of hovering over a county like the previous map, this map will have you click on a dot instead in order to reveal more information about the location you're looking at. When clicking on one of the dot, it will show you information about how many cases were in that area.

> *Proportional symbol map of COVID-19 cases*
![Proportional symbol](https://raw.githubusercontent.com/ryantamtran/Web-Map-Application/main/img/count1.JPG)

> *What it looks like when clicking on a dot*\
![Proportional symbol1](https://raw.githubusercontent.com/ryantamtran/Web-Map-Application/main/img/count2.JPG)

### Libraries
For this assignment, I used React Mapbox GL JS as the framework and mapshaper.org in order to convert and compress our shapefiles/data into a geojson file. The data and assignment was hosted on Github and basemaps were provided by Mapbox.

### Sources
- [U.S Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)
- [2018 ACS 5 year estimates](https://data.census.gov/table?g=0100000US$050000&d=ACS+5-Year+Estimates+Data+Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true)
- [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv)


[COVID-19 rates]: https://ryantamtran.github.io/Web-Map-Application/map1.html
[COVID-19 cases]: https://ryantamtran.github.io/Web-Map-Application/map2.html
