---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/9
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Harvester of Lies"]
---
# [Harvester of Lies](Mechanics\bestiary\undead/harvester-of-lies-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 13*  

> [!quote]  
> 
> Don't lie to me, or the harvester will steal your tongue!

## Salvage

If defeated, the harvester's [coat of lies](Mechanics/items/coat-of-lies-ghloe.md) (see Appendix A of Lairs of Etharis) can be claimed.

## Lore

- **DC 10 Intelligence ([History](Mechanics/Rules/skills.md#History)).** Harvesters of lies can detect when a lie is uttered from 1 mile away. They are attracted to lies, the more frequent the lies and the more outlandish, the greater the attraction.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Harvesters are resistant to nonmagical weapons and necrotic damage, and immune to poison.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The harvester wears a coat made of the severed tongues of its victims that allow it to cast several spells.  

```statblock
"name": "Harvester of Lies (GHLoE)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "coat of lies"
"hp": !!int "91"
"hit_dice": "14d8 + 28"
"stats":
- !!int "13"
- !!int "20"
- !!int "14"
- !!int "11"
- !!int "16"
- !!int "15"
"speed": "40 ft."
"saves":
  "Charisma": !!int "6"
  "Dexterity": !!int "9"
  "Wisdom": !!int "7"
"skillsaves":
  "Stealth": !!int "13"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Acrobatics": !!int "9"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "the languages it knew in life"
"cr": "9"
"traits":
- "desc": "The harvester's spellcasting ability is Charisma (spell save DC 14). It\
    \ can innately cast the following spells, requiring only that the harvester be\
    \ wearing its coat of lies:\n\nAt will: [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [zone of truth](Mechanics/spells/zone-of-truth.md)\n\n1/day each: [levitate](Mechanics/spells/levitate.md),\
    \ [tongues](Mechanics/spells/tongues.md)\n\n3/day each: [hold person](Mechanics/spells/hold-person.md),\
    \ [invisibility](Mechanics/spells/invisibility.md), [misty step](Mechanics/spells/misty-step.md),\
    \ [silence](Mechanics/spells/silence.md)"
  "name": "Innate Spellcasting"
- "desc": "While wearing their specially prepared coat, the harvester's AC is increase\
    \ by 2 and it can use its innate spellcasting."
  "name": "Coat of Lies"
- "desc": "The harvester hears all lies uttered within 1 mile of it and knows the\
    \ liar's distance and direction while the harvester choses to concentrate."
  "name": "Hear Lies"
- "desc": "The harvester can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "The harvester leaves no tracks to indicate where it has been or where it's\
    \ headed."
  "name": "Trackless"
"actions":
- "desc": "The harvester makes three attacks, only one of which can be sever tongue."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage. If the target is Medium or smaller, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 17)."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one humanoid [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ by the harvester of lies. Hit: 33 (8d6 + 5) slashing damage and the target\
    \ must succeed on a DC 17 Constitution saving throw or have their tongue ripped\
    \ out. A creature without a tongue cannot speak or cast spells with verbal components.\
    \ A creature is immune to this effect if it is immune to slashing damage, doesn't\
    \ have or need a tongue, or has legendary actions.\n\nA tongue can be reattached\
    \ within 1 hour of being severed with a successful DC 10 Wisdom ([Medicine](Mechanics/Rules/skills.md#Medicine))\
    \ check, or at can be regrown using magic that replaces lost limbs."
  "name": "Sever Tongue"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Harvester%20of%20Lies.webp"
```
^statblock