---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/11
- monster/size/medium
- monster/type/fiend
statblock: inline
aliases: ["Candlelight Daemon"]
---
# [Candlelight Daemon](Mechanics\bestiary\fiend/candlelight-daemon-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 25*  

> [!quote]  
> 
> A candlelight daemon remains for the duration of a cursed candle's flame. That's long enough for a host of sinister deeds.

## Salvage

The melted leavings of a candlelight daemon's candle act as oil of sharpness against aberrations, celestials, fey, and fiends, as well as against the creature that created the candle.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Candlelight daemons return to the Netherworld if their candle goes out.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Candlelight daemons have immunities and resistances typical of fiends, including immunity to poison and resistance to cold, fire, lightning, and nonmagical weapon attacks. The daemon is also resistant to magic and capable of countering spells.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** A candlelight daemon is most effective in shadows or darkness, which allow the fiend to hide easily and bring its murderous talents to bear.  

```statblock
"name": "Candlelight Daemon (GHLoE)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"stats":
- !!int "16"
- !!int "17"
- !!int "18"
- !!int "12"
- !!int "14"
- !!int "17"
"speed": "50 ft., fly 50 ft."
"skillsaves":
  "Deception": !!int "7"
  "Stealth": !!int "7"
  "Investigation": !!int "5"
  "Insight": !!int "6"
  "Perception": !!int "6"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Infernal"
"cr": "11"
"traits":
- "desc": "The daemon's spellcasting ability is Charisma (spell save DC 15, +7 to\
    \ hit with spell attacks). The daemon can innately cast the following spells,\
    \ requiring no components:\n\nAt will: [detect magic](Mechanics/spells/detect-magic.md),\
    \ [hunter sense](Mechanics/spells/hunter-sense-ghloe.md), [knock](Mechanics/spells/knock.md)\n\
    \n1/day each: [counterspell](Mechanics/spells/counterspell.md), [darkness](Mechanics/spells/darkness.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [shield](Mechanics/spells/shield.md),\
    \ [suffocate](Mechanics/spells/suffocate-ghloe.md)"
  "name": "Innate Spellcasting"
- "desc": "The daemon remains on the Material Plane only while the candle that summoned\
    \ it burns."
  "name": "Candle Dependence"
- "desc": "The daemon has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "As its movement for its turn, the candlelight daemon can teleport to an\
    \ unoccupied space within 30 feet of it, provided the space it's teleporting to\
    \ and from are both in dim light or darkness. The daemon doesn't need to see the\
    \ destination."
  "name": "Nether Step"
- "desc": "While in dim light or darkness, the daemon can take the Hide action as\
    \ a bonus action."
  "name": "Shadow Stealth"
- "desc": "The candlelight daemon has advantage on attack rolls against any creature\
    \ that hasn't had a turn in combat."
  "name": "Slayer's Advantage"
- "desc": "The candlelight daemon deals an extra 35 10d6 damage when it hits a target\
    \ with an attack and has advantage on the attack roll. With the [suffocate](Mechanics/spells/suffocate-ghloe.md)\
    \ spell, the daemon deals this damage as extra bludgeoning damage."
  "name": "Slayer's Attack (1/Turn)"
"actions":
- "desc": "The daemon makes two claw attacks and one gore attack. It can use hurl\
    \ fire in place of any of these attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10\
    \ (2d6 + 3) slashing damage and 4 (1d8) fire damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d8 + 3) piercing damage and 4 (1d8) fire damage."
  "name": "Gore"
- "desc": "Ranged Spell Attack: +7 to hit, range 120 ft., one target. Hit: 13\
    \ (3d8) fire damage."
  "name": "Hurl Fire"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Candlelight%20Daemon.webp"
```
^statblock