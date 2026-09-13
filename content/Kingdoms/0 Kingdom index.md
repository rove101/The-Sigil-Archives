---
publish: true
title: Kingdom index
---

# Kingdom index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: Kingdom index
```
