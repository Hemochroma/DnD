---
navigation_level: 1
---
```base
views:
  - type: cards
    name: Kategorie
    filters:
      and:
        - file.inFolder("3-Compendium")
        - file.hasTag("srd/index")
    order:
      - file.name

```
