---
navigation_level: 2
---
```base
views:
  - type: cards
    name: Tabelle
    filters:
      or:
        - navigation_level == 3
        - and:
            - file.inFolder("3-Compendium/Monster")
            - '!file.inFolder("3-Compendium/Monster/Monster von A-Z")'
            - '!file.inFolder("3-Compendium/Monster/Tiere von A-Z")'
            - file.name != "Monster"

```
