---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/veor
- monster/cr/21
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Rerak"]
---
# [Rerak](Mechanics\bestiary\npc/rerak-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Rerak (VEoR)"
"size": "Medium"
"type": "undead"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "199"
"hit_dice": "21d8 + 105"
"stats":
- !!int "10"
- !!int "16"
- !!int "20"
- !!int "25"
- !!int "19"
- !!int "15"
"speed": "30 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "11"
  "Intelligence": !!int "14"
  "Constitution": !!int "12"
"damage_immunities": "necrotic; poison; psychic; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned), [stunned](Mechanics/Rules/conditions.md#Stunned)"
"senses": "truesight 60 ft., passive Perception 14"
"languages": "Abyssal, Common, Draconic, Dwarvish, Elvish, Giant, Infernal, Primordial,\
  \ Undercommon"
"cr": "21"
"traits":
- "desc": "Rerak casts one of the following spells, requiring no material components\
    \ and using Intelligence as the spellcasting ability (spell save DC 22):\n\nAt\
    \ will: [Detect Magic](Mechanics/spells/detect-magic.md), [Fly](Mechanics/spells/fly.md),\
    \ [Mage Hand](Mechanics/spells/mage-hand.md), [Prestidigitation](Mechanics/spells/prestidigitation.md)\n\
    \n1/day each: [Globe of Invulnerability](Mechanics/spells/globe-of-invulnerability.md),\
    \ [Hold Monster](Mechanics/spells/hold-monster.md)\n\n3/day each: [Dispel\
    \ Magic](Mechanics/spells/dispel-magic.md), [Invisibility](Mechanics/spells/invisibility.md)\
    \ (self only)"
  "name": "Spellcasting"
- "desc": "If Rerak fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Rerak has advantage on saving throws against spells and magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Rerak makes two Death Rend attacks and uses Bloodcurdling Lament if available."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +14 to hit, reach 5 ft., one target. Hit: 23\
    \ (3d10 + 7) necrotic damage."
  "name": "Death Rend"
- "desc": "Rerak emits a hideous shriek charged with malignant energy. Each creature\
    \ within 30 feet of Rerak must succeed on a DC 22 Wisdom saving throw or have\
    \ the [frightened](Mechanics/Rules/conditions.md#Frightened) condition for 1 minute.\
    \ While [frightened](Mechanics/Rules/conditions.md#Frightened) in this way, a\
    \ creature also has the [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ condition. An affected creature can repeat the saving throw at the end of each\
    \ of its turns, ending the effect on itself on a success."
  "name": "Bloodcurdling Lament (Recharge 5-6)"
"bonus_actions":
- "desc": "Rerak targets one creature it can see within 120 feet of itself. The target\
    \ must make a DC 22 Charisma saving throw; if the target has the [unconscious](Mechanics/Rules/conditions.md#Unconscious)\
    \ condition, it has disadvantage on this saving throw. The target takes 21 (6d6)\
    \ force damage on a failed save or half as much damage on a successful one. Rerak\
    \ then regains a number of hit points equal to the amount of force damage taken.\n\
    \nIf this damage reduces the target to 0 hit points, the target immediately dies,\
    \ its body disappears, and its soul is trapped inside one of the soul gems within\
    \ Rerak's skull. After 24 hours, the gem transfers the soul to Rerak's creator.\n\
    \nWhen Rerak is reduced to 0 hit points, it is destroyed and disintegrates, leaving\
    \ behind the gems. Crushing a gem releases any souls trapped within, at which\
    \ point the soul's body re-forms in an unoccupied space nearest to the gem and\
    \ in the same state as it was when its soul was trapped."
  "name": "Soul Siphon"
"legendary_actions":
- "desc": "Rerak, along with anything it is wearing or carrying, teleports to an unoccupied\
    \ space it can see within 60 feet of itself. It then makes one Death Rend attack\
    \ if possible."
  "name": "Spiteful Teleport"
- "desc": "Rerak uses Spellcasting."
  "name": "Cast a Spell (Costs 2 Actions)"
"source":
- "VEoR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/VEoR/Rerak.webp"
```
^statblock