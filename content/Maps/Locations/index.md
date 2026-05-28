---
aliases:
  - Locations
title: Locations
---
## Locations on Maps

```base
filters:
  and:
    - "!marker.isEmpty()"
    - file.tags.contains("location")
views:
  - type: list
    name: Locations
    order:
      - file.name
      - description

```

## Locations Not on Maps

```base
filters:
  and:
    - marker.isEmpty()
    - file.tags.contains("location")
views:
  - type: list
    name: Locations
    order:
      - file.name
      - description

```

