# offline-vector-map

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

An exerimental of display vector map on HTML5 from local server. Donloaded offline vector tile (mbtiles) from openmaptiles is used as a map source and hosted by tileserver-gl-light. 

Folder public/gl-styles is contained style and map data, OSM-Bright style in public/gl-styles/styles/osm-bright/osm_bright is modified for local use which based on Mapbox GL style specification. 

Bangkok.mbtiles in /public/gl-style is used as test source.

run tileserver-gl-light will be called the config.json from root folder as by default.  

# conclusion
  - vector mbtiles is downloaded from openmaptiles.
  - tileserver-gl-light serve as local map server. 
  - mapbox-gl-js is used as frontend interface.
  - leaflet-mapbox-gl.js used to binding leafletjs Mapbox GL JS.

# Some note!

  - Rely on Chrome limitation, sprite cannot load via local, must be route by running webserver and passing as URL eg. http://localhost:....

