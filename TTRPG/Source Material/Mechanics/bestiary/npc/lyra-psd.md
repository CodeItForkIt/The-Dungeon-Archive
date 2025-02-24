---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/psd
- monster/cr/16
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Lyra"]
---
# [Lyra](Mechanics\bestiary\npc/lyra-psd.md)
*Source: Plane Shift: Dominaria p. 9*  

The most visible and recognized symbols of the Church of Serra are her angels—both those that were personally created by Serra and those that appeared spontaneously in the Cathedral at Sursi. Some angels live contemplative lives within the cathedrals, but most are active defenders of the faith, protecting Serra's people across the world. Powerful angels often take responsibility for large regions of the world. Lyra, for example, stands as the protector of Benalia, and Shalai plays a similar role in Llanowar. Serra's angels are believed to hear prayers addressed to Serra, and they have an uncanny tendency to arrive exactly when they are needed.

Any of the angels in the "Monster Manual" can serve as [Serra angels](Mechanics/bestiary/celestial/serra-angel-psd.md). The [deva](Mechanics/bestiary/celestial/deva.md) represents the most common angels, while the [planetar](Mechanics/bestiary/celestial/planetar.md) and [solar](Mechanics/bestiary/celestial/solar.md) are appropriate for powerful angels such as [Lyra](Mechanics/bestiary/npc/lyra-psd.md) and [Shalai](Mechanics/bestiary/npc/shalai-psd.md).

```statblock
"name": "Lyra (PSD)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"stats":
- !!int "24"
- !!int "20"
- !!int "24"
- !!int "19"
- !!int "22"
- !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  "Charisma": !!int "12"
  "Wisdom": !!int "11"
  "Constitution": !!int "12"
"skillsaves":
  "Perception": !!int "11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](Mechanics/Rules/conditions.md#Charmed), [exhaustion](Mechanics/Rules/conditions.md#Exhaustion),\
  \ [frightened](Mechanics/Rules/conditions.md#Frightened)"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Lyra's spellcasting ability is Charisma (spell save DC 20). Lyra can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [detect evil and good](Mechanics/spells/detect-evil-and-good.md), [invisibility](Mechanics/spells/invisibility.md)\
    \ (self only)\n\n1/day each: [commune](Mechanics/spells/commune.md), [control\
    \ weather](Mechanics/spells/control-weather.md), [insect plague](Mechanics/spells/insect-plague.md)\n\
    \n3/day each: [blade barrier](Mechanics/spells/blade-barrier.md), [dispel\
    \ evil and good](Mechanics/spells/dispel-evil-and-good.md), [flame strike](Mechanics/spells/flame-strike.md),\
    \ [raise dead](Mechanics/spells/raise-dead.md)"
  "name": "Innate Spellcasting"
- "desc": "Lyra's weapon attacks are magical. When Lyra hits with any weapon, the\
    \ weapon deals an extra 5d8 radiant damage (included in the attack)."
  "name": "Angelic Weapons"
- "desc": "Lyra knows if it hears a lie."
  "name": "Divine Awareness"
- "desc": "Lyra has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Lyra makes two melee attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 21\
    \ (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
  "name": "Greatsword"
- "desc": "Lyra touches another creature. The target magically regains 30 (6d8 +\
    \ 3) hit points and is freed from any curse, disease, poison, blindness, or deafness."
  "name": "Healing Touch (4/Day)"
"source":
- "PSD"
"image": "https://raw.githubusercontent.com/5etools-mirror-3/5etools-img/main/bestiary/tokens/PSD/Lyra.webp"
```
^statblock