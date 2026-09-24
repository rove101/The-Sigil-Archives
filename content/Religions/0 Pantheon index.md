---
publish: true
title: Religions index
---

# [[0 Gods index|Gods]]

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Gods index
    limit: 5

```

# [[0 Demi-Gods index|Demi-Gods]]

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Demi-Gods index
    limit: 5

```

# [[0 Saints index|Saints]]

```base
filters:
  and:
    - file.inFolder("Religions/Saints")
    - file.name != "0 Saints index"
    - file.ext == "md"
views:
  - type: list
    name: Saints index
    limit: 5

```

# [[0 Religions index|Religions]]

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Religions index
    limit: 5

```
