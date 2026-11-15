---
navigation_level: 2
tags:
  - Category/Group
---

```base
properties:
  note.char_race:
    displayName: Race
  note.char_gender:
    displayName: Gender
  note.char_age:
    displayName: Age
  note.level:
    displayName: Level
  note.char_class:
    displayName: Class
views:
  - type: cards
    name: Table
    filters:
      and:
        - file.hasTag("Category/Player")
        - file.folder == "1-Party/Die Götter von Morgen"
    order:
      - file.name
      - level
      - Klasse
      - Unterklasse
    sort:
      - property: level
        direction: ASC
    image: note.image
    cardSize: 150
    imageFit: contain
    imageAspectRatio: 1.5

```
