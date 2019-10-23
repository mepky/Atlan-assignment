# Atlan-assignment


##  Aim:Identify commercial centers using Points of Interest (POI) data

![Language](https://img.shields.io/badge/Language-Python3-blue.svg)

## Introduction

The main pupose of this assignment is to get points of interest from open data sources like open street maps (OSM).
We have to get points of interest data for one city so i have chosen my city (kolkata) , i framed the query in [overpass-turbo](https://overpass-turbo.eu/) to get the city POI data .In city point on interest ,i considered phisical entity that makes more sense like cafe,resturants,school,hospital,railways-station,airport,hoistorical-building,commercial-building etc.

## Table of contents
----------------  Get OSM data from  [link](https://www.openstreetmap.org/#map=11/28.6518/77.2219)  and choose the city kolkata then export it.  

----------------- Go to the overpass-turbo [link](https://overpass-turbo.eu/#) to fame query.
[link](https://github.com/mepky/Atlan-assignment/blob/master/visualised_result/query.txt) i saved query in query.txt file.
After run query i got result like: 
<img src="https://github.com/mepky/Atlan-assignment/blob/master/visualised_result/poi_result.png" align="right" hspace="1" vspace="1" height="400" width="268">

----------------- Extract framed query data from overpass-turbo

----------------- Convert the kolkata_osm_data to kolkata_poi_data using ogr2ogr[API Link](https://ogre.adc4gis.com/).Data will be converted to SHAPEFILE.


