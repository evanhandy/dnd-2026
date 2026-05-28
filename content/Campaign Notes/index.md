---
title: Campaign Notes
aliases:
  - Campaign Notes
---
This is the home for the various logistical details of the campaign; session plans, story arc info, and other things that don't necessarily fit into [[World Lore/index|World Lore]].

One such detail is this visual representation of the basic campaign conceit: [[Campaign-Mindmap]]

## Session List

```base
filters:
  and:
    - file.hasTag("session")
views:
  - type: list
    name: Sessions
    groupBy:
      property: arc
      direction: ASC
    order:
      - file.name
      - description
    sort: []

```

