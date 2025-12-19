Agriculture, livestock, farmland and liquor

---

```leaflet  
id: Mistbridge ### Must be unique with no spaces  
image: [[Mistbridge.webp]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [4800,6000]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 550px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 2400 ### To center the map, make this half of the map height.  
long: 3000 ### To center the map, make this half of the map width.  
minZoom: -3.25 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: -1.5 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -3.25 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.25 ### Adjust how much the zoom changes when you zoom in or out.  
unit: m ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.055279159756771695 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false
marker:
- Road,4353.3333740234375,3073.333251953125,Mistbridge-Wintermore Road,,,
- Road,4208.69956162233,4563.195876346181,Northern Wyrmhold Road,,,
- Road,33.29779922007619,2210.339721196314,Mistbridge-Riverwell Road,,,
- Town,Coordinates,<Linked Note>,,<minZoom*>,<maxZoom*>

```
