---
publish: true
title: Story index
---

# Story index

> [!tip] The [[Temporal Scribes]] are busy at work maintaining the [[Chronal-Vortex]]. As such, we have elected to place all writings not in chronological order, but in order we receive them from our [[Wayfarers]].

---

```base
filters:
  and:
    - file.inFolder("Anthology/Campaigns")
    - file.ext == "md"
    - '!file.hasTag("Sig-MD")'
views:
  - type: list
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
    - '!file.hasTag("Sig-MD")'
views:
  - type: list
    name: Session index
    sort:
      - property: file.ctime
        direction: DESC
```
