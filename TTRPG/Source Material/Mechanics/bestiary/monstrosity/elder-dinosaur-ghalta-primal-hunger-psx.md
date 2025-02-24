---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psx
- monster/cr/30
- monster/size/gargantuan
- monster/type/monstrosity/titan
statblock: inline
aliases: ["Elder Dinosaur (Ghalta, Primal Hunger)"]
---
# [Elder Dinosaur (Ghalta, Primal Hunger)](Mechanics\bestiary\monstrosity/elder-dinosaur-ghalta-primal-hunger-psx.md)
*Source: Plane Shift: Ixalan p. 34*  

The opening of Orazca, the golden city—which marks the turn between the Ixalan set and Rivals of Ixalan—reveals the existence of six huge and ancient elder dinosaurs, apparently preserved for centuries. Compared to their smaller cousins, they have less brightly-colored plumage and more grayish scales, but their feathers are a bright gold that matches the city around them. They are strong-willed and ferocious, and thus are hard to control. But the power of the Immortal Sun gives the Sun Empire warriors who wield it the ability to bring these elder dinosaurs under their command.

```statblock
"name": "Elder Dinosaur (Ghalta, Primal Hunger) (PSX)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Unaligned"
"ac": !!int "25"
"ac_class": "natural armor"
"hp": !!int "676"
"hit_dice": "33d20 + 330"
"stats":
- !!int "30"
- !!int "11"
- !!int "30"
- !!int "3"
- !!int "11"
- !!int "11"
"speed": "40 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "9"
  "Intelligence": !!int "5"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [frightened](Mechanics/Rules/conditions.md#Frightened),\
  \ [paralyzed](Mechanics/Rules/conditions.md#Paralyzed), [poisoned](Mechanics/Rules/conditions.md#Poisoned)"
"senses": "blindsight 120 ft., passive Perception 10"
"languages": ""
"cr": "30"
"traits":
- "desc": "If the elder dinosaur fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "The elder dinosaur has advantage on saving throws against spells and other\
    \ magical effects."
  "name": "Magic Resistance"
- "desc": "The elder dinosaur deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "These statistics are shared by all six elder dinosaurs: [Etali, Primal\
    \ Storm](Mechanics/bestiary/monstrosity/elder-dinosaur-etali-primal-storm-psx.md),\
    \ [Ghalta, Primal Hunger](Mechanics/bestiary/monstrosity/elder-dinosaur-ghalta-primal-hunger-psx.md),\
    \ [Nezahal, Primal Tide](Mechanics/bestiary/monstrosity/elder-dinosaur-nezahal-primal-tide-psx.md),\
    \ [Tetzimoc, Primal Death](Mechanics/bestiary/monstrosity/elder-dinosaur-tetzimoc-primal-death-psx.md),\
    \ [Zacama, Primal Calamity](Mechanics/bestiary/monstrosity/elder-dinosaur-zacama-primal-calamity-psx.md),\
    \ [Zetalpa, Primal Dawn](Mechanics/bestiary/monstrosity/elder-dinosaur-zetalpa-primal-dawn-psx.md)"
  "name": "Uniqueness"
"actions":
- "desc": "Each creature of the elder dinosaur's choice within 120 feet of it and\
    \ aware of it must succeed on a DC 17 Wisdom saving throw or become [frightened](Mechanics/Rules/conditions.md#Frightened)\
    \ for 1 minute. A creature can repeat the saving throw at the end of each of its\
    \ turns, with disadvantage if the elder dinosaur is within line of sight, ending\
    \ the effect on itself ona success. If a creature's saving throw is successful\
    \ or the effect ends for it, the creature is immune to the elder dinosaur's Frightful\
    \ Presence for the next 24 hours."
  "name": "Frightful Presence"
- "desc": "The elder dinosaur makes one bite attack against a Large or smaller creature\
    \ it is grappling. If the attack hits, that creature takes the bite's damage,\
    \ the target is swallowed, and the grapple ends. While swallowed, the creature\
    \ is [blinded](Mechanics/Rules/conditions.md#Blinded) and [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ it has total cover against attacks and other effects outside the elder dinosaur,\
    \ and it takes 56 (16d6) acid damage at the start of each of the elder dinosaur's\
    \ turns. If the elder dinosaur takes 60 damage or more on a single turn from a\
    \ creature inside it, it must succeed on a DC 20 Constitution saving throw at\
    \ the end of that turn or regurgitate all swallowed creatures, which fall [prone](Mechanics/Rules/conditions.md#Prone)\
    \ in a space within 10 feet of it. If the elder dinosaur dies, a swallowed creature\
    \ is no longer [restrained](Mechanics/Rules/conditions.md#Restrained) by it and\
    \ can escape from the corpse by using 20 feet of movement, exiting [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Swallow"
- "desc": "The elder dinosaur can use its Frightful Presence. It then makes three\
    \ attacks: one with its bite, one with its stomp, and one with its tail. It can\
    \ use its Swallow instead of its bite."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +19 to hit, reach 10 ft., one target. Hit: 62\
    \ (8d12 + 10) piercing damage. If the target is a creature, it is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 20). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and the elder dinosaur can't bite another target."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +19 to hit, reach 5 ft., one target. Hit: 46\
    \ (8d8 + 10) bludgeoning damage."
  "name": "Stomp"
- "desc": "Melee Weapon Attack: +19 to hit, reach 20 ft., one target. Hit: 38\
    \ (8d6 + 10) bludgeoning damage. If the target is a creature, it must succeed\
    \ on a DC 20 Strength saving throw or be knocked [prone](Mechanics/Rules/conditions.md#Prone)."
  "name": "Tail"
"legendary_actions":
- "desc": "The elder dinosaur makes one claw attack, tail attack, wing attack, or\
    \ flipper attack."
  "name": "Attack"
- "desc": "The elder dinosaur moves up to half its speed."
  "name": "Move"
- "desc": "The elder dinosaur makes one bite attack or uses its Swallow."
  "name": "Chomp (Costs 2 Actions)"
"source":
- "PSX"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSX/Elder%20Dinosaur%20%28Ghalta%2C%20Primal%20Hunger%29.webp"
```
^statblock