---
publish: true
title: History Index
---

# History Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: History index
    groupBy:
      property: Era Name
      direction: ASC
    groupOrder:
      - Planetary Extinction Event
      - Era of Steam
      - Fungal Outbreak
      - Anthropomorphic
      - Interstellar Travel
    sort:
      - property: Era Date
        direction: DESC

```
