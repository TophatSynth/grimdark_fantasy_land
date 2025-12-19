Rest, restock, prepare. Also much party

---
```leaflet  
id: Riverwell ### Must be unique with no spaces  
image: [[Riverwell.webp]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [8500, 6200]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 750px ### Size of the leaflet embed in px on your screen  
width: 90% ### Size of the leaflet embed in your note  
lat: 4250 ### To center the map, make this half of the map height.  
long: 3100 ### To center the map, make this half of the map width.  
minZoom: -4 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 3 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -3.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false
marker:
- Road,6156,5358.6669921875,Southern Wyrmhold Road,,,
- Road,5811.474817222844,539.2863114289629,Mistbridge-Riverwell Road,,,
- Road,212,4398.666748046875,Nose and Neck - Coastal Road,,,
- Town,Coordinates,<Linked Note>,,<minZoom*>,<maxZoom*>

```

