### Session
```base
filters:
  and:
    - file.folder == ("Sessions")
properties:
  file.name:
    displayName: Sessions
formulas:
  Untitled: ""
views:
  - type: list
    name: list
```
### Map
```base
views:
  - type: leaflet-map
    name: Map
    mapName: Evils of Illmire
    image: theEvilsofIllmire.png
    height: 600
    minZoom: -1.5
    maxZoom: 2
    defaultZoom: 0.5
    zoomDelta: 0.25
    scale: "0.2"
    unit: km
```
### Players
```base
filters:
  and:
    - file.folder == "Players"
properties:
  file.name:
    displayName: Players
  file.links:
    displayName: Currently Playing
views:
  - type: table
    name: Table
    order:
      - file.name
      - Currently Playing
    sort:
      - property: Currently Playing
        direction: ASC

```

### Characters
```base
filters:
  and:
    - file.folder == "Characters/NPCs"
formulas:
  Untitled: ""
views:
  - type: table
    name: table
    order:
      - file.name
      - Location
    sort:
      - property: Location
        direction: ASC
```
### Locations
```base
filters:
  and:
    - file.folder == ("Locations")
formulas:
  Untitled: ""
views:
  - type: cards
    name: Card View
    cardSize: 140
```