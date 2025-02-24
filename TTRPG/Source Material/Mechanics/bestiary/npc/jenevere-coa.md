---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/coa
- monster/cr/17
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Jenevere"]
---
# [Jenevere](Mechanics\bestiary\npc/jenevere-coa.md)
*Source: Chains of Asmodeus p. 264*  

It was Jenevere's role to watch the mortal planes for individuals of particular virtue. Forbidden to intervene, she would record their struggles and deeds, to be brought in evidence when their souls migrated to their final reward. After centuries of meek observation, she petitioned for more active divine involvement in the fates of those she watched. She was refused. It was too much for her. Against the strictures of her role, she visited the mortal realms to interfere. No grand drawing of flaming swords, just calm words, a timely reminder of morality at the fulcrum point of someone's moral struggle. In time, the Nine Hells became aware of her influence and set a trap for her. After her capture she passed through various hands. Jenevere isn't fierce and combative, but open, honest, and infinitely merciful. She forgives the Fiends that torment her, knowing it is their nature, and her forgiveness burns them more than they can burn her. Possession of Jenevere became something of a poisoned chalice, so that she fell through their hierarchy, possessed by meaner and meaner masters, until she was acquired by Vaness and Fling of the Eye Market.

Jenevere's eyes are remarkable things, fashioned by gods to see all the virtues of the mortal realms. Vaness and Fling removed her eyes easily enough, but implanting them into a Fiend, or any of the evil things that come cap in hand to them, proved problematic. The eyes are a gateway to all the virtue and goodness of the planes. To Vaness and Fling's patrons, the experience proved unendurable. Vaness and Fling continue to experiment, but they're beginning to feel that in acquiring Jenevere they've taken on more than they can handle.

```statblock
"name": "Jenevere (CoA)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "216"
"hit_dice": "16d10 + 128"
"stats":
- !!int "18"
- !!int "22"
- !!int "26"
- !!int "18"
- !!int "20"
- !!int "24"
"speed": "40 ft., fly 120 ft."
"saves":
  "Charisma": !!int "13"
  "Wisdom": !!int "11"
  "Intelligence": !!int "10"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "17"
"traits":
- "desc": "Jenevere casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 21):\n\nAt will:\
    \ [Bless](Mechanics/spells/bless.md), [Detect Evil and Good](Mechanics/spells/detect-evil-and-good.md)\n\
    \n1/day: [Foresight](Mechanics/spells/foresight.md)\n\n2/day each: [Commune](Mechanics/spells/commune.md),\
    \ [Heal](Mechanics/spells/heal.md), [Legend Lore](Mechanics/spells/legend-lore.md),\
    \ [Raise Dead](Mechanics/spells/raise-dead.md), [Scrying](Mechanics/spells/scrying.md)"
  "name": "Spellcasting"
- "desc": "Jenevere has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Jenevere makes three Radiant Touch attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 33\
    \ (6d8 + 6) radiant damage."
  "name": "Radiant Touch"
- "desc": "Jenevere selects a target within 10 feet. The target is freed from any\
    \ curse, disease, poison, blindness, or deafness. If the target is a Fiend, it\
    \ must succeed on a DC 21 saving throw or have disadvantage on all attack rolls\
    \ for 24 hours."
  "name": "Forgiveness (2/Day)"
"source":
- "CoA"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/CoA/Jenevere.webp"
```
^statblock