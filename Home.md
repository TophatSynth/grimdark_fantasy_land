
<center> Homepage with Leaflet map </center>
---

```leaflet  
id: OverviewMap ### Must be unique with no spaces  
image: [[WIP Map.webp]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [725, 1024]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 500px ### Size of the leaflet embed in px on your screen  
width: 100% ### Size of the leaflet embed in your note  
lat: 362 ### To center the map, make this half of the map height.  
long: 512 ### To center the map, make this half of the map width.  
minZoom: -1 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -0.5 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.24193548387096772 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false
marker:
- Town,662.1666717529297,436,Wintermore (Name placeholder),,<minZoom*>,<maxZoom*>,
- Town,396.5,471,Mistbridge (Name Placeholder),,<minZoom*>,<maxZoom*>
- Town,110.5,872,Ironkeep (Name Placeholder),,<minZoom*>,<maxZoom*>
- Town,193.5,659.3333129882812,Riverwell (Name placeholder),,<minZoom*>,<maxZoom*>
- Road,163.16665649414062,766.1666259765625,Nose and Neck - Coastal Road,,,
- Road,330.6458435058594,724.5000305175781,Southern Wyrmhold Road,,,
- Road,443.6666717529297,591.1666564941406,Northern Wyrmhold Road,,,

```

---
```base
filters:
  or:
    - file.tags.contains("todo")
properties:
  file.folder:
    displayName: Folder
  file.name:
    displayName: To work on
views:
  - type: table
    name: Table
    order:
      - file.name
    sort:
      - property: file.ctime
        direction: DESC
    columnSize:
      file.name: 400

```

---
## Notes here:

## TechSavvySynth's Notes:
- Need to read up on all the lore so far, then re-organise them so it's a lil clearer
 - [x] Use bases to make TOC 
	- [ ] Show number of todo tags per file?
- Work on alchemy 
- Spirit fragment types need thinking
- Add my fireflower idea to [[Ironkeep (Name Placeholder)]] 

---
## BoomerNoiza's Notes:

- Ideas to add for the Sandbox/Brainstorm Area:
	- Fortified Inns along the roads (The chain broken and Inns varying widely in architecture and state of repair)
	- "The Paladins" (Name pending) have a smallish keep in the area
	- There is at least one Thin-veiled area in the valley, allowing the "Predators" easy access
<br>
- Would like an Alchemy-System
- Flora & Fauna: Should we go full fantastical or use real world animals at least to keep things grounded (and less work)?
	- {I'd say go with what we did for Vilenought. Real world animals, corrupted by the veil}