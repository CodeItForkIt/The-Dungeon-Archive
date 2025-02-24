---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tob1-2023
- monster/cr/4
- monster/environment/underdark
- monster/size/large
- monster/type/plant
statblock: inline
aliases: ["Cavelight Moss"]
---
# [Cavelight Moss](Mechanics\bestiary\plant/cavelight-moss-tob1-2023.md)
*Source: Tome of Beasts 1 (2023 Edition) p. 52*  

*These patches of tangled, lacy moss cling to the ceiling, slowly pulsing with an eerie glow. Their stems gently writhe among the soft, feathery mass, dusting the ground below with a twinkling of phosphorescent spores.*

## Plant Carnivore

Cavelight moss glows with a pale, yellow light, but when agitated, its light changes to an icy blue. Cavelight moss is frequently mistaken for a benign organism, but it hunts living flesh and renders its meals immobile before starting the long process of digestion. A cavelight moss is a collective of smaller life forms patched together and sharing sensations. Barely cognitive, a cavelight moss spends its time positioning itself above well‑traveled sections of cavern, feeding on rats, bats, and crawling insects. When it senses larger prey, it slowly and quietly moves toward the creature.

## Long-Lived Spores

A cavelight moss can survive for 200 years, shedding luminous spores and consuming vermin. Its spores germinate in the carcasses of its victims, and in lean times, these spores can grow slowly on guano or other areas rich in moisture and organic nutrients.

## Rare Colonies

If a cave system has no true protectors and food is plentiful, these creatures congregate—most commonly, in bat colonies of millions of individuals. When they gather this way, cavelight mosses function as a large colony, covering strategic locations where prey roams. When a source of food moves on, the entire colony slowly disperses as well.

```statblock
"name": "Cavelight Moss (ToB1-2023)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "95"
"hit_dice": "10d10 + 40"
"stats":
- !!int "20"
- !!int "10"
- !!int "18"
- !!int "1"
- !!int "13"
- !!int "5"
"speed": "5 ft., climb 15 ft."
"damage_resistances": "slashing, acid, cold, fire from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [deafened](Mechanics/Rules/conditions.md#Deafened),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened), [paralyzed](Mechanics/Rules/conditions.md#Paralyzed),\
  \ [prone](Mechanics/Rules/conditions.md#Prone), [stunned](Mechanics/Rules/conditions.md#Stunned),\
  \ [unconscious](Mechanics/Rules/conditions.md#Unconscious)"
"senses": "tremorsense 60 ft., passive Perception 11"
"languages": ""
"cr": "4"
"traits":
- "desc": "The cavelight moss sheds bright light in a 5- to 20-foot radius and dim\
    \ light for an additional number of feet equal to the chosen radius. The moss\
    \ can alter the radius as a bonus action."
  "name": "Variable Illumination"
"actions":
- "desc": "The cavelight moss makes two Tendrils attacks. If both attacks hit a Large\
    \ or smaller creature, the target is [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ (escape DC 15). Until this grapple ends, the target is [restrained](Mechanics/Rules/conditions.md#Restrained),\
    \ and at the start of each of the target's turns, it must succeed on a DC 15 Constitution\
    \ saving throw or suffer one level of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion).\
    \ The cavelight moss then gains 5 temporary hp. A creature that succeeds on the\
    \ saving throw can't suffer further levels of [exhaustion](Mechanics/Rules/conditions.md#Exhaustion)\
    \ from the cavelight moss's grapple for the next 24 hours. The cavelight moss\
    \ can have only one creature [grappled](Mechanics/Rules/conditions.md#Grappled)\
    \ at a time."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 16\
    \ (2d10 + 5) bludgeoning damage."
  "name": "Tendrils"
"source":
- "ToB1-2023"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/ToB1-2023/Cavelight%20Moss.webp"
```
^statblock

## Environment

underdark