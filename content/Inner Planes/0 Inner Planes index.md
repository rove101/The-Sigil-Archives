---
publish: true
title: Inner Planes index
---

# Inner Planes index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: Inner Planes index
```
