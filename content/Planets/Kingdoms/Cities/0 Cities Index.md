---
publish: true
title: Cities Index
---

# Cities Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: 0 Cities Index
```
