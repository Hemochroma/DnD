---
tags:
  - "srd/index"
---
```base
views:
  - type: table
    name: Sicht
    filters:
      and:
        - file.inFolder("3-Compendium/Magische Gegenstände")
        - file.hasTag("srd/magischer-gegenstand")
    groupBy:
      property: kategorie
      direction: ASC
    order:
      - file.name
      - kategorie
      - seltenheit
      - einstimmung
    sort:
      - property: seltenheit
        direction: DESC
      - property: file.name
        direction: ASC

```
