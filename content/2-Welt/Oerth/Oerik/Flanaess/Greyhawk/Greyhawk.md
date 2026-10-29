---
map_height_y: 1438
map_width_x: 2468
scale_pixels: 1438
scale_pixels_range: 2468
mapCalc1: 1.7162726008344922
tags:
  - Category/Continent
image: "[[Template_Continent_Placeholder.png]]"
---
```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.hasTag("Category/Region")
        - file.inFolder("2-Welt")
    image: note.image

```


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

