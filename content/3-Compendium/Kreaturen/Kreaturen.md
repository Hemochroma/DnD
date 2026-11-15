---
tags:
  - "srd/index"
---
```base
views:
  - type: table
    name: View
    filters:
      and:
        - file.inFolder("3-Compendium/Kreaturen")
        - file.hasTag("srd/kreatur")
    groupBy:
      property: source
      direction: ASC
    groupOrder:
      - SRD
    order:
      - file.name
      - type
      - HG
      - ep
    sort:
      - property: HG
        direction: ASC
      - property: type
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      file.name: 345

```
