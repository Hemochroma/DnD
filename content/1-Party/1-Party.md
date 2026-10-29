---
navigation_level: 1
---
```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("1-Party")
        - file.hasTag("Category/Group")
    sort:
      - property: file.name
        direction: ASC

```
