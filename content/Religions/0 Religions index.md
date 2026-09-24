---
publish: true
title: Religions index
---

# Religions index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Religions index
    limit: 5

```
