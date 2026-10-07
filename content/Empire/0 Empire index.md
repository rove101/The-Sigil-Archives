---
publish: true
title: Empire index
---

# Empire Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Kingdom index
    groupBy:
      property: tags
      direction: ASC
    sort:
      - property: file.name
        direction: ASC
    markers: bullet

```
