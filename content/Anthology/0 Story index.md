---
publish: true
title: Story index
---

# Story index

> [!tip] The Temporal Scribes are busy at work maintaining the chronic vortex

---

```base
filters:
  and:
    - file.inFolder("Anthology/Campaigns")
    - file.ext == "md"
views:
  - type: table
    name: Campaign index
    sort:
      - property: file.ctime
        direction: DESC

```

---

```base
filters:
  and:
    - file.inFolder("Anthology/Session Recaps")
    - file.ext == "md"
views:
  - type: table
    name: Session index
    sort:
      - property: file.ctime
        direction: DESC

```
