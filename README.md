## Goal: Reduce Child Mortality (Under the age of 5, per 1000 birth)


**Correlation of Child Mortality with World Bank Development Indicators**


This is my submission to the [United Nations' Data Visualization Competition #WSD2015](https://unite.un.org/ideas/content/wsd2015-data-visualization-challenge) in celebration of the World's Statistics Day. The increasing availability of data is an opportunity to better understand the world around us. The pursuit to reduce child mortality must rely on data-driven decisions that examine its relationship with social, environmental and economic factors. The World Bank Development Indicators present the most robust and comprehensive repository measuring these factors. We examine these relationships by computing the correlation between child mortality under the age of five and each of the 1343 development indicators available in the World Bank’s database. Since data is better seen than read, we decided to visualize the correlations onto the world map, where you can see child mortality in the background color fill and how a selected indicator relates to it using markers on each country.


The top correlation development indicators should be used to efficiently address the reduction of child mortality in an indirect manner. Positively correlated indicators should be actively reduced through United Nations Organizations efforts. Similarly, negatively correlated indicators should be actively supported.



**Tools Used**

1. R: Used to compute the correlations on each development indicator with child mortality.

2. Java Script: Used in building the visualization. [JVectorMap](http://jvectormap.com/) library is used to build the map. [ChartNew](https://github.com/FVANCOP/ChartNew.js) library is used to chart the correlations. [CSVtoJSON](http://www.csvjson.com/csv2json) is used to convert comma-separated value to JSON format.

3. HTML + CSS: Used in building and styling the demo page.

4. MS Excel: Used to sort and transpose the data where necessary


Leave a comment if you see additional interesting info presented by the data.

Data source can be found [here](http://dim.csvalley.com/files/Child%20Mortality%20Source%20Files.zip).
