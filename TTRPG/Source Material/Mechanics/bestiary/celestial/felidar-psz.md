---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psz
- monster/cr/5
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Felidar"]
---
# [Felidar](Mechanics\bestiary\celestial/felidar-psz.md)
*Source: Plane Shift: Zendikar p. 23*  

Standing fully ten feet high at the shoulder, the great cats called felidars are noble, fierce beasts charged with white mana. Felidars consent to be ridden only by knights they consider virtuous. The crystalline horns rising from a hard plate on their foreheads glow with white or golden light when they spring into battle, sometimes brightly enough to blind their foes.

In game terms, a felidar is similar to a [unicorn](Mechanics/bestiary/celestial/unicorn.md), with changes that reflect its feline nature.

```statblock
"name": "Felidar (PSZ)"
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
"languages": "Celestial, telepathy 60 ft."
"cr": "5"
"traits":
- "desc": "The felidar's innate spellcasting ability is Charisma (spell save DC 14).\
    \ The felidar can innately cast the following spells, requiring no components:\n\
    \nAt will: [detect evil and good](Mechanics/spells/detect-evil-and-good.md),\
    \ [light](Mechanics/spells/light.md), [thaumaturgy](Mechanics/spells/thaumaturgy.md)\n\
    \n1/day each: [calm emotions](Mechanics/spells/calm-emotions.md), [daylight](Mechanics/spells/daylight.md),\
    \ [dispel evil and good](Mechanics/spells/dispel-evil-and-good.md)"
  "name": "Innate Spellcasting"
- "desc": "If the felidar moves at least 20 feet straight toward a creature and then\
    \ hits it with a claws attack on the same turn, the target must succeed on a DC\
    \ 15 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone).\
    \ If the target is [prone](Mechanics/Rules/conditions.md#Prone), the felidar can\
    \ make one bite attack against it as a bonus action."
  "name": "Pounce"
- "desc": "The felidar has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The felidar's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The felidar makes two attacks with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d6 + 4) slashing damage."
  "name": "Claws"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8\
    \ + 4) piercing damage."
  "name": "Bite"
- "desc": "The felidar touches another creature with its horns. The target magically\
    \ regains 11 (2d8 + 2) hit points. In addition, the touch removes all diseases\
    \ and neutralizes all poisons afflicting the target"
  "name": "Healing Touch (3/Day)"
- "desc": "The felidar magically teleports itself and up to three willing creatures\
    \ it can see within 5 feet of it, along with any equipment they are wearing or\
    \ carrying, to a location the felidar is familiar with, up to 1 mile away."
  "name": "Teleport (1/Day)"
"legendary_actions":
- "desc": "The felidar makes one attack with its claws."
  "name": "Claws"
- "desc": "The felidar creates a shimmering magical field around itself or another\
    \ creature it can see within 60 feet of it. The target gains a +2 bonus to AC\
    \ until the end of the felidar's next turn."
  "name": "Shimmering Shield (Costs 2 Actions)"
- "desc": "The felidar magically regains 11 (2d8 + 2) hit points."
  "name": "Heal Self (Costs 3 Actions)"
"source":
- "PSZ"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSZ/Felidar.webp"
```
^statblock