---
publish: true
title: Cities index
---

# Cities index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: 0 Cities index
```
