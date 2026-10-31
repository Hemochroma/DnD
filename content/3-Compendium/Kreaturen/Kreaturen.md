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
        - file.inFolder("3-Compendium/Kreaturen")
        - file.hasTag("srd/kreatur")
    groupBy:
      property: HG
      direction: ASC
    groupOrder:
      - 
      - "0"
      - 1/8
      - 1/4
      - 1/2
      - "1"
      - "2"
      - "3"
      - "4"
      - "5"
      - "6"
      - "7"
      - "8"
      - "9"
      - "10"
      - "11"
      - "12"
      - "13"
      - "14"
      - "15"
      - "16"
      - "17"
      - "19"
      - "20"
      - "21"
      - "22"
      - "23"
      - "24"
      - "30"
    order:
      - file.name
      - typ
      - ep
    cardSize: 70
    columnSize: {}

```
