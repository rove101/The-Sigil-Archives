---
publish: true
title: Character Index
---

# Character Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: 0 Character index
    sort:
      - property: file.mtime
        direction: ASC

```
