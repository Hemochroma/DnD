---
map_height_y: 1700
map_width_x: 2468
scale_pixels: 1700
scale_pixels_range: 2468
mapCalc1: 1.4517647058823528
tags:
  - Category/Region
image:
---

```leaflet  
id: MapCalcGrenzlande ### Must be unique with no spaces  
image: [[Helder der Grenzlande.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [2468, 1700]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 1200px ### Size of the leaflet embed in px on your screen  
width: 50% ### Size of the leaflet embed in your note  
lat: 1234 ### To center the map, make this half of the map height.  
long: 850 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: m ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 1.4517647058823528 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
