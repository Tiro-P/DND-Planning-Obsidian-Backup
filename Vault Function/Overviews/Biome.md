---
limit: 40
mapWithTag: true
icon: trees
tagNames:
  - biome
filesPaths: 
bookmarksGroups: 
excludes: 
extends: 
savedViews:
  - name: Risk level
    children: []
    sorters:
      - id: Biome____Risk-level
        name: Risk-level
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: Biome____file
        name: file
        query: ""
      - id: Biome____Creator
        name: Creator
        query: ""
      - id: Biome____Terrain
        name: Terrain
        query: ""
      - id: Biome____Risk-level
        name: Risk-level
        query: ""
      - id: Biome____Weather
        name: Weather
        query: ""
      - id: Biome____Climate
        name: Climate
        query: ""
    columns:
      - id: Biome____file
        name: file
        hidden: false
        position: 0
      - id: Biome____Creator
        name: Creator
        hidden: false
        position: 1
      - id: Biome____Terrain
        name: Terrain
        hidden: false
        position: 2
      - id: Biome____Risk-level
        name: Risk-level
        hidden: false
        position: 3
      - id: Biome____Weather
        name: Weather
        hidden: false
        position: 4
      - id: Biome____Climate
        name: Climate
        hidden: false
        position: 5
favoriteView: 
fieldsOrder:
  - xHBcnW
  - hnLKo3
  - bYPWQu
  - w8dI8v
  - xWGbs3
version: "2.33"
fields:
  - name: Creator
    type: Multi
    options:
      sourceType: ValuesList
      valuesList:
        "1": Astarte
        "2": Tataluk
        "3": Hysteria
        "4": Cujokra
        "5": Kesk
        "6": Muerin
    path: ""
    id: xHBcnW
  - name: Terrain
    type: Multi
    options:
      sourceType: ValuesList
      valuesList:
        "1": Coniferous Forest
        "2": Deciduous Forest
        "3": Plains
        "4": Island
        "5": Desert
        "6": Jungle
        "7": Tundra
        "8": Mountains
        "9": Ocean
        "10": Swamp
    path: ""
    id: hnLKo3
  - name: Risk-level
    type: Number
    options: {}
    path: ""
    id: bYPWQu
  - name: Climate
    type: Select
    options:
      sourceType: ValuesList
      valuesList:
        "1": Hot
        "2": Warm
        "3": Temperate
        "4": Cool
        "5": Cold
    path: ""
    id: xWGbs3
  - name: Weather
    type: Select
    options:
      sourceType: ValuesList
      valuesList:
        "1": Arid
        "2": Dry
        "3": Damp
        "4": Humid
        "5": Wet
        "6": Hazardous
        "7": None
    path: ""
    id: w8dI8v
---
