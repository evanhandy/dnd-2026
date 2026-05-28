---
title: Maps
aliases:
  - Maps
---
A collection of the various maps of the campaign, some of which are interactable with map pins leading to location notes. For a list of all locations, including those *not* on maps, see [[Maps/Locations/index|Locations]].

## Maps

```base
filters:
  and:
    - file.hasTag("map")
views:
  - type: list
    name: Maps
    order:
      - file.name
      - description

```

