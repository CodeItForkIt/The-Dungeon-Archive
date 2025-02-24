---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/16
- monster/size/large
- monster/type/fiend
statblock: inline
aliases: ["Ekengarik"]
---
# [Ekengarik](Mechanics\bestiary\npc/ekengarik-coa.md)
*Source: Chains of Asmodeus p. 141*  

```statblock
"name": "Ekengarik (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "231"
"hit_dice": "22d10 + 110"
"stats":
- !!int "23"
- !!int "16"
- !!int "21"
- !!int "14"
- !!int "17"
- !!int "21"
"speed": "30 ft."
"saves":
  "Charisma": !!int "10"
  "Constitution": !!int "10"
"skillsaves":
  "Deception": !!int "10"
  "Insight": !!int "8"
  "Persuasion": !!int "10"
"damage_resistances": "acid; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 13"
"languages": "Common, Formian, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Ekengarik casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 18):\n\nAt will:\
    \ [Detect Magic](Mechanics/spells/detect-magic.md), [Dispel Magic](Mechanics/spells/dispel-magic.md),\
    \ [Heroism](Mechanics/spells/heroism.md), [Magic Missile](Mechanics/spells/magic-missile.md)\n\
    \n1/day each: [Evard's Black Tentacles](Mechanics/spells/evards-black-tentacles.md),\
    \ [Cone of Cold](Mechanics/spells/cone-of-cold.md), [Confusion](Mechanics/spells/confusion.md),\
    \ [Dimension Door](Mechanics/spells/dimension-door.md), [Geas](Mechanics/spells/geas.md),\
    \ [Invisibility](Mechanics/spells/invisibility.md), [Prismatic Wall](Mechanics/spells/prismatic-wall.md),\
    \ [Slow](Mechanics/spells/slow.md)"
  "name": "Spellcasting"
- "desc": "All fiendish formians within 1 mile of Ekengarik can telepathically communicate\
    \ with each other and Ekengarik."
  "name": "Hive Mind"
- "desc": "Ekengarik regenerates 10 hit points at the start of her turn, unless she\
    \ took radiant damage in the last round."
  "name": "Regeneration"
"actions":
- "desc": "Ekengarik makes three Bite attacks. She can replace one of the attacks\
    \ with an Acid Spray (if available) attack or a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one target. Hit: 15\
    \ (2d8 + 6) piercing damage and the target must make a DC 19 Constitution saving\
    \ throw. On a failed save, the target's Strength score is reduced by 2 (1d4).\
    \ The target dies if this reduces its Strength to 0. Otherwise, the reduction\
    \ lasts until the target finishes a short or long rest."
  "name": "Bite"
- "desc": "Ekengarik spits acid at one creature within 60 feet of her, or two creatures\
    \ within 60 feet of her and 5 feet of each other. Targets must make a DC 18 Dexterity\
    \ saving throw, taking 33 (6d10) acid damage on a failed saving throw, or half\
    \ as much on a successful one."
  "name": "Acid Spray (Recharge 5-6)"
"reactions":
- "desc": "When hit with an attack, Ekengarik temporarily hardens her carapace, reducing\
    \ her speed to 0 and increasing her AC by 5 until the start of her next turn."
  "name": "Hardened Carapace (Recharge 4-6)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Ekengarik.webp"
```
^statblock