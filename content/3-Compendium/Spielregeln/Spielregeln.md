---
navigation_level: 2
---

```base
views:
  - type: cards
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Spielregeln")
        - file.name != "Spielregeln"
    order:
      - file.name

```
