---
navigation_level: 2
---

```base
views:
  - type: table
    name: Tabelle
    filters:
      and:
        - file.inFolder("2-Kampagne/Gegenstände")
        - file.name != "Gegenstände"
    markers: bullet
    indentProperties: true

```
