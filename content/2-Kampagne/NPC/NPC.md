---
navigation_level: 2
---

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("2-Kampagne/NPC")
        - file.ext == "md"
        - file.name != "NPC"
    image: note.image
    imageAspectRatio: 1.5

```
