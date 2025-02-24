---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/1-4
- monster/environment/badlands
- monster/environment/desert
- monster/size/small
- monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Dust Goblin"]
---
# [Dust Goblin](Mechanics\bestiary\humanoid/dust-goblin-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 215*  

*A ragged creature emerges from the sand. Its spindly frame is encased in a hodge-podge of armor scraps and rusted weapons. A long, hooked nose protrudes over a wide mouth filled with sharp teeth*.

Dust goblins vary greatly in size and appearance, although they are universally scrawny, bony, and lanky. They seem to suffer from malnutrition even when in perfect health, a perception reinforced by the way their bellies distend after they've gorged themselves on flesh. Their skin is always dry and cracked, ranging from dusky gray to dark green in color.

## Rule the Wastelands

Dust goblins are twisted creatures, tainted by many generations of life in a blasted wasteland. After a magical war devastated the dust goblins' homeland, they rose to become the most dominant inhabitants. They inhabit ancient ruins and ambush travelers who stray too close to their borders.

## Twisted Minds

The lingering magical energy saturating the wastes of their home, coupled with the harsh conditions in which they scratch out a living, have tainted the minds of all dust goblins. Their thinking is alien and unfathomable to most creatures. Whereas most goblins are cowardly, dust goblins don't seem to experience fear. To the contrary, they enjoy wearing skull helmets and using ghostly whistles to frighten foes. Owing to this alien mindset, dust goblins get along disturbingly well with Aberrations. The creatures often forge alliances and work together for mutual benefit, while making their unnerving mark on communal lairs.

```statblock
"name": "Dust Goblin (ToB1-2023)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[leather armor](Mechanics/items/leather-armor.md)"
"hp": !!int "16"
"hit_dice": "3d6 + 6"
"stats":
- !!int "8"
- !!int "16"
- !!int "14"
- !!int "10"
- !!int "8"
- !!int "8"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "7"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1/4"
"traits":
- "desc": "When the dust goblin attacks a creature from hiding, the target must succeed\
    \ on a DC 10 Wisdom saving throw or be [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ until the end of its next turn."
  "name": "Twisted"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
    \ 7 (1d8 + 3) piercing damage."
  "name": "Light Crossbow"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Dust%20Goblin.webp"
```
^statblock

## Environment

badlands, desert