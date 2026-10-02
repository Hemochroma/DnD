---
navigation_level: 1
---

```base
views:
  - type: list
    name: Tabelle
    filters:
      and:
        - file.inFolder("1-Sessions")
        - file.name != "1-Sessions"
    markers: bullet
    indentProperties: true

```
