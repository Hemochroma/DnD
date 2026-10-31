---
tags:
  - "srd/index"
---
```base
views:
  - type: table
    name: Sicht
    filters:
      and:
        - file.hasTag("srd/gift")
    order:
      - file.name
      - giftart
      - kosten

```
