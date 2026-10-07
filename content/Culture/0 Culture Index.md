---
publish: true
title: Culture Index
---

# Culture Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Culture Index
```
