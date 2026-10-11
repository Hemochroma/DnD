---
navigation_level: 2
---

```base
views:
  - type: list
    name: Tabelle
    filters:
      and:
        - file.inFolder("1-Sessions/Helden der Grenzlande")
        - file.name != "Helden der Grenzlande"
    markers: bullet
    indentProperties: true

```
