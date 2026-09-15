---
publish: true
title: Travel index
---

# Travel index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Travel index
```
