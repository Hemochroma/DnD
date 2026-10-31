---
tags:
  - "srd/index"
---



## Klassen
```base
views:
  - type: cards
    name: Sicht
    filters:
      and:
        - file.inFolder("3-Compendium/Charaktere/Klassen")
        - '!file.hasTag("srd/index")'
        - file.hasTag("srd/klasse")
    order:
      - file.name
    sort:
      - property: file.tags
        direction: ASC
      - property: file.name
        direction: ASC
    markers: bullet
    indentProperties: false
    cardSize: 100
    imageAspectRatio: 1
    image: note.image

```
## Spezies

```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.inFolder("3-Compendium/Charaktere/Spezies")
        - file.hasTag("srd/spezies")
    order:
      - file.name
    sort:
      - property: file.tags
        direction: ASC
      - property: file.name
        direction: ASC
    markers: bullet
    indentProperties: false
    cardSize: 100
    imageAspectRatio: 1
    image: note.image
```

## Hintergründe
```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.inFolder("3-Compendium/Charaktere/Hintergründe")
        - file.hasTag("srd/hintergrund")
    order:
      - file.name
    sort:
      - property: file.tags
        direction: ASC
      - property: file.name
        direction: ASC
    markers: bullet
    indentProperties: false
    cardSize: 100
    imageAspectRatio: 1
    image: note.image
```

## Talente

### Herkunftstalente

```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.hasTag("srd/talent")
        - file.inFolder("3-Compendium/Charaktere/Talente/Herkunftstalente")

```

### Allgemeine Talente

```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.hasTag("srd/talent")
        - file.inFolder("3-Compendium/Charaktere/Talente/Allgmeine Talente")

```

### Kampfstil-Talente

```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.hasTag("srd/talent")
        - file.inFolder("3-Compendium/Charaktere/Talente/Kampfstil-Talente")

```

### Epische-Gabe-Talente

```base
views:
  - type: list
    name: Sicht
    filters:
      and:
        - file.hasTag("srd/talent")
        - file.inFolder("3-Compendium/Charaktere/Talente/Epische Gabe Talente")

```