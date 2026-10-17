---
navigation_level: 2
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
        - file.folder == "1-Party/Helden der Grenzlande"
        - file.name != "Helden der Grenzlande"
    order:
      - file.name
    sort:
      - property: level
        direction: ASC
    image: note.Icon
    cardSize: 150
    imageFit: contain
    imageAspectRatio: 1.5

```
