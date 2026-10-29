---
navigation_level: 1
---

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("1-Sessions")
        - file.hasTag("Category/Journal")
    markers: bullet
    indentProperties: true

```
