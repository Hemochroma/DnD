```base
properties:
  file.folder:
    displayName: Gruppe
views:
  - type: table
    name: Tabelle
    filters:
      and:
        - file.inFolder("3-Compendium/Spielregeln")
        - file.name != "Spielregeln2"
    order:
      - file.name
    sort:
      - property: file.name
        direction: ASC
      - property: monster_tp
        direction: DESC
      - property: monster_rk
        direction: DESC
      - property: monster_ini
        direction: DESC
      - property: monster_hg
        direction: DESC
      - property: file.folder
        direction: ASC
      - property: TP
        direction: ASC
      - property: RK
        direction: ASC
      - property: HG
        direction: DESC
    columnSize:
      note.family: 135

```

