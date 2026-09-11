---
publish: true
title: Planets Index
---

# Planets Index

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: 0 Planets Index
```
