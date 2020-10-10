# offline-vector-map

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

An exeriment of display vector map on HTML5 from local server. Offline vector tile (mbtiles) which is downloaded from openmaptiles was used as map source and hosted by tileserver-gl-light. 

Folder gl-styles is contained style and map data, OSM-Bright style is modified for local use which based on Mapbox GL style specification. 

Bangkok.mbtiles in /public/gl-style is downloaded from openmaptiles.com to use as test source.

run tileserver-gl-light from root folder will be called the config.json 

# conclusion!
  - tileserver-gl-light serve as local map server, mbtiles is downloaded from openmaptiles.  
  - leaflet-mapbox-gl.js used to binding leafletjs Mapbox GL JS.

# Some note!

  - sprite cannot load via local, must be by pass as URL eg. http://localhost:....

