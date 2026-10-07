---
publish: true
title: Species index
---

# Species Index

> [!quote] How to Read Biological Classification and Other Large Words for the Lesser Minded
> Due to the many different species present throughout our studies. I, [[Thuurd Möotsuus]] (in common means 'gem-throne'), have devised a way to classify each known creature. Be it man or beast, divine or corrupt. The official order, as adopted by the [[Sigil Order]], is as follows. First is the creature typing or 'Classis'. This is a general category referring to what the creature is. For example either a Monstrosity or Humanoid. Next is 'Familia' to indicate grouping. All dragonoid and dragon adjacent creatures have this label. Finally, we have Species. This is the more common term used to describe a specific grouping of creatures. To keep it simple for you, the word "Elf" is an example.

```base
filters:
  and:
    - file.folder == this.file.folder
    - file.path != this.file.path
    - file.ext == "md"
views:
  - type: list
    name: Species index
    groupBy:
      property: tags
      direction: ASC
    sort:
      - property: file.name
        direction: ASC

```
