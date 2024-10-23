# Planet_API_101
 A quick introduction to searching and ordering through the Planet API


* Planet Signup (stanford.edu only): <https://bit.ly/planetstanford>  

* Slides: <https://slides.com/staceymaples/planet-stanford-lovedataweek/>

* GISDay@Stanford w/Planet.com Workshops Notebooks/Data Download: <https://hello.planet.com/data/s/sdtjXQAPQpmBBbc>

## Introduction to Planet.com

### Explorer

* Searching in Explorer
* A Sample Search in Planet Explorer:
https://www.planet.com/explorer/?s=_wu2NPKDRVmXRy6PYcUCHQ
* Features Manager

* Ordering data in the GUI
* Code Snippets
* Viewing & Symbolizing Basemaps in Explorer

### Basemap Viewer

Quick overview of web maps & tile services: https://slides.com/d/uOzMMKQ/live#/3/1 

Klokan's Interactive Tile Demo: https://docs.maptiler.com/google-maps-coordinates-tile-bounds-projection/#2/40.33/14.82 

* https://www.planet.com/basemaps/#/mode/selection/mosaic/global_quarterly_2024q3_mosaic/zoom/2.3

* https://tiles{0-3}.planet.com/basemaps/v1/planet-tiles/global_quarterly_2024q3_mosaic/gmap/{z}/{x}/{y}.png?api_key={api-key}

Accessing the tiles, programmatically

* https://tiles.planet.com/basemaps/v1/planet-tiles/global_quarterly_2024q3_mosaic/gmap/0/0/0.png?api_key={api-key}

* Mercantile: https://mercantile.readthedocs.io/en/stable/quickstart.html 

### Integrations

#### QGIS
https://developers.planet.com/docs/integrations/qgis/

#### ArcGIS Pro
https://developers.planet.com/docs/integrations/arcgis/ 

#### Google Earth Engine

https://developers.planet.com/docs/integrations/gee/ 

https://developers.planet.com/docs/integrations/gee/quickstart/





## Area of Interest (AOI)

* Later, when you are interested in quickly making an AOI GeoJSON file for your own area, you can use geojson.io (You can just save this for later): <https://geojson.io/#map=15.05/37.42155/-122.17619>

* Use this file for the workshop: <https://raw.githubusercontent.com/StanfordGeospatialCenter/Planet_API_101/main/lakelagunita.geojson> (Download it to your machine, then drag&drop it to your Colabs File Panel, once you have the Python Notebook opened)

## Open the Notebook in Colab

* Go to: https://colab.research.google.com/

* Use this link in Colab: <https://github.com/StanfordGeospatialCenter/Planet_API_101> 

Or click the link, below:

<a target="_blank" href="https://colab.research.google.com/github/StanfordGeospatialCenter/Planet_API_101/blob/main/planet_API_101_LakeLagunita.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
