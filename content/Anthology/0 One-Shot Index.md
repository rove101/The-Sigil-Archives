---
publish: true
title: Multidimensional Index
---

# One-Shot Index

> [!Warning]
> Due to an unfortunate fluctuation in the [[Chronal-Vortex]], several of our [[Wayfarers]] were lost to the Multiverse. Even so, these brave souls continue to carry out the [[Sigil Order]]’s mission, and this collection is dedicated to them. It contains all the knowledge they send back to us. Out of respect and hope for their eventual return, these archives will remain organized solely in alphabetical order—so that they may one day have the honor of cataloging the records appropriately themselves.

```base
filters:
  and:
    - file.inFolder("atlas-vtt/campaigns")
    - file.ext == "md"
    - file.hasTag("Sig-MD")
views:
  - type: cards
    name: Campaign index
    groupBy:
      property: tags
      direction: ASC
    sort:
      - property: file.name
        direction: ASC
    markers: bullet

```

---

```base
filters:
  and:
    - file.inFolder("Anthology/Session Notes/One-Shots")
    - file.ext == "md"
views:
  - type: list
    name: Session index
    groupBy:
      property: tags
      direction: ASC
    sort:
      - property: file.ctime
        direction: DESC

```
