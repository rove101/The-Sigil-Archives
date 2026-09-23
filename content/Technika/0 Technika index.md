---
publish: true
aliases:
  - Tech
  - tech
  - Technology
  - technology
title: Technika index
---

# Technika index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Technika index
```
