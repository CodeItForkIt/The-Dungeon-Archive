---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/15
- monster/size/medium
- monster/type/fiend
statblock: inline
aliases: ["Doomcaller"]
---
# [Doomcaller](Mechanics\bestiary\fiend/doomcaller-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 47*  

> [!quote]  
> 
> Despair, the end is nigh!

## Salvage

When slain, the eyes of a doomcaller harden into gems worth 2000 gp each.

When a creature holding one of these gems makes an attack roll, ability check, or saving throw, they can consume it to improve their fortunes. After the roll has been made, but before the GM has announced the result of the roll, the player can expend one gem and reroll the roll. Once done, the player must use the new result, the gem shatters and becomes worthless.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Doomcallers are powerful spellcasting fiends.  
- **DC 15 Intelligence ([History](Mechanics/Rules/skills.md#History)).** A doomcaller can summon succubi or barbed devils.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Doomcallers are resistant to cold, fire, lightning, and nonmagical weapons. They are immune to acid and poison.  

```statblock
"name": "Doomcaller (GHLoE)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "20d8 + 60"
"stats":
- !!int "8"
- !!int "17"
- !!int "17"
- !!int "14"
- !!int "12"
- !!int "21"
"speed": "30 ft., fly 40 ft. (hover)"
"saves":
  "Charisma": !!int "10"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
  "Constitution": !!int "8"
"skillsaves":
  "Deception": !!int "10"
  "Religion": !!int "7"
  "Insight": !!int "6"
  "Perception": !!int "6"
  "Arcana": !!int "7"
  "Persuasion": !!int "10"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "all"
"cr": "15"
"traits":
- "desc": "The doomcaller is an 18th-level spellcaster. Its spellcasting ability is\
    \ Charisma (spell save DC 18, +10 to hit with spell attacks). It has the following\
    \ spells prepared:\n\nCantrips (at will): [fire bolt](Mechanics/spells/fire-bolt.md),\
    \ [hunter sense](Mechanics/spells/hunter-sense-ghloe.md), [message](Mechanics/spells/message.md),\
    \ [shocking grasp](Mechanics/spells/shocking-grasp.md), [true strike](Mechanics/spells/true-strike.md)\n\
    \n1st level (4 slots): [detect magic](Mechanics/spells/detect-magic.md), [magic\
    \ missile](Mechanics/spells/magic-missile.md), [shield](Mechanics/spells/shield.md)\n\
    \n2nd level (3 slots): [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [misty step](Mechanics/spells/misty-step.md)\n\n3rd level (3 slots): [bestow\
    \ curse](Mechanics/spells/bestow-curse.md), [fireball](Mechanics/spells/fireball.md)\n\
    \n4th level (3 slots): [banishment](Mechanics/spells/banishment.md), [consume\
    \ mind](Mechanics/spells/consume-mind-ghloe.md)\n\n5th level (3 slots): [magic\
    \ mirror](Mechanics/spells/magic-mirror-ghloe.md), [scrying](Mechanics/spells/scrying.md)\n\
    \n6th level (1 slots): [disintegrate](Mechanics/spells/disintegrate.md)\n\n\
    7th level (1 slots): [arboreal curse](Mechanics/spells/arboreal-curse-ghloe.md)\n\
    \n8th level (1 slots): [mind blank](Mechanics/spells/mind-blank.md) \n\n\
    9th level (1 slots): [gate](Mechanics/spells/gate.md)\n\nThe doomcaller casts\
    \ this spell on itself before combat."
  "name": "Spellcasting"
- "desc": "The doomcaller has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) bludgeoning damage, and the target has disadvantage on their next\
    \ attack roll. Additionally, all attacks against the target by allies of the doomcaller\
    \ are made with advantage until the start of the doomcaller's next turn."
  "name": "Slam"
- "desc": "The doomcaller chooses what to summon and attempts a magical summoning.\
    \ A doomcaller has a 60 percent chance of summoning 1d6 succubi or 1d4 barbed\
    \ devils. A summoned fiend appears in an unoccupied space within 60 feet of its\
    \ summoner, does as it pleases, and can't summon other fiends. The summoned fiend\
    \ remains for 1 minute, until it or its summoner dies, or until its summoner takes\
    \ a bonus action to dismiss it."
  "name": "Summon Fiend (1/Day)"
"reactions":
- "desc": "When a creature the doomcaller can see makes an attack roll, a saving throw,\
    \ or an ability check, the doomcaller can roll a d20 and choose to use this\
    \ roll in place of the attack roll, saving throw, or ability check."
  "name": "Ill Fortune (3/Day)"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Doomcaller.webp"
```
^statblock