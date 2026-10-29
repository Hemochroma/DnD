```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Klassen/Hexenmeister/Unterklassen")
        - file.name != "Unterklassen"
    order:
      - file.name
    markers: bullet
    cardSize: 200
    image: note.Icon
    imageAspectRatio: 1
    indentProperties: true

```
