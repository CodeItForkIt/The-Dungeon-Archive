---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Counterflux Blastseeker"]
---
# [Counterflux Blastseeker](Mechanics\bestiary\humanoid/counterflux-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Counterflux Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "16 with [mage armor](Mechanics/spells/mage-armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "13"
- !!int "16"
- !!int "15"
- !!int "18"
- !!int "11"
- !!int "14"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "2"
  "Constitution": !!int "4"
"skillsaves":
  "Perception": !!int "2"
  "Arcana": !!int "6"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "2"
"traits":
- "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell save\
    \ DC 14, +6 to hit with spell attacks). The blastseeker can innately cast the\
    \ following spells, requiring no components other than its Izzet gear, which doesn't\
    \ function for others:\n\n1/day each: [counterspell](Mechanics/spells/counterspell.md),\
    \ [dispel magic](Mechanics/spells/dispel-magic.md), [protection from energy](Mechanics/spells/protection-from-energy.md)\n\
    \n3/day each: [enlarge/reduce](Mechanics/spells/enlarge-reduce.md), [mage\
    \ armor](Mechanics/spells/mage-armor.md) (self only), [scorching ray](Mechanics/spells/scorching-ray.md)"
  "name": "Innate Spellcasting"
- "desc": "The blastseeker can create an additional effect immediately after casting\
    \ a spell. Roll a d6 to determine the effect:\n\n- 1–3.. The blastseeker\
    \ creates a 15-foot-radius [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ sphere centered on itself that lasts until the end of its next turn. Creatures\
    \ in the sphere have disadvantage on saving throws against spells and other magical\
    \ effects.  \n- 4–6.. The blastseeker creates a 15-foot-radius [invisible](Mechanics/Rules/conditions.md#Invisible)\
    \ sphere centered on itself that lasts until the end of its next turn. Creatures\
    \ in the sphere have advantage on saving throws against spells and other magical\
    \ effects.  "
  "name": "Counterflux Overcast (Recharge 5-6)"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Rapier"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Counterflux%20Blastseeker.webp"
```
^statblock