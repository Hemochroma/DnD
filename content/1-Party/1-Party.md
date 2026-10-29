---
navigation_level: 1
image: "[[PartyLogo.jpg]]"
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
