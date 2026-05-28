---
tags:
  - map
description: A high-level overview map of the continent of Anroth
---
Another cool feature of this setup is interactable maps!

```base
views:
  - type: leaflet-map
    name: Map
    mapName: anroth
    image: AnrothDetailV1.png
    height: 380
    minZoom: -1.5
    maxZoom: 2
    defaultZoom: -1.5
    zoomDelta: 0.75
    scale: "0.3"
    unit: mi

```

> [!info] Hint
> Some markers can be hid until zoomed in. Try zooming in on Skyreach!
