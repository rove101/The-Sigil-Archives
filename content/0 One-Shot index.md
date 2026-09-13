---
publish: true
title: One-Shot index
---

# One-Shot index

> [!Warning]
> Due to an unfortunate fluctuation in the [[Chronal-Vortex]], several of our [[Wayfarers]] were lost to the Multiverse. Even so, these brave souls continue to carry out the [[Sigil Order]]’s mission, and this collection is dedicated to them. It contains all the knowledge they send back to us. Out of respect and hope for their eventual return, these archives will remain organized solely in alphabetical order—so that they may one day have the honor of cataloging the records appropriately themselves.

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: table
    name: One-Shot index
    filters:
      and:
        - file.hasTag("#Sig-MD")

```
