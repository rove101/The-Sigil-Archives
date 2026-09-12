---
publish: true
title: Rules index
---

# Rules index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: Rules index
```
