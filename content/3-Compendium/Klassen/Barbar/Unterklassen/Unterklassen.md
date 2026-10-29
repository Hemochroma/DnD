```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Barbar/Unterklassen")
        - file.name != "Unterklassen"
    order:
      - file.name
    markers: bullet
    cardSize: 200
    image: note.Icon
    imageAspectRatio: 0.95
    indentProperties: true

```
