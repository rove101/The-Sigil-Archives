---
publish: true
title: Outer Planes index
---

# Outer Planes index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: Outer Planes index
```
