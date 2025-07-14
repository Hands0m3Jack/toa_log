---
{"dg-publish":true,"permalink":"/1-dm-toolkit/map/"}
---

```leaflet
id: MapChult ### Must be unique with no spaces
image: 
- [[Chult_fog.png]] ### Link to the map image file
bounds: [[0,0], [2997, 2213]] ### Size of the map in px Height_y, Width_x
height: 1200px ### Size of the leaflet embed in px on your screen
width: 95% ### Size of the leaflet embed in your note
lat: 1498.5 ### To center the map, make this half of the map width. 
long: 1106.5 ### To center the map, make this half of the map height. 
minZoom: -1.4 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level. 
maxZoom: 1 ### Controls how far towards the map you can zoom in.  Hover over the target icon to see the current level. 
defaultZoom: -1.35 ### Sets the default zoom level when the map loads.  Hover over the target icon to see the current level. 
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out. 
unit: ml ### The value displayed when measuring so you know what type of unit is being measure.
scale: 0.29411764705882354 ### Real units/px (resolution) of your map
recenter: false
darkmode: false ### marker
```
