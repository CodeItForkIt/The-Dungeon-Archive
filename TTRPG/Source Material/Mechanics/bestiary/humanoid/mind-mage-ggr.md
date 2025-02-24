---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/5
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Mind Mage"]
---
# [Mind Mage](Mechanics\bestiary\humanoid/mind-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Dimir mind mages are among the most feared spellcasters in Ravnica, thanks in large part to the aura of mystery that shrouds them and their work. Their ability to read and alter memories commands respect from the other members of House Dimir and makes them useful in the full spectrum of the guild's activities. Many mind mages lead cells of their own.

```statblock
"name": "Mind Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "49"
"hit_dice": "11d8"
"stats":
- !!int "10"
- !!int "14"
- !!int "10"
- !!int "20"
- !!int "15"
- !!int "16"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "8"
"skillsaves":
  "Deception": !!int "6"
  "Insight": !!int "5"
  "Arcana": !!int "8"
  "Persuasion": !!int "6"
"senses": "passive Perception 12"
"languages": "Common plus any four languages"
"cr": "5"
"traits":
- "desc": "The mage's spellcasting ability is Intelligence (spell save DC 16). It\
    \ can innately cast the following spells, requiring no components:\n\nAt will:\
    \ [encode thoughts](Mechanics/spells/encode-thoughts-ggr.md) (see chapter 2),\
    \ [friends](Mechanics/spells/friends.md)\n\n1/day each: [dominate person](Mechanics/spells/dominate-person.md),\
    \ [mass suggestion](Mechanics/spells/mass-suggestion.md), [modify memory](Mechanics/spells/modify-memory.md)\n\
    \n3/day each: [charm person](Mechanics/spells/charm-person.md), [detect thoughts](Mechanics/spells/detect-thoughts.md),\
    \ [mage armor](Mechanics/spells/mage-armor.md), [sleep](Mechanics/spells/sleep.md),\
    \ [suggestion](Mechanics/spells/suggestion.md)"
  "name": "Innate Spellcasting (Psionics)"
- "desc": "The mage wears a [spies' murmur](Mechanics/items/spies-murmur-ggr.md) (see\
    \ chapter 5)."
  "name": "Special Equipment"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Mind%20Mage.webp"
```
^statblock