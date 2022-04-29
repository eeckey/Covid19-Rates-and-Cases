# Covid19-Rates-and-Cases
Emily Eckey \
GEOG 458 Sp 22: Advanced Digital Geographies, Section AC \
Lab 3: Web Map Application \
April 29, 2022

## Project Introduction
This project includes two thematic maps using county level data. Map 1 is a choropleth map of covid-19 rates and Map 2 is a proportional symbols map of covid-19 cases.

## Links to Maps
- [Covid-19 Map 1](https://eeckey.github.io/Covid19-Rates-and-Cases/map1.html)
- [Covid-19 Map 2](https://eeckey.github.io/Covid19-Rates-and-Cases/map2.html)

## Map Screenshots
Map 1: Choropleth map of covid-19 rates in the United States by county
![Map 1](/img/map1.png "Map 1") 

Map 2: Proportional symbols of covid-19 cases in the United States by county
![Map 2](/img/map2.png "Map 2") 

## Primary Map Functions
- The primary function of Map 1 is the information window. When the cursor is hovering over a county, the information window shows the covid-19 rate information for that county and what state it is in. If the cursor is not hovering over a county, the information window says, "Hover over a county!"
- The primary function of Map 2 is the clickable data points to show the exact number of covid-19 cases and the county name.

## Libraries Used
- [Map Box API](https://docs.mapbox.com/api/overview/)
- [JavaScript](https://www.javascript.com/)

## Data Sources
The COVID-19 case/death data used are originally from [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv). The data include all the cases in 2020. The population data used for calculating the case rates are from the [2018 ACS 5 year estimate](https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true). Both data are at the county level. The U.S. county boundary shapefile was downloaded from the [U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html).

## Credits
- [MapBox](https://docs.mapbox.com/mapbox.js/api/v3.3.1/)
- [MapShaper](https://mapshaper.org/)
- [ColorBrewer](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)
- [Professor Zhao's Github Tutorial](https://github.com/jakobzhao/geog458/tree/master/labs/lab03)

## Acknowledgments
Thank you Professor Zhao and Jiaxin Feng for your assistance.

