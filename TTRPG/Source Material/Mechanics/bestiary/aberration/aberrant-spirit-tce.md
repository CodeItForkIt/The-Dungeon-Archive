---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/medium
- monster/type/aberration
statblock: inline
aliases: ["Aberrant Spirit"]
---
# [Aberrant Spirit](Mechanics\bestiary\aberration/aberrant-spirit-tce.md)
*Source: Tasha's Cauldron of Everything p. 109*  

```statblock
"name": "Aberrant Spirit (TCE)"
"size": "Medium"
"type": "aberration"
"alignment": "Unaligned"
"ac_class": "11 + the level of the spell (natural armor)"
"stats":
- !!int "16"
- !!int "10"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "6"
"speed": "30 ft., fly 30 ft. (beholderkin only; hover)"
"damage_immunities": "psychic"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Deep Speech, understands the languages you speak"
"traits":
- "desc": "The aberration regains 5 hit points at the start of its turn if it has\
    \ at least 1 hit point."
  "name": "Regeneration (Slaad Only)"
- "desc": "At the start of each of the aberration's turns, each creature within 5\
    \ feet of the aberration must succeed on a Wisdom saving throw against your spell\
    \ save DC or take 2d6 psychic damage, provided that the aberration isn't [incapacitated](Mechanics/Rules/conditions.md#Incapacitated)."
  "name": "Whispering Aura (Star Spawn Only)"
"actions":
- "desc": "The aberration makes a number of attacks equal to half this spell's level\
    \ (rounded down)."
  "name": "Multiattack"
- "desc": "Ranged Spell Attack: YourSpellAttack to hit, range 150 ft., one creature.\
    \ Hit: 1d8 + 3 + the spell's level psychic damage."
  "name": "Eye Ray (Beholderkin Only)"
- "desc": "Melee Weapon Attack: YourSpellAttack to hit, reach 5 ft., one target.\
    \ Hit: 1d10 + 3 + the spell's level slashing damage. If the target is a creature,\
    \ it can't regain hit points until the start of the aberration's next turn."
  "name": "Claws (Slaad Only)"
- "desc": "Melee Spell Attack: YourSpellAttack to hit, reach 5 ft., one creature.\
    \ Hit: 1d8 + 3 + the spell's level psychic damage."
  "name": "Psychic Slam (Star Spawn Only)"
"source":
- "TCE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/TCE/Aberrant%20Spirit.webp"
```
^statblock