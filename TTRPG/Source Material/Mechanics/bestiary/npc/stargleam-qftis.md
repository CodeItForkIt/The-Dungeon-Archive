---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/qftis
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Stargleam"]
---
# [Stargleam](Mechanics\bestiary\npc/stargleam-qftis.md)
*Source: Quests from the Infinite Staircase*  

```statblock
"name": "Stargleam (QftIS)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "12"
"hp": !!int "67"
"hit_dice": "9d10 + 18"
"stats":
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "11"
- !!int "17"
- !!int "16"
"speed": "50 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Celestial, Elvish, Sylvan, telepathy 60 ft."
"cr": "5"
"traits":
- "desc": "Stargleam's innate spellcasting ability is Charisma (spell save DC 14).\
    \ Stargleam can innately cast the following spells, requiring no components:\n\
    \nAt will: [detect evil and good](Mechanics/spells/detect-evil-and-good.md),\
    \ [druidcraft](Mechanics/spells/druidcraft.md), [pass without trace](Mechanics/spells/pass-without-trace.md)\n\
    \n1/day each: [calm emotions](Mechanics/spells/calm-emotions.md), [dispel\
    \ evil and good](Mechanics/spells/dispel-evil-and-good.md), [entangle](Mechanics/spells/entangle.md)"
  "name": "Innate Spellcasting"
- "desc": "If Stargleam moves at least 20 feet straight toward a target and then hits\
    \ it with a horn attack on the same turn, the target takes an extra 9 (2d8)\
    \ piercing damage. If the target is a creature, it must succeed on a DC 15 Strength\
    \ saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Charge"
- "desc": "Stargleam has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Stargleam's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "Stargleam makes two attacks: one with its hooves and one with its horn."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) bludgeoning damage."
  "name": "Hooves"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Horn"
- "desc": "Stargleam touches another creature with its horn. The target magically\
    \ regains 11 (2d8 + 2) hit points. In addition, the touch removes all diseases\
    \ and neutralizes all poisons afflicting the target."
  "name": "Healing Touch (3/Day)"
- "desc": "Stargleam magically teleports itself and up to three willing creatures\
    \ it can see within 5 feet of it, along with any equipment they are wearing or\
    \ carrying, to a location Stargleam is familiar with, up to 1 mile away."
  "name": "Teleport (1/Day)"
"legendary_actions":
- "desc": "Stargleam makes one attack with its hooves."
  "name": "Hooves"
- "desc": "Stargleam creates a shimmering, magical field around itself or another\
    \ creature it can see within 60 feet of it. The target gains a +2 bonus to AC\
    \ until the end of Stargleam's next turn."
  "name": "Shimmering Shield (Costs 2 Actions)"
- "desc": "Stargleam magically regains 11 (2d8 + 2) hit points."
  "name": "Heal Self (Costs 3 Actions)"
"source":
- "QftIS"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/QftIS/Stargleam.webp"
```
^statblock