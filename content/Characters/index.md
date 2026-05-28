---
aliases:
  - Characters
title: Characters
---
## PCs

```base
filters:
  and:
    - file.hasTag("PC")
views:
  - type: list
    name: PCs
    order:
      - file.name
      - description
    imageAspectRatio: 1
    cardSize: 200

```

## NPCs

```base
filters:
  and:
    - file.hasTag("NPC")
views:
  - type: list
    name: NPCs
    order:
      - file.name
      - description
    imageAspectRatio: 1
    cardSize: 200

```

## Creatures

```base
filters:
  and:
    - file.hasTag("creature")
views:
  - type: list
    name: PCs
    order:
      - file.name
      - description

```
