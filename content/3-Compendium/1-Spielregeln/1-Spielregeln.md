```base
properties:
  note.fileName:
    displayName: File
  note.Theme:
    displayName: Thema
views:
  - type: table
    name: Table
    filters:
      and:
        - file.folder.startsWith("3-Compendium/Mechaniken/1-Spielregeln")
    order:
      - file.name
    sort:
      - property: file.folder
        direction: ASC

```
