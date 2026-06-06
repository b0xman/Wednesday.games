
```base
views:
  - type: leaflet-map
    name: Map
    mapName: Evils of Illmire
    image: [[theEvilsofIllmire.png]]
    height: 400
    minZoom: -1.5
    maxZoom: 2
    defaultZoom: -0.3
    zoomDelta: 0.25
    scale: "0.2"
    unit: km
```


```leaflet
id: leaflet-map
image: [[theEvilsofIllmire.png]]
height: 500px
lat: 50
long: 50
minZoom: 1
maxZoom: 10
defaultZoom: 9
unit: meters
scale: 3
marker: default, 39.983334, -82.983330, [[Note]]
darkMode: false
```



```zoommap
imageBases:
  - path: zzReference/theEvilsofIllmire.png
    name: The Evils of Illmire Map
markers: 
markerLayers:
  - Default
minZoom: 0.25
maxZoom: 8
wrap: false
responsive: false
width: 100%
height: 480px
resizable: false
resizeHandle: native
render: dom
id: mapmq1bqlhf
```

# Players
![[Players.base]]

# Characters
![[Characters.base]]

# Locations
![[Locations.base]]