# Atlan-assignment


##  Aim:Identify commercial centers using Points of Interest (POI) data

![Language](https://img.shields.io/badge/Language-Python3-blue.svg) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/mepky/Atlan-assignment/blob/master/LICENSE)

## Introduction

The main pupose of this assignment is to get points of interest from open data sources like open street maps (OSM).
We have to get points of interest data for one city so i have chosen my city (kolkata) , i framed the query in [overpass-turbo](https://overpass-turbo.eu/) to get the city POI data .In city point on interest ,i considered phisical entity that makes more sense like cafe,resturants,school,hospital,railways-station,airport,hoistorical-building,commercial-building etc.

## Table of contents
----------------  Get OSM data from  [osm dataset](https://www.openstreetmap.org/#map=11/28.6518/77.2219)  and choose the city kolkata then export it.  

----------------- Go to the overpass-turbo to fame query.
([overpass-turbo](https://overpass-turbo.eu/#))
([query](https://github.com/mepky/Atlan-assignment/blob/master/visualised_result/query.txt))
I saved my query in query.txt file.
After run query we get result like: 
<img src="https://github.com/mepky/Atlan-assignment/blob/master/visualised_result/poi_result.png" align="right" hspace="1" vspace="1" height="400" width="368">

----------------- Extract framed query data from overpass-turbo

----------------- Convert the kolkata_osm_data to kolkata_poi_data using ogr2ogr.Data will be converted to SHAPEFILE.
[ogr2ogr](https://ogre.adc4gis.com)


In shapefile we have .dbf,.prj.shp,.shx file .

I used .shp file for visualisation in Tableau.

## Visualisation with Tableau
If you have online Tableau account then you could see it.[press here](https://prod-useast-a.online.tableau.com/#/site/kumar/views/Atlan-assignment/Sheet2?:iid=3)
In Other case [press it](https://github.com/mepky/Atlan-assignment/tree/master/Tableau-visualisation)

1.[sheet1](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%201.pdf) shows the name of all the aminent or node we have extracted from osm data.*separate paragraph*.

2.[sheet2](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%202.pdf) contains scatter plot of all extracted data points(latitude and longitude).*same line*.

3.[sheet3](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%203.pdf) contains name,amenity and building names in column and in row total number of data presents.

4.[sheet4](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%204.pdf) contains types of building (ex: commercial,historical etc..) in column .

5.[sheet5](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%205.pdf) contains all the aminity with number of occurece in city kolkata.

6.[sheet6](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%206.pdf) contains all the aminity with number of occurence(for ex: number of starbucks ,marketplace,cafe,school etc. All the POI data)

7.[sheet7](https://github.com/mepky/Atlan-assignment/blob/master/Tableau-visualisation/Sheet%207.pdf) contains ,which type of aminity presents how many times.

