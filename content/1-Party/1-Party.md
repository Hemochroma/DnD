---
navigation_level: 1
---
```base
views:
  - type: table
    name: Tabelle
    filters:
      and:
        - navigation_level == 2
        - file.inFolder("1-Party")
    sort:
      - property: file.name
        direction: ASC

```
