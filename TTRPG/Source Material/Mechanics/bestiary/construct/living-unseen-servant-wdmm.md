---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/wdmm
- monster/cr/0
- monster/size/medium
- monster/type/construct
statblock: inline
aliases: ["Living Unseen Servant"]
---
# [Living Unseen Servant](Mechanics\bestiary\construct/living-unseen-servant-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 313*  

## Living Spell

Areas of wild magic and sites that have been ravaged by powerful eldritch forces can give rise to spell effects that refuse to dissipate. These so-called living spells haunt the places where they were created, subsisting on ambient magical energy.

A living spell appears much like a normal spell effect, except that its magical energy lingers and moves with purpose.

### Constructed Nature

A living spell doesn't require air, food, drink, or sleep.

### Magical Essence

The process that creates a living spell changes the nature of its magic. A living spell isn't subject to [dispel magic](Mechanics/spells/dispel-magic.md) and isn't affected by an [antimagic field](Mechanics/spells/antimagic-field.md).

Like an overzealous butler or maid, a living [unseen servant](Mechanics/spells/unseen-servant.md) spell busies itself with tasks in hopes of pleasing its creator. It can wield simple weapons but prefers not to. [See invisibility](Mechanics/spells/see-invisibility.md), [true seeing](Mechanics/spells/true-seeing.md), and similar effects reveal that the servant has a shape similar to that of a slender humanoid adult.

```statblock
"name": "Living Unseen Servant (WDMM)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "2"
- !!int "10"
- !!int "11"
- !!int "1"
- !!int "10"
- !!int "1"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Mechanics/Rules/conditions.md#Exhaustion), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 12"
"languages": "understands one language (usually Common) but can't speak"
"cr": "0"
"traits":
- "desc": "The unseen servant is [invisible](Mechanics/Rules/conditions.md#Invisible)."
  "name": "Invisibility"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 1 bludgeoning\
    \ damage."
  "name": "Slam"
"source":
- "WDMM"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/WDMM/Living%20Unseen%20Servant.webp"
```
^statblock