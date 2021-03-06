#### Maynooth University Chinese Summer School August 2016
### Introduction to Leaflet and Web Mapping

This is a set of lecture notes and practical examples for a laboratory-based lecture workshop on Leaflet and Web-based Mapping. 

#### Suggested Text Editors
GEANY  http://www.geany.org/download/releases#source  (If you are on Windows or Mac)
If you are on Linux try (sudo apt-get install geany)

Notepad++ https://notepad-plus-plus.org/download/v6.7.9.2.html (might be Windows only)

Bluefish http://bfwiki.tellefsen.net/index.php/Installing_Bluefish

Sublime Text Editor http://www.sublimetext.com/2

### Links used within the Lecture Notes

**Map Compare**: http://tools.geofabrik.de/mc/

**Get the Latitude Longitude of ANY Point** http://dbsgeo.com/latlon/

**LEAFLET - Layer Providers Page** - here you can pick a different background layer. The Javascript you require to insert this layer into your webmap application is also included http://leaflet-extras.github.io/leaflet-providers/preview/

** Mongoose Web Server ** https://www.cesanta.com/products

**US Geological Survey Current Earth Quake Activity for the Earth in GeoJSON format**: http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

** Color Brewer ** http://colorbrewer2.org/ - Useful suggestions on good color combinations for web-based mapping

** OpenStreetMap Map Features ** http://wiki.openstreetmap.org/wiki/Map_Features

### Overpass Turbo - for OpenStreetMap Data
https://overpass-turbo.eu/#

To find all of the nodes representing PARKING around Central London (radius of 3000m) the Overpass API query is as follows
```
node
  [amenity=parking]
(around:3000,51.507343,-0.127656);
out body;
```
