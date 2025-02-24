---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/hftt
- monster/cr/4
- monster/size/medium
- monster/type/monstrosity
statblock: inline
aliases: ["Demogorgon"]
---
# [Demogorgon](Mechanics\bestiary\monstrosity/demogorgon-hftt.md)
*Source: Hunt for the Thessalhydra p. 36*  

A predator of the Upside Down, the demogorgon hunts the dimension looking for unfortunate creatures that find their way there. The size and shape of an adult humanoid, the demogorgon's mouth encompasses its face and unfolds like a blossoming flower

```statblock
"name": "Demogorgon (HftT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"stats":
- !!int "16"
- !!int "12"
- !!int "16"
- !!int "3"
- !!int "12"
- !!int "5"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "5"
  "Perception": !!int "3"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "4"
"traits":
- "desc": "The demogorgon has advantage on Wisdom ([Perception](Mechanics/Rules/skills.md#Perception))\
    \ checks that rely on smell."
  "name": "Keen Smell"
- "desc": "The demogorgon has advantage on melee attack rolls against any creature\
    \ that doesn't have all its hit points."
  "name": "Blood Frenzy"
- "desc": "The demogorgon regains 10 hit points at the start of its turn. If the demogorgon\
    \ takes acid or fire damage, this trait doesn't function at the start of the demogorgon's\
    \ next turn. The demogorgon dies only if it starts its turn with 0 hit points\
    \ and doesn't regenerate."
  "name": "Regeneration"
"actions":
- "desc": "The demogorgon makes three attacks: one with its bite and two with its\
    \ claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d8 + 3) slashing damage."
  "name": "Claw"
"source":
- "HftT"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/HftT/Demogorgon.webp"
```
^statblock