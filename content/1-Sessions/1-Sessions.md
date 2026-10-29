---
navigation_level: 1
image: "[[AdventureIcon.png]]"
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
