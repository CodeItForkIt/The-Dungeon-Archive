---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ghloe
- monster/cr/0
- monster/size/tiny
- monster/type/aberration
statblock: inline
aliases: ["Spythronar Sac"]
---
# [Spythronar Sac](Mechanics\bestiary\aberration/spythronar-sac-ghloe.md)
*Source: Grim Hollow: Lairs of Etharis p. 31*  

> [!quote]  
> 
> Armored corpses in the cavern, resting among thick strands of webbing, have sparks of lightning playing off them.

## Salvage

Spythronar silk is prized, although it's worthless if acid or fire touched the web. One web can be used to make silk rope or fine clothing. A proficient alchemist can use the same amount of silk to produce a [potion of lightning resistance](Mechanics/items/potion-of-lightning-resistance.md) or a dose of an oil that allows a metal weapon to deal `1d6` extra lightning damage for 1 hour. Producing either concoction takes 4 hours of work and a successful DC 13 Intelligence check.

A proficient weaver can turn three spythronar webs into a rope of entanglement or 10 webs into leather armor of lightning resistance. Doing either requires other materials worth 500 gp, 5 days of work, and a successful DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)) check.

## Lore

- **DC 10 Intelligence ([Nature](Mechanics/Rules/skills.md#Nature)).** Spythronar swarms can weave dangerous webbing, making egg sacs quickly. It takes them some time to weave a sentient web.  
- **DC 15 Intelligence ([Arcana](Mechanics/Rules/skills.md#Arcana)).** The sentient spythronar webs adhere to you if you touch them, and they charge their silken strands with lightning. Crushing spythronar egg sacs sets off a lightning discharge, but hitting them with lightning releases a new spythronar swarm.  

```statblock
"name": "Spythronar Sac (GHLoE)"
"size": "Tiny"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "5"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "1"
- !!int "1"
- !!int "8"
- !!int "1"
- !!int "3"
- !!int "1"
"speed": "0 ft."
"condition_immunities": "[blinded](Mechanics/Rules/conditions.md#Blinded), [charmed](Mechanics/Rules/conditions.md#Charmed),\
  \ [deafened](Mechanics/Rules/conditions.md#Deafened), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [restrained](Mechanics/Rules/conditions.md#Restrained),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "tremorsense (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "0"
"traits":
- "desc": "The spythronar sac appears to be a tangled ball of string, twigs, and dirt.\
    \ Someone who can see the sac can identify it with a successful DC 15 Intelligence\
    \ ([Arcana](Mechanics/Rules/skills.md#Arcana) or [Nature](Mechanics/Rules/skills.md#Nature))\
    \ check."
  "name": "False Appearance"
- "desc": "A creature who enters the spythronar sac's space must succeed on a DC 10\
    \ Dexterity saving throw, or the sac is destroyed."
  "name": "Fragile"
- "desc": "When the spythronar sac is destroyed, it releases lightning in a 10-foot\
    \ radius. A creature who destroyed the sac by entering its space receives no saving\
    \ throw. Other creatures in that area must succeed on a DC 10 Dexterity saving\
    \ throw or take 4 (1d8) lightning damage. Each spythronar swarm and web in this\
    \ area instead gains advantage on its next attack roll."
  "name": "Lightning Release"
- "desc": "When a spythronar sac takes lightning damage from a source other than another\
    \ spythronar, it hatches, transforming into a spythronar swarm with half the normal\
    \ hit points. This swarm rolls initiative and enters the combat."
  "name": "Shocking Birth"
"source":
- "GHLoE"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/GHLoE/Spythronar%20Sac.webp"
```
^statblock