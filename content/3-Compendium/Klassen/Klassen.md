---
navigation_level: 2
---

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen")
        - '!file.path.containsAny("Unterklassen")'
        - file.name != "Klassen"
    order:
      - file.name
      - PrimärAttribut
      - Rettungswürfe
      - Trefferwürfel
    markers: bullet
    cardSize: 200
    image: note.Icon
    imageAspectRatio: 1
    indentProperties: true
    imageFit: contain

```
