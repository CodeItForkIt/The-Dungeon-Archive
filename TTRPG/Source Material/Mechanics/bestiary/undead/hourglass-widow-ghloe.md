---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/20
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Hourglass Widow"]
---
# [Hourglass Widow](Mechanics\bestiary\undead/hourglass-widow-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 81*  

> [!quote]  
> 
> When the clock stops, your time has run out.

## Salvage

When the sand from the widow's hourglass is mixed with wine, it creates an elixir that when consumed prevents the creature from aging for `2d6 + 10` years. There is enough sand in the hourglass to create an elixir for two creatures. A creature cannot benefit from the sand of an hourglass widow more than once. The sand can be sold for 5,000 gp.

## Lore

- **DC 10 Intelligence ([Religion](Mechanics/Rules/skills.md#Religion)).** Hourglass widows are undead who can control time to act more than once a round.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Hourglass widows are resistant to cold, force, lightning, and necrotic. They are immune to poison and nonmagical attacks.  
- **DC 20 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** Inexplicably, an hourglass widow can affect those trapped in a time stop, imprisonment, or other stasis effect.  

```statblock
"name": "Hourglass Widow (GHLoE)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "18 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"stats":
- !!int "16"
- !!int "19"
- !!int "18"
- !!int "19"
- !!int "17"
- !!int "22"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "9"
  "Intelligence": !!int "10"
  "Strength": !!int "9"
  "Constitution": !!int "10"
"skillsaves":
  "Athletics": !!int "9"
  "Investigation": !!int "10"
  "Insight": !!int "9"
  "Perception": !!int "15"
  "Arcana": !!int "10"
"damage_resistances": "cold, force, lightning, necrotic"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "truesight 120 ft., passive Perception 25"
"languages": "the languages it knew in life"
"cr": "20"
"traits":
- "desc": "The widow's spellcasting ability is Charisma (spell save DC 20, +12 to\
    \ hit with spell attacks). It can innately cast the following spells, requiring\
    \ no material components:\n\nAt will: [eldritch blast](Mechanics/spells/eldritch-blast.md)\
    \ (four beams), [expeditious retreat](Mechanics/spells/expeditious-retreat.md)\
    \ , [mage armor](Mechanics/spells/mage-armor.md) , [mage hand](Mechanics/spells/mage-hand.md)\n\
    \n1/day each: [eyebite](Mechanics/spells/eyebite.md), [foresight](Mechanics/spells/foresight.md)\
    \ , [freedom of movement](Mechanics/spells/freedom-of-movement.md), [power word\
    \ stun](Mechanics/spells/power-word-stun.md), [teleport](Mechanics/spells/teleport.md),\
    \ [time stop](Mechanics/spells/time-stop.md), [wall of force](Mechanics/spells/wall-of-force.md)\n\
    \n3/day each: [blight](Mechanics/spells/blight.md), [disintegrate](Mechanics/spells/disintegrate.md),\
    \ [haste](Mechanics/spells/haste.md), [misty step](Mechanics/spells/misty-step.md),\
    \ [shield](Mechanics/spells/shield.md), [slow](Mechanics/spells/slow.md), [see\
    \ invisibility](Mechanics/spells/see-invisibility.md)\n\nThe widow casts these\
    \ spells before combat."
  "name": "Innate Spellcasting"
- "desc": "The widow takes one additional action."
  "name": "Accelerate Through Time (2/Day)"
- "desc": "The widow can choose to be unaffected by effects that modify time or change\
    \ its speed. The widow can affect others frozen in a time stop or other stasis-like\
    \ effects."
  "name": "Master of Time"
- "desc": "If the widow fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The widow regains 25 hit points at the start of its turn. If it takes fire\
    \ or radiant damage, this trait doesn't function at the start of the widow's next\
    \ turn. The widow's body is destroyed only if it starts its turn with 0 hit points\
    \ and doesn't regenerate."
  "name": "Regeneration"
- "desc": "The widow has advantage on saving throws against any effect that turns\
    \ undead."
  "name": "Turn Resistance"
"actions":
- "desc": "The widow uses disintegrating touch and withering gaze."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 16\
    \ (3d6 + 6) force damage and the target must succeed on a DC 20 Constitution\
    \ saving throw or have their speed decreased by 15 feet for 1 minute. The target\
    \ can repeat the saving throw at the end of each of its turns, ending the effect\
    \ on itself on a success. The effects are cumulative."
  "name": "Disintegrating Touch"
- "desc": "A creature within 30 feet that the widow can see suffers 21 (6d6) necrotic\
    \ damage."
  "name": "Withering Gaze"
"legendary_actions":
- "desc": "The widow casts [eldritch blast](Mechanics/spells/eldritch-blast.md)."
  "name": "Eldritch Blast"
- "desc": "The widow teleports to a space it can see within 30 feet and uses disintegrating\
    \ touch before or after it teleports."
  "name": "Sudden Rush (2 Actions)"
- "desc": "All creatures within 20 ft. of the widow must succeed on a DC 20 Constitution\
    \ saving throw or be [paralyzed](Mechanics/Rules/conditions.md#Paralyzed) until\
    \ the end of the creature's next turn."
  "name": "Frozen in Time (3 Actions)"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Hourglass%20Widow.webp"
```
^statblock