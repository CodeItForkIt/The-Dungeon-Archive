---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/1-4
- monster/size/small
- monster/type/construct
statblock: inline
aliases: ["Servitor Thrull"]
---
# [Servitor Thrull](Mechanics\bestiary\construct/servitor-thrull-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 221*  

The most wretched of thrulls are the servitors, small and slender, that serve as playthings for their Orzhov masters. They run trivial errands, transport small items, caper and dance, and keep their masters' expensive robes from trailing on the dirty street. They are utterly loyal, lacking any concept of thinking for themselves.

## Thrulls

When the Orzhov Syndicate rips a soul from its body to create a spirit, the cast-off remains go to the fleshmages, who use their necromantic magic to liquefy the corpse and transform it into something useful. These creations become thrulls, obedient slaves that serve in a variety of menial roles: laborers, messengers, beasts of burden, and even fashion accessories for the elite. Whatever tasks they perform, they wear faceplates forged from devalued coinage to conceal their ghastly features.

### Construct Nature

A thrull doesn't require air, food, drink, or sleep.

```statblock
"name": "Servitor Thrull (GGR)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "22"
"hit_dice": "4d6 + 8"
"stats":
- !!int "11"
- !!int "13"
- !!int "14"
- !!int "6"
- !!int "6"
- !!int "3"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 8"
"languages": "understands Common but can't speak"
"cr": "1/4"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8\
    \ + 1) slashing damage."
  "name": "Claws"
"reactions":
- "desc": "When a creature within 5 feet of the thrull is hit by an attack, the thrull\
    \ swaps places with that creature and is hit instead."
  "name": "Self-Sacrifice"
"source":
- "GGR"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GGR/Servitor%20Thrull.webp"
```
^statblock