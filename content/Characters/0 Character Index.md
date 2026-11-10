---
publish: true
title: Character Index
tags:
  - Character
---

# Character Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: cards
    name: 0 Character index
    sort:
      - property: file.name
        direction: ASC
    image: note.image

```
