---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/10
- monster/size/large
- monster/type/construct
statblock: inline
aliases: ["Stone Guardian (Stone Golem)"]
---
# [Stone Guardian (Stone Golem)](Mechanics\bestiary\construct/stone-guardian-stone-golem-psx.md)
*Source: Plane Shift: Ixalan p. 40*  

Through the years in which the Sun Empire was ruled from Orazca, its priests crafted huge stone guardians to protect the empire's cities and temples. The incredible magic of the Immortal Sun gave a semblance of life to these artificial creatures, endowing them with the ability to move their stone bodies, a keen awareness of their surroundings, and a limited ability to think and reason in order to help them carry out their orders. These stone guardians were tasked with standing watch—constantly alert, vigilant to any danger, never sleeping, and unswerving in their duty.

Most stone guardians are inactive now. In ancient ruins lying far from the old capital, the magic that gave them life has faded over the centuries. Even within the golden city, many of them have become inert, and those who seek to explore Orazca or other ancient ruins must be on constant guard. Any carved figure or statue might well be a stone guardian whose magic has failed. But it might also be a guardian that is simply waiting for a threat before it activates and drives that threat away.

Constructs such as [animated armor](Mechanics/bestiary/construct/animated-armor.md), [helmed horrors](Mechanics/bestiary/construct/helmed-horror.md), [shield guardians](Mechanics/bestiary/construct/shield-guardian.md), and [stone golems](Mechanics/bestiary/construct/stone-golem.md) can represent these guardians.

```statblock
"name": "Stone Guardian (Stone Golem) (PSX)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"stats":
- !!int "22"
- !!int "9"
- !!int "20"
- !!int "3"
- !!int "11"
- !!int "1"
"speed": "30 ft."
"damage_immunities": "poison; psychic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't adamantine"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [petrified](Mechanics/Rules/conditions.md#Petrified), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "10"
"traits":
- "desc": "The stone guardian is immune to any spell or effect that would alter its\
    \ form."
  "name": "Immutable Form"
- "desc": "The stone guardian has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The stone guardian's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The stone guardian makes two slam attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 5 ft., one target. Hit: 19\
    \ (3d8 + 6) bludgeoning damage."
  "name": "Slam"
- "desc": "The stone guardian targets one or more creatures it can see within 10 feet\
    \ of it. Each target must make a DC 17 Wisdom saving throw against this magic.\
    \ On a failed save, a target can't use reactions, its speed is halved, and it\
    \ can't make more than one attack on its turn. In addition, the target can take\
    \ either an action or a bonus action on its turn, not both. These effects last\
    \ for 1 minute. A target can repeat the saving throw at the end of each of its\
    \ turns, ending the effect on itself on a success."
  "name": "Slow (Recharge 5-6)"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Stone%20Guardian%20%28Stone%20Golem%29.webp"
```
^statblock