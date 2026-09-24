---
publish: true
title: Pantheon index
---

# [[0 Gods index|Gods]]

```base
filters:
  and:
    - file.inFolder("Divinity/Gods")
    - file.name != "0 Gods index"
    - file.ext == "md"
formulas:
  Shuffle: random()
views:
  - type: list
    name: Gods index
    order:
      - file.name
    sort:
      - property: formula.Shuffle
        direction: ASC
    limit: 5

```

# [[0 Demi-Gods index|Demi-Gods]]

```base
filters:
  and:
    - file.inFolder("Divinity/Demi-Gods")
    - file.name != "0 Demi-Gods index"
    - file.ext == "md"
formulas:
  Shuffle: random()
views:
  - type: list
    name: Demi-Gods index
    order:
      - file.name
    sort:
      - property: formula.Shuffle
        direction: ASC
    limit: 5

```

# [[0 Saints index|Saints]]

```base
filters:
  and:
    - file.inFolder("Divinity/Saints")
    - file.name != "0 Saints index"
    - file.ext == "md"
formulas:
  Shuffle: random()
views:
  - type: list
    name: Saints index
    order:
      - file.name
    sort:
      - property: formula.Shuffle
        direction: ASC
    limit: 5

```

# [[0 Religions index|Religions]]

```base
filters:
  and:
    - file.inFolder("Divinity/Religions")
    - file.name != "0 Religions index"
    - file.ext == "md"
formulas:
  Shuffle: random()
views:
  - type: list
    name: Religions index
    order:
      - file.name
    sort:
      - property: formula.Shuffle
        direction: ASC
    limit: 5

```
