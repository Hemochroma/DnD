---
map_height_y: 1438
map_width_x: 2468
scale_pixels: 1438
scale_pixels_range: 2468
mapCalc1: 1.7162726008344922
---

> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`

```leaflet  
id: MapCalcGreyhawk ### Must be unique with no spaces  
image: [[Greyhawk.png]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1438, 2048]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 1000px ### Size of the leaflet embed in px on your screen  
width: 80% ### Size of the leaflet embed in your note  
lat: 719 ### To center the map, make this half of the map height.  
long: 1024 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -0.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: m ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 1.7162726008344922 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```

