---
navigation_level: 1
---
```base
views:
  - type: cards
    name: Kategorie
    filters:
      and:
        - navigation_level == 2
        - file.inFolder("3-Compendium")
    order:
      - file.name

```
